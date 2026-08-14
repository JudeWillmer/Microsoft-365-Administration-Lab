# Teams and SharePoint

## Overview

This section covers the core **Microsoft Teams** and **SharePoint** administration tasks I completed within the **Microsoft 365** environment. I configured organisation-wide **Teams settings**, **Guest Access**, and **Meeting Policies**, before creating a **SharePoint Team Site** and managing its **permissions, membership, and user access**. These tasks demonstrate practical collaboration, access management, and user support skills commonly used within an **IT Support** environment.

---

# Task 1 - Configure Microsoft Teams Organization Settings

## Objective

Configure **Microsoft Teams organization-wide settings** to control which file storage integrations are available across the organisation.

---

## Implementation

I configured the **Teams Settings** within the **Microsoft Teams admin center** by reviewing the organisation-wide file storage options. Following the demonstrated configuration, I disabled the available third-party cloud storage providers within the **Files** section and saved the updated settings.

After saving the configuration, I verified that the changes were successfully applied by confirming the on-screen success notification.

---

## Navigation

```text
Microsoft Teams admin center
└─ Teams
   └─ Teams settings
```

---

## Outcome

I successfully configured the **Microsoft Teams organization settings** by updating the available file storage integrations and confirmed that the changes were successfully saved.

---

## Screenshots

**Figure 1:** Configuring the **Microsoft Teams organization settings** by updating the available **Files** integrations and confirming the successful save notification.

<img width="1919" height="913" alt="01 – Configure Microsoft Teams Organization Settings" src="https://github.com/user-attachments/assets/9c6b68e0-9d04-41ed-ac62-7c7b18c7cca2" />

# Task 2 - Configure Guest Access

## Objective

Configure **Guest Access** in the **Microsoft Teams Admin Center** to control what external users are permitted to do within Microsoft Teams. This is a common security administration task used to manage collaboration with users outside the organisation.

---

## Implementation

I configured the **Guest Access** settings within the **Microsoft Teams Admin Center** by disabling guest access for external users. After saving the configuration, I verified that the changes were successfully applied and confirmed by the on-screen success notification.

---

## Navigation

```text
Microsoft Teams admin center
└─ External collaboration
   └─ Guest access
```

---

## Outcome

I successfully configured the **Guest Access** settings by disabling external guest access and confirmed the configuration was saved successfully.

---

## Screenshots

**Figure 1:** Guest Access settings configured within the **Microsoft Teams Admin Center**, showing guest access disabled and the successful save confirmation message.

<img width="1919" height="915" alt="02 – Configure Guest Access" src="https://github.com/user-attachments/assets/4cce4e1c-437f-4c43-84c3-acec65d37115" />

# Task 3 - Configure Meeting Policies

## Objective

Configure **Meeting Policies** in the **Microsoft Teams Admin Center** to control meeting security settings such as anonymous meeting access and meeting recording.

---

## Implementation

I configured the **Global Meeting Policy** within the **Microsoft Teams Admin Center** by disabling anonymous meeting access and meeting recording to demonstrate common security configurations used to protect Microsoft Teams meetings.

---

## Navigation

```text
Microsoft Teams admin center
└── Meetings
    └── Meeting policies
        └── Global (Org-wide default)
```

---

## Outcome

I successfully configured the **Global Meeting Policy** by disabling anonymous meeting access and meeting recording, then confirmed the policy was successfully updated.

---

## Screenshots

**Figure 1:** Meeting Join & Lobby settings showing **Anonymous users** configured.

<img width="1919" height="913" alt="03 – Configure Meeting Policies" src="https://github.com/user-attachments/assets/afa02fc3-0dba-4b0d-b8ed-61c3a85e6036" />

**Figure 2:** Recording & Transcription settings showing **Meeting recording** configured.

<img width="1919" height="915" alt="04 – Configure Meeting Policies" src="https://github.com/user-attachments/assets/7732c734-a0dc-4aba-854b-69f895ab958f" />

**Figure 3:** **Meeting Policies** page confirming the policy was successfully updated.

<img width="1919" height="915" alt="05 – Configure Meeting Policies" src="https://github.com/user-attachments/assets/881cb18f-1416-4049-9845-c3900a36af66" />

---

# Task 4 - Create a SharePoint Team Site

## Objective

Create a **SharePoint Team Site** within the **SharePoint Admin Center** to provide a dedicated collaboration space for the IT Help Desk team. This demonstrates a common Microsoft 365 administration task used to provision departmental sites for document management and team collaboration.

