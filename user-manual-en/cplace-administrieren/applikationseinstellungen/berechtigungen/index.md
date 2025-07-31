::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Application
Settings](/user-manual-en/cplace-administrieren/applikationseinstellungen/){.docs-subsubtopic-page}
/ [Permissions]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/applikationseinstellungen/berechtigungen.md){.edit-btn
.float-end}
:::

# Permissions

You can control the global permissions in the **Permissions** tab in the
application settings. The following permissions/roles exist:

  -----------------------------------------------------------------------------------------------------
  Permission                          Description
  ----------------------------------- -----------------------------------------------------------------
  **Create Groups**                   The users/groups selected here can create new groups.\
                                      *Default value: Default group "Administrators"*

  **User Administrators**             The users/groups selected here can create, edit, deactivate, and
                                      delete users.\
                                      *Default value: Default group "Administrators "*

  **Group Administrators are allowed  If activated, group administrators can invite new users.\
  to invite new users**               *Default value: Deactivated*

  **Non-administrator users are       If activated, users who have not been selected under **User
  allowed to delete their own         administrators** can also delete their own accounts.\
  accounts**                          *Default value: Deactivated*

  **Users are allowed to send emails  If activated, users who have not been selected under **User
  to group administrators**           administrators** can also send emails to any group
                                      administrators.\
                                      *Default value: Deactivated*

  **Create Workspaces**               The users/groups selected here can create new workspaces.\
                                      *Default value: Default group "Administrators"*

  **Editing Types "User" and          The users/groups selected here can edit the "User" and "Group"
  "Group"**                           types (add more attributes to the type, for example).\
                                      *Default value: Default group "Administrators"*

  **Export direct Group Memberships** The users/groups selected here can export group memberships to
                                      Excel®.\
                                      *Default value: Default group "Administrators"*

  **Import direct Group Memberships** The users/groups selected here can import group memberships from
                                      Excel®.\
                                      *Default value: Default group "Administrators"*

  **Adaptability of a user's          Determines whether users are authorized to configure their own
  dashboard**                         dashboards or choose one from predefined layouts.\
                                      *Default: Freely customizable*

  **Access to all system              The users/groups selected here can execute all available actions
  information**                       on the "System information" page.\
                                      *Default: Standard group "Administrators"*

  **Configure Data Exchange**         The users/groups selected here can set up and adjust the data
                                      exchange. Effectively only valid if data exchange has been
                                      activated in the general application settings.\
                                      *Default: Standard group "Administrators"*

  **Permission to edit cplaceJS       The users/groups selected here can edit cplaceJS scripts and add
  scripts, which can call actions**   them to types. Further information can be found in the [Low-Code
                                      documentation](https://docs.cplace.io/lowcode/){target="_blank"
                                      rel="noopener"}\
                                      **Note that this permission can only be added via the server-side
                                      execution of the script
                                      "AddRemoveCplaceJJSEditPermissionsAction.java".**
  -----------------------------------------------------------------------------------------------------

## Editing global permissions

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be a member of the default "Administrators" group.
:::

To edit the global permissions, proceed as follows:

1.  Open the "User Menu".

2.  Open the "Application settings" menu option.

3.  Open the "Permissions" tab.

4.  Make the required changes.
:::::
