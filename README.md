# Customer Setup Guide

<details>

<summary>Set Up Backend Database</summary>

Set Up Backend Database \<JoD Operations Team>

1. Create customer record in database table "customers"
   1. Organization Is Active = Yes (select)
   2. Customer Name
   3. Customer Logo
   4. Slug
2. Create initial Org Member(s) in the org\_members table
   1. Organization\_ID
   2. Active = "Yes" (string)
   3. Staff Full Name
      1. Staff First Name
      2. Staff Last Name
   4. Member is JoD User = No (select) [_\[note\]_](#user-content-fn-1)[^1]__
   5. Work Email (ensure consistency with User record)
   6. Position = OPTIONAL
   7. Position Level = OPTIONAL

_Note: No need to create JoD User(s) via the database - instead they will be created via the Admin interface - see next step._&#x20;

</details>

<details>

<summary>Create Initial JoD Users</summary>

Create Initial JoD Users via the Tables' Admin \<JoD Admin>

Using the super admin's add user tool...&#x20;

![](<.gitbook/assets/Screenshot 2023-01-29 at 4.50.46 PM.png>)

1. Select the desired organization from Organization Name
2. A set of all available Org Members (those that are not already JoD Users) are already populated in the Org Member Full Name field
3. First Name and Last Name fields will auto populate, but may be changed.&#x20;
4. Email should also auto populate (if available in the member's record). This field may be changed.&#x20;

_Note: All fields are required. The Create User button will change to a JoD-purple color when the record is ready to be submitted._&#x20;

**IMPORTANT NOTE:**&#x20;

If users are having issues with setting up their account:&#x20;

* Have them check their spam folders for the JoD email
  * If possible, inform recipients in advance that emails may go to their spam folder -- they should check there if they do not see it in their inbox. &#x20;
* Also confirm that emails have been sent to the correct (expected) address

</details>

<details>

<summary>Create Initial Elements</summary>

Create Initial Elements via the Tables’ GUI \<Org Admin>

1. Add Org Members (Org Admin)
2. Convert Org Members to JoD Users and Invite them to the Tables Application (via email request to JustOrg Design ONLY)
3. Create initial
   1. Values (optional)&#x20;
   2. Strategies&#x20;
   3. Table(s) – The Org Admin must create the first Table. The Org Admin has the option to set permissions to one or more Tables that will allow such tables to create Tables.

_Note: Only JoD Users can log into the Tables Application and be Sponsors or Conveners_

</details>

[^1]: S_etting this field to Yes would prevent the user from showing up in the Create New User dropdown._&#x20;
