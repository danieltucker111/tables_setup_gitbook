---
description: RBAC, System, and Feature-Based
---

# JOD Tables Application Access Rules

## Roles and Access

#### User

This is the standard role for most people using JustOrg Design. As a User, you can fully participate in the teams and groups you belong to. You'll see everything you need for your own work, but you won't see the detailed activities of other groups. This role also applies to people who lead groups (Group Conveners).

#### Insight

This role works just like the User role, with one addition: you can see all reports in the system. Organizations typically give this role to board members or senior leaders who need a broader view of what's happening (see Reporting below).

#### Org View

This role is for leaders who need to see the big picture across the entire organization. You can view reports and dashboards for all groups, which helps with strategic planning and alignment. However, you can only actively work in groups where you're an actual member. This role is usually reserved for executive leaders and Group Sponsors (see Dashboards and Reporting below).&#x20;

#### Org Admin

This is your organization's power user role. Org Admins set up and manage the core structure of your JustOrg Design system—things like your organization's strategies, priorities, and structures. They also manage who has access to the system. Like Org View, this role can only actively work in groups where they're a member. Because this role can make major changes to your organization's setup, we recommend limiting it to just a few trusted people.

#### Super Admin

This role is reserved for JustOrg Design staff only. It allows our team to configure and maintain the platform for all customers. Like Org View and Org Admin, this role can only actively work in groups where they're a member.&#x20;



## Top Level Navigation

<details>

<summary>Application’s Left Nav Bar Element is Visible</summary>

<table><thead><tr><th width="190.8203125"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th width="119.21484375" align="center">Org View</th><th width="109.87890625" align="center">User</th></tr></thead><tbody><tr><td>Design</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>My Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Meetings</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Reports</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Decisions🔒</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Structure🔒</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Strategic Priorities</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Org Strategies</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Values</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Org Members🔒</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Community Mbrs🔒</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr></tbody></table>

</details>

## Dashboards

<details>

<summary>Design Dashboard</summary>

<table><thead><tr><th width="202.0390625"></th><th align="center">Super Admin</th><th width="115.85546875" align="center">Org Admin</th><th width="113.625" align="center">Org View</th><th width="107.58984375" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Click to Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center"><p>☑️</p><p>(2)</p></td></tr><tr><td>Can Modify View</td><td align="center">✅</td><td align="center">✅</td><td align="center"><p>☑️</p><p>(3)</p></td><td align="center"><p>☑️</p><p>(3)</p></td></tr><tr><td>Can Sort</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Create Record from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ = can access Purpose, Strategies, and Priorities&#x20;
3. ☑️ = partial capacity. Can show/hide Table Participants or Represented Groups
4. Sort = Tables and Teams only
{% endhint %}

</details>

<details>

<summary>My Dashboard</summary>

<table><thead><tr><th width="251.234375"></th><th width="121.26171875" align="center">Super Admin</th><th width="128.6328125" align="center">Org Admin</th><th width="112.84765625" align="center">Org View</th><th width="92.125" align="center">User</th></tr></thead><tbody><tr><td>Can View Page</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can View Team/Table Card</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Can Click to Team/Table Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Can View My Open Commitments</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Can View My Open Group Lead Tasks</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Sort</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Create Record from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️(p) = only for Teams/Table where the user is a participant
3. ☑️(gl) = only for Teams/Table where the user is a Group Lead
4. Filter = active vs inactive
5. All users can mark their Commitments as “Ready”
{% endhint %}

</details>

<details>

<summary>Meetings Dashboard</summary>

<table><thead><tr><th width="198.296875"></th><th align="center">Super Admin</th><th width="125.91796875" align="center">Org Admin</th><th width="118.3828125" align="center">Org View</th><th width="101.45703125" align="center">User</th></tr></thead><tbody><tr><td>Can View Summary Info</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Can Click to Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Can Sort</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Create Record from Dashboard</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ (p) = partial capacity for view, filter, and click to: only for Groups where they are a participant
3. ☑️(gl) = partial capacity for create from dashboard: only where User is a GL for the team/table
4. Filter = active vs inactive, user tables/teams, and meeting start time
{% endhint %}

</details>

<details>

<summary>Reports Dashboard</summary>

<table><thead><tr><th width="164.1875"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th align="center">Org View</th><th align="center">User</th></tr></thead><tbody><tr><td>Can View Page</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can View Report Summary Info</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">☑️</td></tr><tr><td>Can Click to Detailed Report</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">☑️</td></tr><tr><td>Can Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Can Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ = partial capacity: Only Unlocked Reports (reports <mark style="color:red;">WITHOUT</mark> the 🔒 icon)
{% endhint %}

