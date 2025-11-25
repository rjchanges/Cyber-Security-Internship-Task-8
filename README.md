# Task 8: VPN Configuration and Analysis

## Objective
To understand the role of Virtual Private Networks (VPNs) in protecting privacy, securing communication, and masking digital identity.

## Step 1: Baseline (No VPN)
First, I checked my public IP address without any VPN connection to establish a baseline.
* **Original Location:** Mattanur, Kerala, India
* **Original IP:** 103.161.54.60
* **ISP:** M N Cable Vision

![Before VPN](image_f2c8d0.jpg)

## Step 2: VPN Setup & Connection
I used a free VPN service to establish a secure tunnel.
* **VPN Tool Used:** [Insert Name of VPN you used, e.g., ProtonVPN or Windscribe]
* **Target Server:** United States (US-West)

## Step 3: Verification (VPN Connected)
After connecting, I refreshed the IP checking tool to verify the change. The website now believes I am accessing the internet from California.
* **Masked Location:** Redwood City, California, United States
* **Masked IP:** 216.247.106.112
* **ISP:** Internet Utilities NA LLC

![After VPN](image_f2c8b4.jpg)

## Research & Analysis

### 1. What is a VPN?
A Virtual Private Network (VPN) creates a secure, encrypted tunnel between your device and the internet. It hides your real IP address by routing your traffic through a remote server, making it appear as if you are browsing from that server's location.

### 2. VPN vs. Proxy
* **VPN:** Encrypts **all** internet traffic on the device (operating system level). It is more secure.
* **Proxy:** Only redirects traffic for a specific application (like a browser). It usually does not encrypt data, meaning your ISP can still see what you are doing, even if your IP changes.

### 3. Limitations
* **Speed:** Internet speed often drops because traffic has to travel further to the VPN server and undergo encryption/decryption.
* **Trust:** You are hiding your data from your ISP, but the VPN provider can technically see it. It is crucial to use a "No-Logs" VPN.
