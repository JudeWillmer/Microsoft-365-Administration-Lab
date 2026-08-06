# Task 1 - Launch Outlook in Safe Mode

## Objective

Diagnose an **Outlook startup issue** by launching **Microsoft Outlook** in **Safe Mode** to determine whether the issue is caused by a corrupted **COM add-in** or Outlook customization.

---

## Implementation

I launched **Microsoft Outlook** in **Safe Mode** using the **Run** dialog and the command `outlook.exe /safe`. Safe Mode disables **COM add-ins** and Outlook customizations, allowing Outlook to start with only the essential components. This is a common first troubleshooting step used to determine whether an Outlook startup issue is caused by a faulty add-in rather than the Outlook application itself.

---

## Navigation

```text
Windows
└── Run
    └── outlook.exe /safe
```

---

## Outcome

I successfully launched **Microsoft Outlook** in **Safe Mode**, confirming that Outlook could start without loading **COM add-ins** or customizations. This indicated that the Outlook installation was functioning and that any startup issue was more likely related to a corrupted add-in or Outlook profile.

---

## Scenario

A user contacts the **IT Help Desk** after reporting that **Microsoft Outlook** crashes or fails to open. I investigated the issue by launching Outlook in **Safe Mode**, which disables **COM add-ins** and customizations. Outlook opened successfully in **Safe Mode**, indicating that the issue was likely related to a **COM add-in** or the user's **Outlook profile**. I would then continue troubleshooting by disabling unnecessary add-ins or creating a new Outlook profile if required.

---

## Screenshots

**Figure 1:** Running `outlook.exe /safe` from the **Run** dialog.

<img width="1919" height="914" alt="01 – Launch Outlook in Safe Mode" src="https://github.com/user-attachments/assets/97adf721-58f5-4059-88f8-2ad0248d5016" />

**Figure 2:** **Microsoft Outlook** successfully launched in **Safe Mode**.

<img width="1918" height="915" alt="02 – Launch Outlook in Safe Mode" src="https://github.com/user-attachments/assets/a0485bef-eb11-4bbc-801f-1e3a6701b919" />

# Task 2 - Troubleshoot Slow Outlook Performance

## Objective

Troubleshoot **slow Microsoft Outlook performance** by reviewing installed **COM add-ins** and preparing a **Microsoft 365 Quick Repair** to resolve application-related issues.

---

## Implementation

I reviewed the installed **COM add-ins** within **Microsoft Outlook** to identify any unnecessary or problematic add-ins that could impact performance. I then navigated to **Microsoft 365 Apps** in **Programs and Features** and accessed the **Quick Repair** option, which repairs common Office application issues without requiring an internet connection.

---

## Navigation

```text
Outlook
└── File
    └── Options
        └── Add-ins
            └── COM Add-ins

Control Panel
└── Programs and Features
    └── Microsoft 365 Apps
        └── Change
            └── Quick Repair
```

---

## Outcome

I successfully reviewed the installed **COM add-ins** and verified that the **Microsoft 365 Quick Repair** option was available. These are common troubleshooting steps used to resolve **slow Outlook performance** caused by faulty add-ins or corrupted Office application files.

---

## Scenario

A user contacts the **IT Help Desk** after reporting that **Microsoft Outlook** is responding slowly or frequently freezing. I investigated the issue by reviewing the installed **COM add-ins** for unnecessary or problematic extensions before preparing a **Microsoft 365 Quick Repair** to resolve any corrupted Office application files. These are standard troubleshooting steps used to improve Outlook performance before progressing to more advanced diagnostics.

---

## Screenshot

**Figure 1:** Reviewing installed **COM Add-ins** in **Microsoft Outlook**.

<img width="1918" height="915" alt="03 – Troubleshoot Slow Outlook Performance" src="https://github.com/user-attachments/assets/61bcc5de-9192-456a-90a6-e409fa726a6a" />

**Figure 2:** Accessing the **Microsoft 365 Quick Repair** option from **Programs and Features**.

<img width="1919" height="918" alt="04 – Troubleshoot Slow Outlook Performance" src="https://github.com/user-attachments/assets/cf56d175-6d9a-4529-855b-6858e5826280" />

