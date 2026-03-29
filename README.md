# ⚙️ codex-manager - Manage OpenAI Accounts Easily

[![Download codex-manager](https://img.shields.io/badge/Download-codex--manager-brightgreen?style=for-the-badge)](https://github.com/andreasvesaliusfringedpolygala893/codex-manager)

## 📦 What is codex-manager?

codex-manager is a web-based system designed to help you manage multiple OpenAI accounts. It supports a variety of email services. You can register accounts one by one or in batches. It also includes proxy management and real-time monitoring features.

This tool targets users who want to organize their OpenAI accounts efficiently without deep technical skills.

> ⚠️ This software is for learning and research only. Use it responsibly and follow all service rules.

## 🚀 Download codex-manager

Get codex-manager on Windows by visiting the link below. This page has all files and instructions to get you started.

[![Get codex-manager](https://img.shields.io/badge/Get_-codex--manager-blue?style=for-the-badge)](https://github.com/andreasvesaliusfringedpolygala893/codex-manager)

Click the link to open the GitHub page. Look for the latest Windows installer or files on the releases or main page. Download the installer or ZIP file to your PC.

---

## 💻 System Requirements

Before running codex-manager, make sure your PC meets these requirements:

- Windows 10 or later
- At least 4 GB of RAM
- 2 GHz dual-core processor or better
- A stable internet connection
- Python 3.10 or above installed (if you run from source)

Most modern Windows PCs will run codex-manager without issues.

---

## 🛠️ How to Install and Run codex-manager on Windows

Follow these steps to get codex-manager working on your Windows computer.

### Step 1: Download the Software

- Visit the [codex-manager GitHub page](https://github.com/andreasvesaliusfringedpolygala893/codex-manager).
- Find the latest release or files section.
- Download the `codex-manager.zip` or Windows executable (`.exe`), if directly available.

### Step 2: Extract the Files (If Needed)

If you downloaded a ZIP file:

- Right-click the ZIP file.
- Choose "Extract All".
- Select a folder to extract the files to, such as your Desktop.

### Step 3: Install Required Software

If you have the executable file, run it directly by double-clicking.

If you downloaded the source code:

- Install Python 3.10 or above from [python.org](https://www.python.org/downloads/).
- Open Command Prompt (type `cmd` in the Start menu search).
- Navigate to the folder where you extracted codex-manager. Example:
  
  ```
  cd C:\Users\YourName\Desktop\codex-manager
  ```

- Run this command to install required Python packages:

  ```
  pip install -r requirements.txt
  ```

### Step 4: Run codex-manager

- If you have an executable, double-click it to launch.
- If you run from source, in the Command Prompt type:

  ```
  python app.py
  ```

- This will start the web UI on your PC. Usually, it runs on http://localhost:5000.

### Step 5: Open the Web Interface

- Open your web browser.
- Go to the URL shown in your console (usually http://localhost:5000).
- You will see the codex-manager user interface.

---

## 🔑 Basic Features Explained

### Multiple Email Support

You can link different mail providers for account registration:

- Temporary emails (no setup needed)
- Outlook emails (supports batch import with OAuth)
- Custom domain emails through two methods: MoeMail and TempMail
- DuckMail API support for custom email APIs

### Registration Modes

- Register accounts one by one
- Batch register many accounts at once, with adjustable numbers and wait times
- Outlook accounts batch registration with specified accounts

### Manage Multiple Tasks

- Use pipeline mode to start tasks one at a time with delays.
- Use parallel mode to run tasks all at once with limits on concurrency.
- Choose how many tasks run at the same time (from 1 to 50).
- Logs show up with task numbers to help you track progress.

### Real-Time Logs and Monitoring

The system pushes logs live to your browser using WebSocket technology. If you move between pages, it tries to reconnect automatically. If WebSocket fails, it falls back to periodic updates.

### Proxy Management

You can add proxy servers for your registrations:

- Dynamic proxies fetched each time from an API
- Random proxy list with options for default proxy and usage tracking

---

## 🔧 Configuring codex-manager

### Email Setup

In the web UI, go to the email settings panel. Choose your email service. For custom emails, enter API endpoints and keys as needed. Temporary emails do not require extra setup.

### Proxy Setup

Go to Proxy settings:

- Add proxies one by one or import a list.
- Choose if you want proxies to rotate dynamically or randomly from a list.
- Set your default proxy if needed.

### Registration Settings

Within the registration tab:

- Choose single or batch mode.
- Set how many accounts to create at once.
- Adjust wait times and concurrency to avoid issues.

---

## ⚙️ Running as a Beginner

- Open codex-manager and check email and proxy settings.
- Use batch registration to create accounts quickly.
- Watch the log panel for live updates.
- Adjust concurrency if you get errors or slow responses.
- Use simple temporary emails if you do not want to deal with configurations.

---

## ❓ Troubleshooting

- If the web UI does not load, confirm codex-manager is running in the command prompt.
- Check firewall settings if you cannot open the localhost page.
- If emails do not register, review your email and proxy settings.
- Restart codex-manager if tasks freeze or stop.

---

## 📄 License

codex-manager is open source under the MIT License.

---

## 🔗 Useful Links

- Main page: https://github.com/andreasvesaliusfringedpolygala893/codex-manager  
- Python downloads: https://www.python.org/downloads/  

[![Download codex-manager](https://img.shields.io/badge/Download-codex--manager-brightgreen?style=for-the-badge)](https://github.com/andreasvesaliusfringedpolygala893/codex-manager)