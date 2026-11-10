---
sidebar_position: 4
title: Roles, Permission & User Groups
description: Control who can see and do what in Emphyra using roles and user groups.
---

# Roles, Permissions and User Groups

This guide explains how to control who can see and do what in Emphyra. Access is managed in two parts: **Roles** define a set of permissions, and **User Groups** assign those roles to many users at once.

## Where to find it

In the left sidebar, open the **Roles** or **User Groups** page. Both sit in the same section as Home, Employer, Employees, Audit, Leave Approvals and Leave Settings.

## Roles & Permissions

The **Roles & Permissions** page (subtitle: *Manage access levels for your team*) lists every role in your organisation. By default, an **Admin** role is created for the administrator, with every permission needed to manage the system.

Each role in the list shows:

- **Role name**, for example *Admin*.
- **Permission count**, for example *44 permissions*.
- **Permission tags**, a preview of the permissions in the role. Extra permissions are collapsed into a **+N more** tag.

### Understanding permission names

Permissions follow the pattern `resource:action`.

| Example | Meaning |
| --- | --- |
| `employee-personal:view` | View employees' personal information |
| `leave-type:view` | View leave types |
| `leave-type:add` | Create new leave types |
| `employer-contact-info:view` | View the employer's contact information |
| `employer-setting:view` | View employer settings |

The part before the colon is the area of the system. The part after it is what the user may do there (such as `view` or `add`).

### Adding a role

1. Go to **Roles**.
2. Select **Add Role** in the top-right corner.
3. Complete the form that opens and save.

## User Groups

The **User Groups** page (subtitle: *Assign roles to multiple users at once*) lists your groups, such as *Administrators*. Instead of assigning roles to people one by one, put users in a group and give the group the roles.

To change an existing group, select the **pencil icon** on its row.

### Creating a user group

1. Go to **User Groups**.
2. Select **Add Group** in the top-right corner. The **Create user group** window opens.
3. Fill in the form:

   | Field | Required | Description |
   | --- | --- | --- |
   | **Name** | Yes | A short name for the group, e.g. *Administrators*. |
   | **Description** | No | What the group is for. |
   | **Assign Roles** | Yes | Choose one or more roles from the dropdown. Members receive all permissions in these roles. |
   | **Add Users** | Yes | Choose the users who belong to the group. The list may show a loading spinner for a moment while users load. |

4. Select **Save**.

To cancel, select the **X** in the top-right corner of the window.

:::tip

- Create roles around job functions, then attach them to groups, so access stays consistent.
- Give each user only the permissions they need.
- Changes to access are tracked on the **Audit** page.

:::