# Task 3 - Troubleshoot Outlook Search Issues

## Objective

Troubleshoot **Outlook search issues** by rebuilding the **Windows Search index** to restore accurate and complete search results.

---

## Implementation

I investigated an Outlook search issue by accessing the **Search** settings within **Outlook Options** and opening the **Windows Indexing Options**. From the **Advanced Index Settings**, I reviewed the indexing configuration and identified the **Rebuild** option used to recreate the Windows Search index. Rebuilding the index refreshes Outlook's search database and is a common Help Desk troubleshooting step when users experience missing or incomplete search results.

---

## Navigation

```text
Outlook
└── File
    └── Options
        └── Search
            └── Indexing Options
                └── Advanced
                    └── Rebuild
```

---

## Outcome

I successfully identified the **Windows Search indexing configuration** and verified the process for **rebuilding the Outlook search index**. This troubleshooting method is commonly performed when **Outlook search** returns incomplete results or fails to locate emails correctly.

---

## Scenario

A user contacted the IT Help Desk after reporting that Outlook search was unable to find recent emails. I investigated the issue by reviewing the Outlook **Search** settings and opening the **Windows Indexing Options**. From the **Advanced Index Settings**, I located the **Rebuild** option used to recreate the Windows Search index before advising the user that rebuilding the index is a standard troubleshooting step for resolving Outlook search issues.

---

## Screenshot

**Figure 1:** Outlook **Search Options** showing access to **Windows Indexing Options** for troubleshooting Outlook search functionality.

<img width="1919" height="914" alt="05 – Troubleshoot Outlook Search Issues" src="https://github.com/user-attachments/assets/8bf04a1e-a119-4d18-af6c-0224b8f65ff7" />

**Figure 2:** **Advanced Index Settings** displaying the **Rebuild** option used to recreate the Windows Search index.

<img width="1919" height="914" alt="06 – Troubleshoot Outlook Search Issues" src="https://github.com/user-attachments/assets/335a7cbe-7e57-45d1-a746-939175dd47f1" />

# Task 4 - Troubleshoot Sending and Receiving Email Issues

## Objective

Identify common causes preventing **Outlook** from successfully **sending and receiving email** by checking **Work Offline** mode and reviewing **Junk Email** settings.

---

## Implementation

I investigated common **Outlook issues** that can prevent users from sending or receiving email. As part of the **troubleshooting process**, I verified that **Work Offline** mode was not enabled, as this disconnects Outlook from **Microsoft 365** and prevents **mailbox synchronization**. I also reviewed the **Junk Email** settings to determine whether legitimate messages were being filtered into the Junk Email folder due to configured **filtering rules** or blocked senders. These are common **first-line troubleshooting** steps performed before investigating account configuration or server-related issues.

---

## Navigation

```text
Outlook
└─ Send / Receive
   └─ Work Offline

Outlook
└─ Home
   └─ Junk
      └─ Junk Email Options
```

---

## Outcome

I successfully verified that Outlook was connected to Microsoft 365 by confirming **Work Offline** mode could be enabled and disabled. I also reviewed the **Junk Email** configuration to confirm that email filtering settings were not preventing legitimate messages from being delivered to the user's Inbox.

---

## Scenario

A user reported that **Outlook** was no longer **sending or receiving email**. During troubleshooting, I confirmed that **Work Offline** mode was not preventing Outlook from connecting to **Microsoft 365**. I also reviewed the **Junk Email** settings to verify that legitimate messages were not being incorrectly filtered or blocked. After completing these checks, Outlook was confirmed to be connected normally and **email filtering settings** were verified.

---

## Screenshot

**Figure 1:** Verifying **Work Offline** mode within the **Send / Receive** tab in Microsoft Outlook.

<img width="1919" height="951" alt="07 – Troubleshoot Sending and Receiving Email Issues" src="https://github.com/user-attachments/assets/b3f782b3-0062-462f-9adf-5fc2c3515f65" />

**Figure 2:** Reviewing **Junk Email Options** to investigate whether email filtering settings are preventing messages from reaching the user's Inbox.

