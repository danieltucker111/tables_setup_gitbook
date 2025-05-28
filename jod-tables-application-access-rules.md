---
description: RBAC, System, and Feature-Based
---

# JOD Tables Application Access Rules

## Top Level Navigation

<details>

<summary>Application’s Left Nav Bar Element is Visible</summary>

|                      | Super Admin | Org Admin | Designer | User |
| -------------------- | :---------: | :-------: | :------: | :--: |
| Design               |      ✅      |     ✅     |     ✅    |   ✅  |
| My Dashboard         |      ✅      |     ✅     |     ✅    |   ✅  |
| Meetings             |      ✅      |     ✅     |     ✅    |   ✅  |
| Reports              |      ✅      |     ✅     |     ✅    |   ✅  |
| Decisions🔒          |      ✅      |     ✅     |     ✅    |   ❌  |
| Structure🔒          |      ✅      |     ✅     |     ✅    |   ❌  |
| Strategic Priorities |      ✅      |     ✅     |     ✅    |   ✅  |
| Org Strategies       |      ✅      |     ✅     |     ✅    |   ✅  |
| Values               |      ✅      |     ✅     |     ✅    |   ✅  |
| Org Members🔒        |      ✅      |     ✅     |     ❌    |   ❌  |
| Community Mbrs🔒     |      ✅      |     ✅     |     ❌    |   ❌  |

</details>

## Dashboards

<details>

<summary>Design Dashboard</summary>

|                              | Super Admin | Org Admin | Designer |  User  |
| ---------------------------- | :---------: | :-------: | :------: | :----: |
| Can View                     |      ✅      |     ✅     |     ✅    |    ✅   |
| Can Click to Detail          |      ✅      |     ✅     |     ✅    | ❌ (??) |
| Can Filter                   |      ✅      |     ✅     |    ☑️    |   ☑️   |
| Can Sort                     |      ✅      |     ✅     |     ❌    |    ❌   |
| Create Record from Dashboard |      ◻️     |     ◻️    |    ◻️    |   ◻️   |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |   ◻️   |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ = partial capacity. Can show/hide Table Participants or Represented Groups
3. Sort = Tables and Teams only
4. ?? = Why Not
{% endhint %}

</details>

<details>

<summary>My Dashboard</summary>

|                              |     Super Admin     |      Org Admin      |       Designer      |         User        |
| ---------------------------- | :-----------------: | :-----------------: | :-----------------: | :-----------------: |
| Can View                     | <p>☑️</p><p>(p)</p> | <p>☑️</p><p>(p)</p> | <p>☑️</p><p>(p)</p> | <p>☑️</p><p>(p)</p> |
| Can Click to Detail          | <p>☑️</p><p>(p)</p> | <p>☑️</p><p>(p)</p> | <p>☑️</p><p>(p)</p> | <p>☑️</p><p>(p)</p> |
| Can Filter                   |          ✅          |          ✅          |          ✅          |          ✅          |
| Can Sort                     |          ◻️         |          ◻️         |          ◻️         |          ◻️         |
| Create Record from Dashboard |          ◻️         |          ◻️         |          ◻️         |          ◻️         |
| Delete from Dashboard        |          ◻️         |          ◻️         |          ◻️         |          ◻️         |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ = partial capacity: only for Teams/Table where the user is a participant
3. Filter = active vs inactive
4. All users can mark their Commitments as “Ready”
{% endhint %}

</details>

<details>

<summary>Meetings Dashboard</summary>

|                              |       Super Admin      |        Org Admin       |        Designer        |          User          |
| ---------------------------- | :--------------------: | :--------------------: | :--------------------: | :--------------------: |
| Can View                     |            ✅           |            ✅           |            ✅           |   <p>☑️</p><p>(p)</p>  |
| Can Click to Detail          |   <p>☑️</p><p>(p)</p>  |   <p>☑️</p><p>(p)</p>  |   <p>☑️</p><p>(p)</p>  |   <p>☑️</p><p>(p)</p>  |
| Can Filter                   |            ✅           |            ✅           |            ✅           |   <p>☑️</p><p>(p)</p>  |
| Can Sort                     |           ◻️           |           ◻️           |           ◻️           |           ◻️           |
| Create Record from Dashboard | <p>☑️</p><p>(p+gl)</p> | <p>☑️</p><p>(p+gl)</p> | <p>☑️</p><p>(p+gl)</p> | <p>☑️</p><p>(p+gl)</p> |
| Delete from Dashboard        |           ◻️           |           ◻️           |           ◻️           |           ◻️           |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ = partial capacity for view, filter, and click to: only for Groups where they are a participant
3. ☑️ = partial capacity for create from dashboard: only where User is GL for Groups where they are a participant
4. Filter = active vs inactive, user tables/teams, and meeting start time
{% endhint %}

