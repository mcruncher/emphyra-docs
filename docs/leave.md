---
id: leave
title: Leave
sidebar_label: Leave Settings
sidebar_position: 5
description: Set up leave types, leave policies, annual leave accrual and leave policy groups in Emphyra.
---

# Leave Settings

Leave Settings is where you define how leave works in your organisation: which kinds of leave exist, how many days employees are entitled to, and what happens to unused days at the end of the year.

To open it, select **Leave Settings** in the left sidebar.

The page is split into four tabs:

| Tab | What it is for |
| --- | --- |
| **Leave Type** | The kinds of leave employees can take, such as Annual or Sick. |
| **Leave Policies** | The rules for each leave type, including who is entitled and how many days. |
| **Annual Leave Accrual** | How annual leave resets each year and how carry forward works. |
| **Leave Policy Groups** | Collections of leave policies. A *Default Leave Policy Group* is provided. |

:::tip

We recommend setting things up in this order: **Leave Type**, then **Leave Policies**, then **Annual Leave Accrual**.

:::

## Leave Type

The **Leave Type** tab lists every kind of leave available. Each row shows:

- **Name**, the name of the leave type.
- **Category**, shown as a coloured label next to the name.
- **Description**, an optional explanation.

The following leave types are available by default:

- Hospitalization
- Sick
- Maternity
- Annual
- Paternity

To create another leave type, select **Add** in the top-right corner of the list.

## Leave Policies

A leave policy sets the rules for one leave type. For example, you can create a policy that gives employees 10 days of annual leave once they have worked for a year.

### Creating a leave policy

1. Open the **Leave Policies** tab.
2. Select **Add** in the top-right corner. The **Leave Policy** panel opens.
3. Fill in the form:

   | Field | Required | Description |
   | --- | --- | --- |
   | **Name** | Yes | A short name for the policy. |
   | **Description** | No | What the policy covers. |
   | **Leave Type** | Yes | Choose the leave type this policy applies to, such as Annual or Sick. |
   | **Effective From** | No | The date the policy starts. |
   | **Effective Through** | No | The date the policy ends. |
   | **Leave Entitlement** | No | How many days employees are entitled to. See below. |
   | **Active** | No | Turn on to make the policy active. |

4. Select **Save**.

To cancel, select the **X** in the top-right corner of the panel.

### Leave entitlement

The **Leave Entitlement** section decides how many days an employee gets, based on how long they have worked for the organisation. It has three fields:

| Field | Description |
| --- | --- |
| **Min. Length of Service** | The minimum amount of time an employee must have worked, for example `1`. |
| **Unit** | The unit for the length of service, for example *Years*. |
| **Entitled Days** | The number of leave days per year, for example `10`. |

As you type, a summary appears below the fields so you can check the rule reads correctly. For example:

> This leave entitlement applies to employees with a minimum length of service of **1 Years**, entitling them to **10** days of leave per year.

## Annual Leave Accrual

The **Annual Leave Accrual** tab controls how annual leave is reset each year and how unused days are carried forward. The tab shows the current settings: **Reset Type**, **Carry Forward Days** and **Carry Forward Expiry in Months**.

To change them, select the **pencil icon** at the top-right of the settings. The **Annual Leave Accrual** window opens:

| Field | Required | Description |
| --- | --- | --- |
| **Reset Type** | Yes | Choose when employees' annual leave resets. |
| **Carry Forward Days** | No | The number of unused days an employee can carry into the next year. Enter `0` for none. |
| **Carry Forward Expiry in Months** | No | How many months carried-forward days remain valid. Enter `0` for no expiry period. |
| **Leave Entitlement Type** | Yes | Choose the type of leave entitlement the accrual rules apply to. |

Select **Save** to apply your changes.

## Leave Policy Groups

The **Leave Policy Groups** tab lists your leave policy groups. Each row shows the group **Name**. 

:::tip

A **Default Leave Policy Group** is already created for you. It contains default leave policies that follow the Employment Act, so your organisation can start using Emphyra without setting everything up from scratch.

You can keep using these default policies, or create your own leave policies to suit how your organisation works.

:::


To create a new group, select **Add** in the top-right corner of the list. When the list has more than one page, use the arrows at the bottom-right to move between pages.