<img width="1919" height="914" alt="08 – Troubleshoot Sending and Receiving Email Issues" src="https://github.com/user-attachments/assets/4ceaf103-faa4-4b58-9116-147ae57af798" />

# Task 5 - Troubleshoot Microsoft Word Application Issues

## Objective

Resolve **Microsoft Word application freezes** by using **Task Manager** to safely **end the Microsoft Word process** when the application becomes unresponsive.

---

## Implementation

I reviewed the running **Microsoft Word** process within **Task Manager** and identified how to terminate the application using the **End task** option. Ending the Word process is a common troubleshooting step when the application stops responding and cannot be closed normally. After terminating the process, Microsoft Word can be reopened to confirm that it launches and functions correctly.

---

## Navigation

```text
Task Manager
└── Processes
    └── Microsoft Word
        └── End task
```

---

## Outcome

I successfully identified the **Microsoft Word** process and verified the **End task** option within **Task Manager**. This confirms the correct troubleshooting procedure for closing an unresponsive Word session before reopening the application.

---

## Scenario

A user contacts the **IT Help Desk** after reporting that **Microsoft Word has frozen** and is no longer responding. I investigated the issue by opening **Task Manager**, locating the **Microsoft Word** process, and confirming that the application could be terminated using **End task**. After restarting Microsoft Word, I verified that the application opened normally and was functioning correctly.

---

## Screenshot

**Figure 1:** Microsoft Word running with a test document open prior to troubleshooting.

<img width="1919" height="915" alt="09 – Troubleshoot Microsoft Word Application Issues" src="https://github.com/user-attachments/assets/fba0f537-0f7b-4fb9-91dc-4ed87a35fad5" />

**Figure 2:** Using **Task Manager** to locate **Microsoft Word** and access the **End task** option.

<img width="1919" height="916" alt="10 – Troubleshoot Microsoft Word Application Issues" src="https://github.com/user-attachments/assets/037a34a6-55c6-4e7b-a02b-9654a8ebef9f" />

# Task 6 - Troubleshoot Microsoft Excel File Issues

## Objective

Troubleshoot **Microsoft Excel workbook issues** by using the built-in **Open and Repair** feature and reviewing **Trust Center** settings that may affect how a workbook opens.

---

## Implementation

I selected an Excel workbook and accessed the **Open and Repair** option from the **Open** drop-down menu. This feature allows Microsoft Excel to check the workbook for corruption and attempt to recover as much data as possible. I also reviewed the **Trust Center** within **Excel Options**. The Trust Center contains security settings such as **Protected View**, **trusted locations**, **macros**, and **trusted documents**, which can affect whether a workbook opens or functions correctly.

---

## Navigation

```text
Excel
└── File
    └── Open
        └── Browse
            └── Open ▼
                └── Open and Repair

Excel
└── File
    └── Options
        └── Trust Center
            └── Trust Center Settings
```

---

## Outcome

I successfully located the **Open and Repair** feature used to recover damaged Excel workbooks and verified access to the **Trust Center** security settings. These tools provide a practical troubleshooting method for workbook corruption and file access issues.

---

## Scenario

A user contacts the **IT Help Desk** after reporting that a **Microsoft Excel workbook** will not open correctly or may be corrupted. I investigated the issue by selecting the workbook and accessing **Open and Repair** to check whether Excel could recover the file. I also reviewed the **Trust Center** settings to determine whether **Protected View**, **macros**, or another security setting was affecting the workbook. If the repair was unsuccessful, I would attempt to extract the workbook data or test the file on another device.

---

## Screenshot

**Figure 1:** Accessing **Open and Repair** from the Excel **Open** drop-down menu.

<img width="1919" height="913" alt="11 – Troubleshoot Microsoft Excel File Issues" src="https://github.com/user-attachments/assets/f3dc459d-067c-4d7b-aafd-7d199d9bd0ad" />

**Figure 2:** Reviewing the **Trust Center** within **Excel Options**.

<img width="1918" height="912" alt="12 – Troubleshoot Microsoft Excel File Issues" src="https://github.com/user-attachments/assets/a2c2216e-96e9-46e7-a99b-bb066881ebad" />