</details>

<details>

<summary>Decisions Dashboard</summary>

<table><thead><tr><th width="189.44921875"></th><th width="127.3125" align="center">Super Admin</th><th align="center">Org Admin</th><th width="115.46484375" align="center">Org View</th><th width="112.96875" align="center">User</th></tr></thead><tbody><tr><td>Can View Page</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Update Record from Dashboard</td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note 3)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note 3)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note 3)</p></td><td align="center">❌</td></tr><tr><td>Can Click to Detail</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center">❌</td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Can Sort</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Create Record from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Delete from Dashboard</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center">❌</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️(gl) = partial capacity:  only where User is GL for the team/table who created the decision (record deletion occurs via popup of decision record on page).
3. These users can update decision records via a popup on the dashboard screen.
{% endhint %}

</details>

<details>

<summary>Structure Dashboard</summary>

<table><thead><tr><th width="199.80078125"></th><th align="center">Super Admin</th><th width="120.8203125" align="center">Org Admin</th><th width="107.30078125" align="center">Org View</th><th width="114.81640625" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Can Click to Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Can Sort</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td></tr><tr><td>Create Record from Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
{% endhint %}

</details>

<details>

<summary>Strategic Priorities Dashboard</summary>

<table><thead><tr><th width="196.734375"></th><th align="center">Super Admin</th><th width="110.69921875" align="center">Org Admin</th><th align="center">Org View</th><th width="101.94921875" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Click to Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center"><p>☑️</p><p>(2)</p></td></tr><tr><td>Can Sort</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Create Record from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Users can filter for Active or Completed strategic priority items ONLY
{% endhint %}

</details>

<details>

<summary>Org Strategies Dashboard</summary>

<table><thead><tr><th width="197.9296875"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th width="111.14453125" align="center">Org View</th><th width="110.94140625" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Click to Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Sort</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Create Record from Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = active vs inactive
{% endhint %}

</details>

<details>

<summary>Values Dashboard</summary>

<table><thead><tr><th width="200.46875"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th width="108.63671875" align="center">Org View</th><th width="110" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Click to Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Sort</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Create Record from Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = active vs inactive
{% endhint %}

</details>

<details>

<summary>Purpose Dashboard</summary>

<table><thead><tr><th width="209.60546875"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th width="107.08203125" align="center">Org View</th><th width="100.53125" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Access Previous Versions</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Update Record from Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Create Record from Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
{% endhint %}

</details>

<details>

<summary>Org Member Dashboard</summary>

<table><thead><tr><th width="208.84375"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th width="110.47265625" align="center">Org View</th><th width="103.87890625" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Click to Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Sort</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Create Record from Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = active vs inactive, and search
{% endhint %}

</details>

<details>

<summary>Community Member Dashboard</summary>



<table><thead><tr><th width="205.61328125"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th width="117.625" align="center">Org View</th><th width="94.7890625" align="center">User</th></tr></thead><tbody><tr><td>Can View</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Click to Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Filter</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Sort</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>Create Record from Dashboard</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Delete from Dashboard</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = active vs inactive, and search
{% endhint %}

</details>

## Key Feature

<details>

<summary>Table Planner</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR THE TEAM/TABLE PLANNER**</mark>

<mark style="color:blue;">Users must be on a given Team/Table in order to access its Planner details page. The following grid identifies what the different roles can access on the Team/Table Planner page once there.</mark>&#x20;
{% endhint %}

<table><thead><tr><th></th><th width="157.86328125" align="center">Super Admin</th><th width="120.87109375" align="center">Org Admin</th><th width="111.40625" align="center">Org View</th><th width="101.6875" align="center">User</th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark></td><td align="center"><mark style="color:blue;"><strong>Top Navigation</strong></mark>                               </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>Planner Tools Dropdown</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark></td><td align="center"><mark style="color:blue;"><strong>Meetings</strong></mark>                               </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Actions</strong></mark>                                                                 </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Open Commitments</strong></mark>   </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>UPDATE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Decisions</strong></mark>                                 </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Linked Documents</strong></mark>             </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. Meeting Name only
{% endhint %}

</details>

<details>

<summary>Meeting Space</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR MEETINGS**</mark>

<mark style="color:blue;">Users must be on a given Team/Table in order to access its meeting details page. The following grid identifies what the different roles can access on the Meeting Space page once there.</mark>&#x20;
{% endhint %}

