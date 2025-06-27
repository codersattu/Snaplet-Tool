# Snaplet Tool – Automatic Mail Dashboard Reports

**Snaplet** is a free Windows tool that automates the process of capturing full-page **Dynatrace dashboards** and emailing them as **PDF reports** — all without writing a single line of code.

---

## Use Case

Ideal for teams who want:

- Daily or weekly dashboard reports
- Visual performance snapshots in PDF
- Email automation for stakeholders who don’t log in to Dynatrace

---

## What It Does

- Opens your Dynatrace dashboard (via anonymous URL)  
- Waits for all tiles to load  
- Takes a full-page screenshot  
- Converts the screenshot into a **PDF**  
- Emails it via your Outlook desktop client  
- Generates execution logs to `logs.txt` for easy review  

---

## Files Included

You’ll receive a single **Snaplet_Tool**, no setup needed.

🛠 Just double-click the `.exe` file to launch the GUI.

---

##  Requirements

-  Windows System  
-  Outlook desktop app configured  
-  Chrome browser installed  
-  Dynatrace dashboard URL must be shared as an **anonymous URL**

To generate such a URL in Dynatrace:
1. Open your dashboard  
2. Click **Share**  
3. Enable **Anonymous access**  
4. Copy the public link  

---

## How to Use

1. Run the `Snaplet.exe`
2. Enter:
   - Dynatrace dashboard URL (anonymous)
   - Email recipients
   - Subject of the mail
3. Click **Generate EXE**

This will create another executable file based on your inputs.

 You can then:
- Run that generated file manually
- Or schedule it using **Windows Task Scheduler** to automate dashboard reporting

---

## Logs

Every time the report EXE runs, a `logs.txt` file will be updated with timestamped actions including:
- Dashboard loading
- PDF generation
- Email delivery

The top of the log includes this disclaimer:

> _As it's a custom solution which is not part of the direct product, there is no direct support if this solution doesn't work in future._

---

## Security & Privacy

- No internet connections are made.
- No credentials or tokens are needed.
- Dashboard data is accessed **anonymously** and handled locally.

---

## Disclaimer

**Snaplet** is a custom-built utility created to support Dynatrace users with visual reporting needs.  
It is **not officially supported by Dynatrace**, and no future guarantees are implied if changes occur in the platform or Outlook.

---

## Created By

**Abhishek Satpathy**  
_Dynatrace Consultant | MCT_  
📧 abhishek.satpathy@dynatrace.com
