---
title: Workato connectors - Wrike create timelog action
date: 2019-06-14 18:00:00 Z
search:
    keywords: ['wrike', 'timelog', 'create']
---

# Wrike - Create timelog action

This action creates a timelog record for a specified task in Wrike.

![Create timelog action](/assets/images/connectors/Wrike/create-timelog-action.png)
*Create timelog action*

### Input fields

<table class="unchanged rich-diff-level-one">
  <thead>
    <tr>
      <th width='25%'>Input field</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ID of task to add new timelog record</td>
      <td>
        The ID of the task to add new timelog record.
      </td>
    </tr>
    <tr>
      <td>Timelog comment</td>
      <td>
        The comment of this timelog record
      </td>
    </tr>
    <tr>
      <td>Timelog tracked hours</td>
      <td>
        The tracked hours in the timelog record.
      </td>    
    </tr>
    <tr>
      <td>Tracked date</td>
      <td>
        The date of the new timelog record
      </td>    
    </tr>
    <tr>
      <td>Timelog category</td>
      <td>
        Select the category for your timelog.
      </td>
    </tr>
  </tbody>
</table>

### Output fields

<table class="unchanged rich-diff-level-one">
  <thead>
    <tr>
        <th width='25%'>Output field</th>
        <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Timelog ID</td>
      <td>
        The ID of the timelog record.
      </td>
    </tr><tr>
      <td>Task ID</td>
      <td>
        The ID of the task that this timelog record tracks.
      </td>
    </tr>  
    <tr>
      <td>User ID</td>
      <td>
        The ID of the user who tracked the timelog record.
      </td>
    </tr>
    <tr>
      <td>Category ID</td>
      <td>
        The ID of the category of this timelog record.
      </td>
    </tr>
    <tr>
      <td>Hours</td>
      <td>
        The hours tracked in the timelog record.
      </td>
    </tr>
    <tr>
      <td>Created date</td>
      <td>
        The date this timelog record was created.
      </td>
    </tr>
    <tr>
      <td>Updated date</td>
      <td>
        The date this timelog record was updated.
      </td>
    </tr>
    <tr>
      <td>Completed date</td>
      <td>
       The date this timelog record was completed.
     </td>
    </tr>
    <tr>
      <td>Comment</td>
      <td>
        The comment to this timelog record.
      </td>
    </tr>
  </tbody>
</table>
