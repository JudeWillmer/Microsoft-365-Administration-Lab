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

I investigated an Outlook search issue by accessing the **Search** settings within **Outlook Options** and opening the **Windows Indexing Options**.

From the **Advanced Index Settings**, I reviewed the indexing configuration and identified the **Rebuild** option used to recreate the Windows Search index. Rebuilding the index refreshes Outlook's search database and is a common Help Desk troubleshooting step when users experience missing or incomplete search results.

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

I successfully identified the Windows Search indexing configuration and verified the process for rebuilding the Outlook search index. This troubleshooting method is commonly performed when Outlook search returns incomplete results or fails to locate emails correctly.

---

## Scenario

A user contacted the IT Help Desk after reporting that Outlook search was unable to find recent emails. I investigated the issue by reviewing the Outlook **Search** settings and opening the **Windows Indexing Options**. From the **Advanced Index Settings**, I located the **Rebuild** option used to recreate the Windows Search index before advising the user that rebuilding the index is a standard troubleshooting step for resolving Outlook search issues.

---

## Screenshot

**Figure 1:** Outlook **Search Options** showing access to **Windows Indexing Options** for troubleshooting Outlook search functionality.

<img width="1919" height="914" alt="05 – Troubleshoot Outlook Search Issues" src="https://github.com/user-attachments/assets/8bf04a1e-a119-4d18-af6c-0224b8f65ff7" />

**Figure 2:** **Advanced Index Settings** displaying the **Rebuild** option used to recreate the Windows Search index.

<img width="1919" height="914" alt="06 – Troubleshoot Outlook Search Issues" src="https://github.com/user-attachments/assets/335a7cbe-7e57-45d1-a746-939175dd47f1" />
