# Task 1 - Launch Outlook in Safe Mode

## Objective

Diagnose an Outlook startup issue by launching Outlook in Safe Mode to determine whether the issue is caused by a corrupted COM add-in or Outlook customization.

---

## Implementation

I launched Outlook in Safe Mode using the Run dialog (`outlook.exe /safe`). Safe Mode disables COM add-ins and Outlook customizations, allowing Outlook to start with only the essential components. This is a common first troubleshooting step used to determine whether an Outlook startup issue is caused by a faulty add-in rather than the Outlook application itself.

---

## Navigation

```text
Windows
└── Run
    └── outlook.exe /safe
```

---

## Outcome

Outlook launched successfully in Safe Mode, confirming that Outlook could start without loading COM add-ins. This indicated that the Outlook installation was functional and that any startup issue was more likely related to a corrupted add-in or Outlook profile.

---

## Scenario

A user contacts the IT Help Desk after reporting that Microsoft Outlook crashes or fails to open. I investigated the issue by launching Outlook in Safe Mode, which disables COM add-ins and customizations. Outlook opened successfully, confirming that the installation was functioning correctly and indicating that the issue was most likely caused by a faulty add-in or user profile. The next troubleshooting step would be to disable unnecessary add-ins or create a new Outlook profile if required.

---

## Screenshot

**Figure 1:** Running `outlook.exe /safe` from the Run dialog.

<img width="1919" height="914" alt="01 – Launch Outlook in Safe Mode" src="https://github.com/user-attachments/assets/f1b41f59-dbcc-4d1b-b641-bb2686f808f1" />

**Figure 2:** Outlook successfully launched in Safe Mode.

<img width="1918" height="915" alt="02 – Launch Outlook in Safe Mode" src="https://github.com/user-attachments/assets/e2c83371-2fa6-4f07-8003-28b9d5bd57d2" />