<table><thead><tr><th width="161.3046875"></th><th width="166.93359375" align="center">Super Admin</th><th width="133.5546875" align="center">Org Admin</th><th width="111.6171875" align="center">Org View</th><th width="100.3359375" align="center">User</th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>AREA:</strong></mark></td><td align="center"><mark style="color:blue;"><strong>Entire Meeting</strong></mark>                       </td><td align="center"><mark style="color:blue;"><strong>Record</strong></mark></td><td align="center"></td><td align="center"></td></tr><tr><td>CREATE Meeting</td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td></tr><tr><td>DELETE Meeting</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Left Pane</strong></mark>                     </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Logistics</strong></mark>       </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Purpose</strong></mark>         </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Agenda Topics</strong></mark>           </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Linked Documents</strong></mark>      </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Sort List</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>DELETE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Link / Unlink Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Decision Making</strong></mark>            </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Commitments</strong></mark>               </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Notes</strong></mark>              </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Notes</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>UPDATE Notes (from page)</td><td align="center"><p>☑️</p><p>(See note:2)</p></td><td align="center"><p>☑️</p><p>(See note:2)</p></td><td align="center"><p>☑️</p><p>(See note:2)</p></td><td align="center"><p>☑️</p><p>(See note:2)</p></td></tr><tr><td><mark style="color:blue;"><strong>OTHER</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Space</strong></mark>            </td><td align="center"><mark style="color:blue;"><strong>Functionality</strong></mark></td><td align="center"></td><td align="center"></td></tr><tr><td>Email Meeting Agenda</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Email Meeting Results</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Create Capture Board</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Access Capture Board</td><td align="center"><p>☑️</p><p>(See note:3)</p></td><td align="center"><p>☑️</p><p>(See note:3)</p></td><td align="center"><p>☑️</p><p>(See note:3)</p></td><td align="center"><p>☑️</p><p>(See note:3)</p></td></tr><tr><td>Access Voting Room</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Access Planner</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Pull Users to Meeting Space</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Download Meeting Space info</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. Meetings can only be created via the Meeting Dashboard or the Team/Table Planner
2. With Note Taker Permission
3. Once a GL has created an initial Capture Board (CB) - and only when GL is sharing the CB
4. (gl): Group Lead
5. (p):  Group (Team/Table) Participant
{% endhint %}

</details>

<details>

<summary>Decisions (and Decisions Made)</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR DECISION MAKING**</mark>

<mark style="color:blue;">Decisions can only be made within a meeting:</mark>

1. <mark style="color:blue;">a realtime decision made in realtime during a meeting from within a MEETING SPACE</mark>
2. <mark style="color:blue;">a vote decision made from within the GROUP VOTING space</mark> &#x20;

<mark style="color:blue;">The grid below focus on permissions for both. For both the User must be a Group Lead for the team/table they wish to create, update, or delete a decision-made record.</mark>&#x20;
{% endhint %}

**Realtime Decision And Decision From Voting**

|                    |      Super Admin     |       Org Admin      |       Org View       |         User         |
| ------------------ | :------------------: | :------------------: | :------------------: | :------------------: |
| Can View Records   |           ✅          |           ✅          |           ✅          |          ☑️          |
| Can Create Record  | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> |
| Can Update Records | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> |
| Can Delete Records | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> |

{% hint style="info" %}
Notes:

1. ☑️ = Requires user to be a participant of the table they wish to view decision-made records for.&#x20;
{% endhint %}

</details>

<details>

<summary>Group Voting  (Decision Proposals)</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR GROUP VOTING**</mark>

<mark style="color:blue;">A proposal to be voted on must be initiated by a Group Lead for a given Team/Table.  Once initiated, a Vote Administrator can be assigned by a GL to administer the vote for a given proposal. However, the Vote Administrator can be ANY User within the organization (they DO NOT have to be a Team/Table participant or a GL). The Team/Table GL is the only one who can make changes to the Vote Administrator.</mark>&#x20;
{% endhint %}

|            |      Super Admin     |       Org Admin      |       Org View       |         User         |
| ---------- | :------------------: | :------------------: | :------------------: | :------------------: |
| Can View   |          ☑️          |          ☑️          |          ☑️          |          ☑️          |
| Can Create | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> |
| Can Update | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> |
| Can Delete | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> | <p>☑️</p><p>(gl)</p> |
| Can Vote   |          ☑️          |          ☑️          |          ☑️          |          ☑️          |

{% hint style="info" %}
Notes:

1. ☑️ = Requires user to be a participant of the proposal Team/Table&#x20;
{% endhint %}

</details>

