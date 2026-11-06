---
title: "User roles"
layout: default
nav_order: 4
parent: Guide
permalink: /user-roles/
---

# User roles

The Dataverse software underlying the FAIRvault, manages permissions to different parts of the repository through "roles."

Depending on your own role in relations to a Dataverse collection or dataset in the repository, you may be able to assign roles to other users. The table below describes the roles available in the repository and the permissions assigned to each.

<table class="metadata-table">
  <thead>
    <tr>
      <title>User roles</title>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>User role in FAIRvault</th>
      <th>To whom this may apply</th>
      <th>Permissions</th>
    </tr>
    <tr>
      <td>Root Administrator</td>
      <td>Technical admin for FAIRvault</td>
      <td>A person who manages the FAIRvault application and configuration, including assigning permissions to the Dataverse collections. Can also add Dataverse sub-collections and datasets and edit/publish/deaccession datasets submitted to the Dataverse collections.</td>
    </tr>
    <tr>
      <td>Organisational Administrator</td>
      <td>Admin for a collection within FAIRvault</td>
      <td>A person who manages configuration of a Dataverse collection, including assigning permissions to this Dataverse collection. Can add/edit/publish/deaccession datasets submitted to this Dataverse collection as well as manage access to the datasets in this collection.</td>
    </tr>
    <tr>
      <td>Organisational curator</td>
      <td>Curator for a collection within FAIRvault</td>
      <td>A person who can add/edit/publish/deaccession datasets submitted to this Dataverse collection as well as manage access to the datasets in this collection. In practice this will often be the same person as the Organisational administrator</td>
    </tr>
    <tr>
      <td>Contributor</td>
      <td>Member of a participating institute</td>
      <td>A person who can add datasets within a Dataverse collection. Datasets submitted to the Dataverse collection are "submitted for review." An Administrator or Curator for the Dataverse collection must approve and publish (or return to the contributor). r</td>
    </tr>
  </tbody>
</table>

Users logging in through their institutional authentication systems are assigned to an institutional group in the FAIRvault with permissions specific to the collection of that institution. If you have questions about your permissions level, please contact your support staff [add link].

File level permissions are binary. You simply grant (or restrict) access to published files.

Creation of Dataverse sub-collections is at the discretion of the administrators of the participating institutes.