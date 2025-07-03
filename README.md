# Task - 7 Identify and Remove Suspicious Browser Extensions
Learn to spot and remove potentially harmful browser extensions.

# Step 1: Identify Suspicious Extensions
```
 Flags to Look For:
You don't remember installing it.

It has a vague or misleading name.

It asks for too many permissions (like accessing all your websites, clipboard, etc.).

It redirects searches or opens pop-ups.

It slows down your browser or causes crashes.
```
For Google Chrome / Edge (Chromium-based):
====

# Open Chrome and go to: chrome://extensions/

![image](https://github.com/user-attachments/assets/051a1ecf-b6ea-4642-8c31-39daf63ca2c2)

Review the list:

# Click "Details" to view permissions.

![image](https://github.com/user-attachments/assets/f882790b-18b9-439b-97a6-6c65b862770c)

```
Look for unknown, unverified, or high-permission extensions.

Disable suspicious extensions (toggle off) or click “Remove” to uninstall.
````

For Mozilla Firefox:
===

    Open Firefox and go to: about:addons

![image](https://github.com/user-attachments/assets/832052ca-282e-481a-947f-fa2e16269c52)

# Navigate to Extensions.
```
Look for:

Unknown names or recent installations you didn’t authorize.

Suspicious permissions (like reading all website data).

Click the three dots (⋮) next to the extension > Remove.
```
# Step 2: Clean Up and Secure
Run antivirus/anti-malware software (e.g., Malwarebytes, Windows Defender).

Reset browser settings (optional if you notice ongoing issues).

Check sync settings – Some extensions may return via account sync.

# Step 3: Prevent Future Issues

Install only from official web stores.

Read reviews and check permissions before installing.

Use trusted security tools like:

uBlock Origin (ad blocker)

Privacy Badger (tracker blocker)

How Malicious Extensions Harm Users
=====

# 1. Data Theft
Access to all websites: Many extensions request permission to read and modify data on all sites you visit.

Steal credentials: They can capture usernames, passwords, and credit card numbers.

Keylogging: Some log every keystroke, sending it to remote servers.

# 2. Surveillance & Tracking
Persistent user tracking via cookies, local storage, and fingerprinting.

Bypass privacy settings (like Incognito mode or anti-tracking tools).

# 3. Ad Injections and Redirects
Inserts unauthorized ads into websites (called ad injection).

Redirects search queries to malicious or scam websites.

Often monetized via affiliate fraud or malvertising.

# 4. Browser Hijacking
Changes browser settings like homepage, new tab, or default search engine.

Prevents the user from restoring original settings.

Some inject persistent background scripts to reapply changes on startup.

# 5. Privilege Escalation / Remote Code Execution
Some extensions use remote scripts, giving the attacker the ability to:

Load arbitrary malicious JavaScript.

Exploit browser vulnerabilities.

Open backdoors to system-level exploits.

# 6. Credential Phishing
Spoof login forms (e.g., fake Google or Facebook popups).

Auto-fill fake login pages using your real credentials from autofill tools.

Steal OAuth tokens or session cookies.

# 7. Cryptojacking
Uses your CPU/GPU power to mine cryptocurrency in the background.

Causes overheating, device slowdowns, and battery drain.