<details>

<summary>Structures (Teams/Tables Detail Page)</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR STRUCTURES**</mark>

1. <mark style="color:blue;">Structure can only be created from the Organizational Structure summary page or from the initial JOD Onboarder screen.</mark>&#x20;
2. <mark style="color:blue;">Structure information can only be changed from the Team/Table details page or from the initial JOD Onboarder screen.</mark> &#x20;
{% endhint %}

|                        |          Super Admin         |           Org Admin          | Org View | User |
| ---------------------- | :--------------------------: | :--------------------------: | :------: | :--: |
| Can View Page & Detail |               ✅              |               ✅              |     ✅    |   ❌  |
| Can Create Record      | <p>☑️</p><p>(See Note 1)</p> | <p>☑️</p><p>(See Note 1)</p> |     ❌    |   ❌  |
| Can Update Records     |               ✅              |               ✅              |     ❌    |   ❌  |
| Can Delete Records     |               ✅              |               ✅              |     ❌    |   ❌  |
| Can Close a Team/Table |               ✅              |               ✅              |     ❌    |   ❌  |

{% hint style="info" %}
Notes:

1. ☑️ = These Users can create Teams/Tables, but such creation must occur outside of the detail page. See Global Rules above.
{% endhint %}

</details>

<details>

<summary>Strategies and Priorities  (Org Strategy Detail Page)</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR ORG STRATEGIES**</mark>

1. <mark style="color:blue;">Strategies can only be created from the Org Strategy summary page or from the initial JOD Onboarder screen.</mark>&#x20;
2. <mark style="color:blue;">Strategy information can only be changed from the Org Strategy details page or from the initial JOD Onboarder screen.</mark> &#x20;
3. <mark style="color:blue;">These rules also apply to Strategic Priorities which are part of an Org Strategy.</mark>
{% endhint %}

<table><thead><tr><th width="159.5859375"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th align="center">Org View</th><th align="center">User</th></tr></thead><tbody><tr><td>Can View Page &#x26; Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can View Previous Versions</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Create Record</td><td align="center"><p>☑️</p><p>(See Note 1)</p></td><td align="center"><p>☑️</p><p>(See Note 1)</p></td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Update Records</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Delete Records</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>View Strategy Strength Review Indicator Summary Tool</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>View Strategy Strength Review Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Update Strategy Strength Review Indicator Record</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. ☑️ = These Users can create Org Strategies, but such creation must occur outside of the detail page. See Global Rules above.
{% endhint %}

</details>

<details>

<summary>Values  (Values Detail)</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR VALUES**</mark>

1. <mark style="color:blue;">Values can only be created from the Values summary page.</mark>&#x20;
2. <mark style="color:blue;">Values information can only be changed from the Values detail popup.</mark> &#x20;
{% endhint %}

|                        |          Super Admin         |           Org Admin          | Org View | User |
| ---------------------- | :--------------------------: | :--------------------------: | :------: | :--: |
| Can View Record Detail |               ✅              |               ✅              |     ✅    |   ✅  |
| Can Create Record      | <p>☑️</p><p>(See Note 1)</p> | <p>☑️</p><p>(See Note 1)</p> |     ❌    |   ❌  |
| Can Update Records     |               ✅              |               ✅              |     ❌    |   ❌  |
| Can Delete Records     |               ✅              |               ✅              |     ❌    |   ❌  |

{% hint style="info" %}
Notes:

1. ☑️ = These Users can create Values, but such creation must occur outside of the detail page. See Global Rules above.
{% endhint %}

</details>

## Reporting

<details>

<summary>All Reports</summary>

All Reports <mark style="color:red;">**WITHOUT**</mark> The 🔒 Emoji Next To The Report Name

|          | Super Admin | Org Admin | <p>Org View <br>&#x26; Insights</p> |         User        |
| -------- | :---------: | :-------: | :---------------------------------: | :-----------------: |
| Can View |      ✅      |     ✅     |                  ✅                  | <p>☑️</p><p>(p)</p> |



***

All Reports <mark style="color:green;">**WITH**</mark> The 🔒 Emoji Next To The Report Name

|          | Super Admin | Org Admin | <p>Org View <br>&#x26; Insights</p> | User |
| -------- | :---------: | :-------: | :---------------------------------: | :--: |
| Can View |      ✅      |     ✅     |                  ✅                  |   ❌  |

{% hint style="info" %}
Notes:

1. ☑️  For Table/Team based reports Users can only view reports for Teams/Tables for which they are a participant.&#x20;
{% endhint %}

</details>