</details>

<details>

<summary>Reports Dashboard</summary>

|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ✅    |  ☑️  |
| Can Click to Detail          |      ✅      |     ✅     |     ✅    |  ☑️  |
| Can Filter                   |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Can Sort                     |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Create Record from Dashboard |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ = partial capacity: Only Unlocked Reports (reports without 🔒 icon)
{% endhint %}

</details>

<details>

<summary>Decisions Dashboard</summary>

|                              |                Super Admin                |                 Org Admin                 |                  Designer                 | User |
| ---------------------------- | :---------------------------------------: | :---------------------------------------: | :---------------------------------------: | :--: |
| Can View                     |                     ✅                     |                     ✅                     |                     ✅                     |   ❌  |
| Update Record from Dashboard | <p>☑️</p><p>(p+gl)</p><p>(See note 3)</p> | <p>☑️</p><p>(p+gl)</p><p>(See note 3)</p> | <p>☑️</p><p>(p+gl)</p><p>(See note 3)</p> |   ❌  |
| Can Click to Detail          |           <p>☑️</p><p>(p+gl)</p>          |           <p>☑️</p><p>(p+gl)</p>          |           <p>☑️</p><p>(p+gl)</p>          |   ❌  |
| Can Filter                   |                     ✅                     |                     ✅                     |                     ✅                     |   ❌  |
| Can Sort                     |                     ◻️                    |                     ◻️                    |                     ◻️                    |  ◻️  |
| Create Record from Dashboard |                     ◻️                    |                     ◻️                    |                     ◻️                    |  ◻️  |
| Delete from Dashboard        |           <p>☑️</p><p>(p+gl)</p>          |           <p>☑️</p><p>(p+gl)</p>          |           <p>☑️</p><p>(p+gl)</p>          |   ❌  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. ☑️ = partial capacity:  only where User is GL for Groups where they are a participant (record deletion occurs via popup of decision record on page.
3. Also note that these users can update such records as well via a popup on the dashboard screen.
{% endhint %}

</details>

<details>

<summary>Structure Dashboard</summary>

|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ✅    |   ❌  |
| Can Click to Detail          |      ✅      |     ✅     |     ✅    |   ❌  |
| Can Filter                   |      ✅      |     ✅     |     ✅    |   ❌  |
| Can Sort                     |      ✅      |     ✅     |     ✅    |   ❌  |
| Create Record from Dashboard |      ✅      |     ✅     |     ✅    |   ❌  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
{% endhint %}

</details>

<details>

<summary>Strategic Priorities Dashboard</summary>

|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ✅    |   ❌  |
| Can Click to Detail          |      ✅      |     ✅     |     ✅    |   ❌  |
| Can Filter                   |      ✅      |     ✅     |     ✅    |   ❌  |
| Can Sort                     |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Create Record from Dashboard |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
{% endhint %}

</details>

<details>

<summary>Org Strategies Dashboard</summary>

|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ✅    |   ✅  |
| Can Click to Detail          |      ✅      |     ✅     |     ✅    |   ✅  |
| Can Filter                   |      ✅      |     ✅     |     ✅    |   ✅  |
| Can Sort                     |      ✅      |     ✅     |     ❌    |   ❌  |
| Create Record from Dashboard |      ✅      |     ✅     |     ❌    |   ❌  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = active vs inactive
{% endhint %}

</details>

<details>

<summary>Values Dashboard</summary>

|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ✅    |   ✅  |
| Can Click to Detail          |      ✅      |     ✅     |     ✅    |   ✅  |
| Can Filter                   |      ✅      |     ✅     |     ✅    |   ✅  |
| Can Sort                     |      ✅      |     ✅     |     ❌    |   ❌  |
| Create Record from Dashboard |      ✅      |     ✅     |     ❌    |   ❌  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = active vs inactive
{% endhint %}

</details>

<details>

<summary>Purpose Dashboard</summary>

|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ✅    |   ✅  |
| Can Click to Detail          |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Can Filter                   |      ✅      |     ✅     |     ❌    |   ❌  |
| Can Sort                     |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Create Record from Dashboard |      ✅      |     ✅     |     ❌    |   ❌  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = view previous versions
3. Records can be updated by the same groups that can create them from this dashboard (via a popup screen)
{% endhint %}

</details>

<details>

<summary>Org Member Dashboard</summary>

|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ❌    |   ❌  |
| Can Click to Detail          |      ✅      |     ✅     |     ❌    |   ❌  |
| Can Filter                   |      ✅      |     ✅     |     ❌    |   ❌  |
| Can Sort                     |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Create Record from Dashboard |      ✅      |     ✅     |     ❌    |   ❌  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

{% hint style="info" %}
Notes:

1. ◻️ = N/A
2. Filter = active vs inactive, and search
{% endhint %}

</details>

<details>

<summary>Community Member Dashboard</summary>



|                              | Super Admin | Org Admin | Designer | User |
| ---------------------------- | :---------: | :-------: | :------: | :--: |
| Can View                     |      ✅      |     ✅     |     ❌    |   ❌  |
| Can Click to Detail          |      ✅      |     ✅     |     ❌    |   ❌  |
| Can Filter                   |      ✅      |     ✅     |     ❌    |   ❌  |
| Can Sort                     |      ◻️     |     ◻️    |    ◻️    |  ◻️  |
| Create Record from Dashboard |      ✅      |     ✅     |     ❌    |   ❌  |
| Delete from Dashboard        |      ◻️     |     ◻️    |    ◻️    |  ◻️  |

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

<table><thead><tr><th></th><th width="181.65234375" align="center">Super Admin</th><th align="center">Org Admin</th><th align="center">Designer</th><th align="center">User</th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark></td><td align="center"><mark style="color:blue;"><strong>Meetings</strong></mark>                               </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Actions</strong></mark>                                                                 </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Open Commitments</strong></mark>   </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>UPDATE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Decisions</strong></mark>                                 </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Linked Documents</strong></mark>             </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>READ Detail</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>Filter List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td></tr><tr><td>Sort List</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td><td align="center">☑️<br>(p)</td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td><td align="center"><p>☑️<br>(p)??</p><p>(See note:2)</p></td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. Meeting Name only
2. Should be gl only
{% endhint %}

</details>

<details>

<summary>Meeting Space</summary>

{% hint style="info" %}
&#x20;<mark style="color:blue;">**GLOBAL RULE FOR MEETINGS**</mark>

<mark style="color:blue;">Users must be on a given Team/Table in order to access its meeting details page. The following grid identifies what the different roles can access on the Meeting Space page once there.</mark>&#x20;
{% endhint %}

<table><thead><tr><th></th><th width="166.93359375" align="center">Super Admin</th><th align="center">Org Admin</th><th align="center">Designer</th><th align="center">User</th></tr></thead><tbody><tr><td><mark style="color:blue;"><strong>AREA:</strong></mark></td><td align="center"><mark style="color:blue;"><strong>Entire Meeting</strong></mark>                       </td><td align="center"><mark style="color:blue;"><strong>Record</strong></mark></td><td align="center"></td><td align="center"></td></tr><tr><td>CREATE Meeting</td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td><td align="center"><p>☑️</p><p>(gl)</p><p>(See note:1)</p></td></tr><tr><td>DELETE Meeting</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Left Pane</strong></mark>                     </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Logistics</strong></mark>       </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Purpose</strong></mark>         </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Agenda Topics</strong></mark>           </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Linked Documents</strong></mark>      </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Sort List</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>DELETE Record (from page)</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Link / Unlink Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Decision Making</strong></mark>            </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Commitments</strong></mark>               </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Summary</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>READ Detail</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Filter List</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td><td align="center">◻️</td></tr><tr><td>CREATE Record</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>UPDATE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Sort List</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>DELETE Record (from page)</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td><mark style="color:blue;"><strong>SECTION:</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Notes</strong></mark>              </td><td align="center"></td><td align="center"></td><td align="center"></td></tr><tr><td>READ Notes</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>UPDATE Notes (from page)</td><td align="center"><p>☑️</p><p>(See note:2)</p></td><td align="center"><p>☑️</p><p>(See note:2)</p></td><td align="center"><p>☑️</p><p>(See note:2)</p></td><td align="center"><p>☑️</p><p>(See note:2)</p></td></tr><tr><td><mark style="color:blue;"><strong>OTHER</strong></mark> </td><td align="center"><mark style="color:blue;"><strong>Meeting Space</strong></mark>            </td><td align="center"><mark style="color:blue;"><strong>Functionality</strong></mark></td><td align="center"></td><td align="center"></td></tr><tr><td>Email Meeting Agenda</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Email Meeting Results</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Create Capture Board</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Access Capture Board</td><td align="center"><p>☑️</p><p>(See note:3)</p></td><td align="center"><p>☑️</p><p>(See note:3)</p></td><td align="center"><p>☑️</p><p>(See note:3)</p></td><td align="center"><p>☑️</p><p>(See note:3)</p></td></tr><tr><td>Access Voting Room</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Access Planner</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr><tr><td>Pull Users to Meeting Space</td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td><td align="center"><p>☑️</p><p>(gl)</p></td></tr><tr><td>Download Meeting Space info</td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td><td align="center"><p>☑️</p><p>(p)</p></td></tr></tbody></table>

{% hint style="info" %}
Notes:

1. Meetings can only be created via the Meeting Dashboard or the Team/Table Planner
2. With Note Taker Permission
3. Once a GL has created an initial Capture Board
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

|                    |      Super Admin     |       Org Admin      |       Designer       |         User         |
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

|            |      Super Admin     |       Org Admin      |       Designer       |         User         |
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

|                        |          Super Admin         |           Org Admin          |           Designer           | User |
| ---------------------- | :--------------------------: | :--------------------------: | :--------------------------: | :--: |
| Can View Page & Detail |               ✅              |               ✅              |               ✅              |   ❌  |
| Can Create Record      | <p>☑️</p><p>(See Note 1)</p> | <p>☑️</p><p>(See Note 1)</p> | <p>☑️</p><p>(See Note 1)</p> |   ❌  |
| Can Update Records     |               ✅              |               ✅              |               ✅              |   ❌  |
| Can Delete Records     |               ✅              |               ✅              |               ❌              |   ❌  |
| Can Close a Team/Table |               ✅              |               ✅              |               ❌              |   ❌  |

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

<table><thead><tr><th width="159.5859375"></th><th align="center">Super Admin</th><th align="center">Org Admin</th><th align="center">Designer</th><th align="center">User</th></tr></thead><tbody><tr><td>Can View Page &#x26; Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>Can Create Record</td><td align="center"><p>☑️</p><p>(See Note 1)</p></td><td align="center"><p>☑️</p><p>(See Note 1)</p></td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Update Records</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Can Delete Records</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>View Strategy Strength Review Indicator Summary Tool</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td><td align="center">✅</td></tr><tr><td>View Strategy Strength Review Detail</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr><tr><td>Update Strategy Strength Review Indicator Record</td><td align="center">✅</td><td align="center">✅</td><td align="center">❌</td><td align="center">❌</td></tr></tbody></table>

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

|                        |          Super Admin         |           Org Admin          | Designer | User |
| ---------------------- | :--------------------------: | :--------------------------: | :------: | :--: |
| Can View Record Detail |               ✅              |               ✅              |     ✅    |   ✅  |
| Can Create Record      | <p>☑️</p><p>(See Note 1)</p> | <p>☑️</p><p>(See Note 1)</p> |     ❌    |   ❌  |
| Can Update Records     |               ✅              |               ✅              |    ✅??   |  ✅?? |
| Can Delete Records     |               ✅              |               ✅              |    ✅??   |  ✅?? |

{% hint style="info" %}
Notes:

1. ☑️ = These Users can create Org Strategies, but such creation must occur outside of the detail page. See Global Rules above.
2. ?? = Issue (needs to be fixed)
{% endhint %}

</details>

## Reporting

<details>

<summary>All Reports</summary>

All Reports <mark style="color:red;">**WITHOUT**</mark> The 🔒 Emoji Next To The Report Name

|          | Super Admin | Org Admin | Designer |         User        |
| -------- | :---------: | :-------: | :------: | :-----------------: |
| Can View |      ✅      |     ✅     |     ✅    | <p>☑️</p><p>(p)</p> |

***

All Reports <mark style="color:green;">**WITH**</mark> The 🔒 Emoji Next To The Report Name

|          | Super Admin | Org Admin | Designer | User |
| -------- | :---------: | :-------: | :------: | :--: |
| Can View |      ✅      |     ✅     |     ✅    |   ❌  |

{% hint style="info" %}
Notes:

1. ☑️  For Table/Team based reports Users can only view reports for Teams/Tables for which they are a participant.&#x20;
{% endhint %}

</details>
