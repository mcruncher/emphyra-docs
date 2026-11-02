---
sidebar_position: 3
title: Employees
---

# Employees

The **Employees** page is where you keep your team's records in Emphyra. In this guide you will learn how to:

1. Set up automatic employee codes (Auto ID generation)
2. View your employee list
3. Add an employee manually
4. Import employees from a CSV file (ideal for migrating from another system)
5. Export your employee list

---

## Set Up Auto ID Generation

Every employee in an Organization needs a unique **Employee code**. Instead of typing each code yourself, you can let Emphyra generate them for you. This is configured once, in **Employer Setting**.

### Why use Auto ID generation?

- **Saves time.** No need to think of a new code for every new hire.
- **No duplicates.** Emphyra increments the number for you, so two employees never share the same code.
- **Consistent format.** Every code follows the same pattern (for example, `EMP-0001`, `EMP-0002`, `EMP-0003`), which keeps your records tidy and easy to search.
- **Fewer mistakes.** Less manual typing means fewer typos and mismatched records.

### How to set it up

1. Open **Employer Setting**.
2. Turn on the **Auto ID generation** toggle.
3. In **Prefix**, type the text you want to appear before every code, for example `EMP-`. Leave it blank if you don't want a prefix.
4. In **Start value**, enter the number the sequence should start from, for example `0001`. The next employee you create will use this number, and each one after that increases by one automatically.
5. Click **Save**.

:::tip
Decide on your prefix and start value before you add or import employees, so all your codes follow the same pattern from day one.
:::

:::note
Auto ID generation affects employees created **after** you save the setting. Employee codes that already exist are not changed.
:::

---

## View the Employee List

Open **Employees** from the menu to see everyone in your organisation.

The list shows each employee's:

| Column | Description |
| --- | --- |
| **Name** | The employee's name, shown with an avatar of their initial |
| **Employee code** | Their unique code |
| **Email** | Their work email |

At the top of the page you will find the main actions:

- **Refresh**: reloads the list to show the latest data.
- **Import**: adds many employees at once from a CSV file.
- **Add**: adds a single employee manually.
- **Filter** and **Export**: narrow down the list and download it.

---

## Add an Employee Manually

Use this when you are adding one or two people, such as a new hire.

1. On the **Employees** page, click **Add**.
2. Fill in the required fields (marked with a red asterisk):
   - **Full Legal Name**: the employee's name as it appears on their official documents.
   - **Employee code**: a unique code for the employee.
   - **Work Email**: the email address the employee will use for work.
3. Click **Save**.

The new employee appears in your list straight away.

:::tip
Only three details are needed to create an employee. You can complete the rest of their profile later.
:::

---

## Import Employees

Moving from another system or spreadsheet? Instead of adding people one by one, you can import all of them from a CSV file.

### Before you start

- The file must be in **CSV** format.
- The maximum file size is **25 MB**.
- Your file should use the same column headings as the Emphyra import template, shown below.

### Prepare your CSV file

Your file can include the following columns:

| Column | Notes |
| --- | --- |
| **Full Legal Name** | Required |
| **Email** | Required (work email) |
| **Employee Code** | Required, must be unique |
| Preferred Name | Optional |
| Gender | Optional |
| Date of Birth | Optional |
| Marital Status | Optional |
| Nationality | Optional |
| ID Type | Optional |
| ID Number | Optional |
| Race | Optional |
| Date Joined | Optional |
| Probation Period | Optional |
| Probation Period Unit | Optional |
| Probation End Date | Optional |
| Work Position | Optional |


### How to import

1. On the **Employees** page, click **Import**.
2. Click **Choose File** and select your CSV file.
3. Wait for the import to finish. Then a summary will be provided at the bottom of the window.
4. Close the window and click **Refresh** to see your new employees in the list.

:::tip
If some rows fail to import, you will have the option to view the failed rows along with the corresponding error messages explaining why the import failed.
:::

---

## Export the Employee List

Need a copy of your employee data for reporting or backup?

1. On the **Employees** page, apply a **filter** if you only want specific employees (optional).
2. Click **Export**.
3. Your employee list is downloaded as a file to your computer.

---

## What's Next?

