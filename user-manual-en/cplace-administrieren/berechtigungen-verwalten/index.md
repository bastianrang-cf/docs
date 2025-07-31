:::::::::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Managing permissions]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/berechtigungen-verwalten/_index.md){.edit-btn
.float-end}
:::

:::::::::::: p-0
# Managing permissions {#managing-permissions .mb-3 .mt-4}

In cplace permissions for different levels are managed. There are global
permissions, workspace permissions, permissions at type level and
permissions at page level. If there is a hierachical relationship, the
permissions are inherited by default. This means that the permissions
set in a workspace are automatically inherited by the pages of the
respective workspace. However, the succession can be changed by
overwriting the permissions, e.g., for a page.

## Global permissions

Global permissions are permissions that apply to the entire installation
of cplace. In the global permissions, for example, you can define which
users are allowed to create new groups, users, or workspaces. The global
permissions are only visible to and can only be edited by members of the
default "Administrators" group.

A description of the global permissions can be found in the section
["Global
permissions".](/user-manual-en/cplace-administrieren/applikationseinstellungen/berechtigungen/)

## Workspace permissions

The workspace permissions define which users or groups have read access
to a workspace (readers) and/or write access (editors). The
administrators of the workspace and optionally layout editors are also
defined in the workspace permissions. Using the "Layout editor" role,
you can authorize users to allow them to edit (type) layouts in the
respective workspace without having to give them full administration
rights in the workspace.

The workspace permissions can only be edited by the administrator of the
respective workspace.

The following table shows an overview of the permissions of the
respective roles in the workspace.

  Permission                                     Readers   Editor   Layout Editors   Administrators
  ---------------------------------------------- --------- -------- ---------------- ----------------
  **Opening workspace/reading pages**            Yes       Yes      Yes              Yes
  **Commenting on pages**                        Yes       Yes      Yes              Yes
  **Downloading files from a page**              Yes       Yes      Yes              Yes
  **Uploading files to a page**                  No        Yes      No               Yes
  **Creating new pages**                         No        Yes      No               Yes
  **Editing pages and their attribute values**   No        Yes      No               Yes
  **Editing the layout of a single page**        No        Yes      No               Yes
  **Moving pages**                               No        Yes      No               Yes
  **Restoring the versions of a page**           No        Yes      No               Yes
  **Editing the permissions of a single page**   No        Yes      No               Yes

**Administration permissions**

  Permission                                     Readers   Editor   Layout Editors   Administrators
  ---------------------------------------------- --------- -------- ---------------- ----------------
  **Opening workspace settings**                 No        No       Yes              Yes
  **Editing the permissions of the workspace**   No        No       No               Yes
  **Adding/removing apps**                       No        No       No               Yes
  **Creating/editing types and attributes**      No        No       No               Yes
  **Defining the layout for types**              No        No       Yes              Yes
  **Exporting a workspace (XML/Excel®)**         No        No       No               Yes
  **Importing pages**                            No        No       No               Yes
  **Clone Workspace**                            No        No       No               Yes
  **Delete Workspace**                           No        No       No               Yes

### Editing workspace permissions

To edit the workspace permissions, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

To be able to edit the workspace permissions, you must be the
"Administrator" of the respective workspace.
:::

::: {.note .note-hint .with-title}
The adjustment of the workspace permissions is executed in a batch job.
The duration of the execution depends on the size of the workspace and
can take a few minutes in the case of a workspace with a large number of
pages.
:::

1.  Open the workspace whose permissions you would like to edit.

2.  Open the workspace settings.

3.  Under "Permissions", click the **\[Edit all\]** button.

4.  Adjust the workspace permissions by selecting individual users or
    groups for the corresponding roles.

5.  Click the **\[Save\]** button.

::: {.note .note-hint .with-title}
**More than one administrator per workspace**

Entering more than one person as the "administrator" of the workspace is
recommended. It can be useful to define a group of administrators as the
"administrator" in every workspace.
:::

### Permissions at type level

Workspace permissions are automatically inherited to the permissions of
a type. You can override or extend these permissions manually in the
properties of a type. In this way, you can exclude or allow access to
pages of a specific type for users or groups.

You can define the permissions for two roles at type level:

- **Editors**: Editors can create, edit, and delete pages and files of
  this type. However, editors cannot edit the attributes and layouts of
  the type.
- **Readers**: Readers have read access to all pages of the type.

You also have the option of defining whether editors of a type may
delete pages of this type. To allow editors of a type to delete pages of
this type, activate the checkbox "**Editors may delete pages**". If you
deactivate the checkbox, only administrators of the workspace can delete
pages of this type. Editors of a type are allowed to perform deletions
by default and so the checkbox is always activated.

#### Editing permissions of a type

To edit the permissions of a type, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

To be able to edit the permissions of a type, you must be the
"administrator" of the respective workspace.
:::

1.  Open the page of the type for which you would like to edit the
    permissions.

2.  Click the **Properties** tab in the page navigation bar.

3.  Under "Permissions", click the **\[Edit all\]** button.

[]{.fas .fa-check-square} The editing mode opens.

::: {.note .note-tip .with-title}
**Display the succession of permissions**

When you hover your mouse pointer over , you can display the succession
of the permissions and see whether these have been overridden or
extended at a specific place.
:::

4.  By clicking the button , you can choose whether the inherited
    settings are to be inherited and added ("Inherit and add") or
    overridden ("Override with") with the new selection.

5.  Edit the corresponding permissions.

6.  (Optional) Deactivate the checkbox "Editors may delete pages" if you
    want to prevent pages of this type from being deleted by page
    editors.

7.  Click the **\[Save\]** button.

## Permissions at page level

Permissions at type level are automatically inherited to pages created
from this type. You can override or extend these permissions manually in
the properties of a page. In this way, you can exclude or allow access
to specific pages for users or groups.

You can define the permissions for two roles at page level:

- **Editors**: Editors can edit the page.
- **Reader**: Readers can only read the page, but not edit it.

::: {.note .note-hint .with-title}
**Set permissions manually for each newly created page**

You can make a setting whereby the permissions must be defined manually
for each newly created page. You can find out how to make this setting
in the section ["Setting page permissions when creating new
pages"](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/arbeitsbereichseinstellungen/#setting-page-permissions-when-creating-new-pages).
:::

Workspace administrators always have access to all pages of the
workspace. The workspace administrators are therefore always displayed
in a page's permissions but they cannot however be changed for an
individual page.

Deviating page permissions can be reset by workspace administrators (see
the section ["Resetting deviating
permissions"](/user-manual-en/cplace-administrieren/berechtigungen-verwalten/abweichende-berechtigungen/)).

::: {.note .note-hint .with-title}
**Inherited permissions of a page for subpages of another type**

It is important to know that the permissions at page level always
override the permissions at type level. The following case can therefore
arise:

- You have one page A (of type 1) with two subpages A1 (of type 1) and
  A2 (of type 2).
- You have set different permissions for types 1 and 2.

Despite this, in this case, all pages (A, A1 and A2) have the
permissions which are defined in type 1. The reason is that the
permissions of page A (type 1) are inherited to its subpages A1 and A2
and thereby override the permissions at type level. You do however have
the option of overriding these permissions manually.
:::

### Editing permissions of a page

To edit the permissions of a page, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must have the "Editor" role for the page to change the permissions
of this page. The "administrators" and "editors" of a workspace are
automatically the "editors" of all pages in this workspace.
:::

1.  Open the page for which you would like to edit the permissions.

2.  In the page navigation bar, click **Page Settings** to display the
    available tabs.

3.  Click the **Properties** tab.

4.  Under "Permissions", click the **\[Edit all\]** button.

[]{.fas .fa-check-square} The editing mode opens.

::: {.note .note-tip .with-title}
**Display the succession of permissions**

When you hover your mouse pointer over , you can display the succession
of the permissions and see whether these have been overridden or
extended at a specific place.
:::

5.  By clicking the button , you can choose whether the inherited
    settings are to be inherited and added ("Inherit and add") or
    overridden ("Override with") with the new selection.

6.  Edit the corresponding permissions.

7.  Click the **\[Save\]** button.

### Transferring permissions to subpages

You have the option of transferring the set permissions of a page to all
its subpages. You can transfer the read and write rights independently
of each other. This does not include subpages for which you do not have
any read or write rights for the settings.

To transfer the permissions of a page to all its subpages, proceed as
follows:

1.  Open the page whose read and/or write rights you would like to
    transfer to all subpages.

2.  In the page navigation bar, click **Page Settings** to display the
    available tabs.

3.  Click the **Properties** tab.

4.  Under "Permissions", click the **\[Edit all\]** button.

[]{.fas .fa-check-square} The editing mode opens.

5.  If you would like to transfer the write rights of this page to the
    subpages, click the **\[Set write rights for all subpages\]** button
    under "Editor." If you would like to transfer the read rights of
    this page to the subpages, click the **\[Set read rights for all
    subpages\]** button under "Reader."

[]{.fas .fa-check-square} The "Reset rights for all subpages" dialog
opens, which shows you how many pages are affected by this change.

6.  If you would like to set the rights for all subpages, click the
    **\[OK\]** button.

[]{.fas .fa-check-square} The dialog closes and the rights are reset.

------------------------------------------------------------------------
::::::::::::

1.  [ Reset Deviating
    Permissions](/user-manual-en/cplace-administrieren/berechtigungen-verwalten/abweichende-berechtigungen/){.px-2
    .py-3 .d-block .text-13}
::::::::::::::