---

## Implementation

I created a new **SharePoint Team Site** using the **IT Help Desk** template and configured the site with an appropriate name, description, group owner, and private access permissions. After completing the site creation wizard, I verified that the new site was successfully created and appeared within the list of Active Sites.

---

## Navigation

```text
Microsoft 365 Admin Center
└── SharePoint
    └── Active sites
        └── Create
            └── Team site
```

---

## Outcome

I successfully created a new **SharePoint Team Site** for the Help Desk department and confirmed that it was provisioned correctly within the SharePoint Admin Center. The site is now available for collaboration, document storage, and future permission management.

---

## Screenshots

**Figure 1:** **SharePoint Team Site** creation wizard showing the **Site name**, **Site description**, **Group owner**, and **Site configuration**.

<img width="1919" height="917" alt="06 – Create a SharePoint Team Site" src="https://github.com/user-attachments/assets/f734d880-f902-4ef1-9deb-87c2a6d4171c" />

**Figure 2:** Newly created **Helpdesk** Team Site displayed within **Active Sites**, confirming successful site creation.

<img width="1919" height="914" alt="07 – Create a SharePoint Team Site" src="https://github.com/user-attachments/assets/4721e666-87c7-4331-9e86-3a85dd1e7065" />

# Task 5 - Manage SharePoint Site Permissions

## Objective

Manage **SharePoint Site Permissions** for the **Helpdesk** team site by reviewing existing permission groups, controlling member access, and adding a new member to the site.

---

## Implementation

I managed the **SharePoint Site Permissions** for the **Helpdesk** team site by accessing the site's permissions panel and reviewing the configured **Owners**, **Members**, and **Visitors** groups. I verified the site's sharing configuration and added a new member to the **Helpdesk Members** group to grant access to the site.

---

## Navigation

```text
Microsoft 365 Admin Center
└─ SharePoint
   └─ Active sites
      └─ Helpdesk
         └─ View site
            └─ Settings
               └─ Site permissions
```

---

## Outcome

I successfully managed the **SharePoint Site Permissions** by reviewing the site's permission groups and adding a new member to the **Helpdesk Members** group. This ensures that authorized users can securely access the SharePoint site while maintaining appropriate permission management.

---

## Screenshots

**Figure 1:** SharePoint **Site Permissions** panel for the **Helpdesk** site, displaying the configured **Owners**, **Members**, and **Visitors** groups, along with the available site sharing management options.

<img width="1919" height="916" alt="08 – Manage SharePoint Site Permissions" src="https://github.com/user-attachments/assets/ff3a0e06-74de-482a-a9cb-44f900dcbc66" />

**Figure 2:** **Group membership** page showing the successful addition of a new member to the **Helpdesk Members** group, confirming that site permissions were updated successfully.

<img width="1919" height="916" alt="09 – Manage SharePoint Site Permissions" src="https://github.com/user-attachments/assets/a36cb3c0-c3e9-4de4-9200-5e8078352c0d" />

# Task 6 - Share a SharePoint Site

## Objective

Share an existing **SharePoint Team Site** with another user to provide access for collaboration. This demonstrates a common Help Desk task of granting users access to SharePoint resources.

---

## Implementation

I shared the **Helpdesk** SharePoint Team Site by opening the site's **Share** option, selecting a user, and sending an invitation to access the site. After the invitation was sent, SharePoint confirmed that the user had been successfully invited.

---

## Navigation

```text
Microsoft 365 Admin Center
└─ SharePoint
   └─ Active sites
      └─ Helpdesk
         └─ View site
            └─ Share
```

---

## Outcome

I successfully shared the **Helpdesk** SharePoint Team Site with a user by sending a SharePoint invitation. The invitation was accepted by SharePoint, confirming that access had been granted through the site's sharing feature.

---

## Screenshots

**Figure 1:** Share window for the **Helpdesk** SharePoint Team Site with the selected user added before sending the invitation.

<img width="1919" height="913" alt="10 – Share a SharePoint Site" src="https://github.com/user-attachments/assets/d7dd3d69-0d8c-445f-aea7-d703efe7be54" />

**Figure 2:** **SharePoint** confirmation showing that the invitation was successfully sent to the selected user.

<img width="1918" height="913" alt="11 – Share a SharePoint Site" src="https://github.com/user-attachments/assets/f1bd0bfd-f7bf-443f-ae45-78a7cd39b7ea" />
