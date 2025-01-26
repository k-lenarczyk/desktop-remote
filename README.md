﻿# Remote Control for Laptops / Desktops

## Setup
1. Clone this repository to your machine
2. Create a ```.env``` file in the frontend/ directory
3. Check your IPv4 adress in your cmd:
   ```bash
   ipconfig
   ```
4. Add a new line to the ```.env``` file like so:
   ```
   VITE_HOST_IPV4="{Your ipv4 here}"
   ```
5. Run the starting script from inside the project root directory:
   ```
   .\Start.ps1
   ```
