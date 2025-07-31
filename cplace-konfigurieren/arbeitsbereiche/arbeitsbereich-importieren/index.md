:::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Workspaces](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/){.docs-subsubtopic-page}
/ [Importing a workspace]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/arbeitsbereiche/arbeitsbereich-importieren.md){.edit-btn
.float-end}
:::

# Importing a workspace

## Importing a single workspace

To import a previously exported workspace as a new workspace, proceed as
follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You require the global "Create workspaces" permission.
:::

1.  Open the workspace overview.

2.  Next to the **\[+ Create new workspace\]** button, click the arrow
    to display more options.

3.  Click the **Import workspace** menu option.

    []{.fas .fa-check-square} The "Import workspace" dialog is
    displayed.

4.  In the "Workspace zip" option select the zip file of a previously
    exported workspace.

5.  Enter a new name for the workspace to be imported.

6.  Click the **\[Save\]** button to run the import.

    []{.fas .fa-check-square} The import is run in a separate batch job.

7.  Click the **Go to the imported workspace** link to open the imported
    workspace.

    If you have closed the import dialog in the meantime in order to run
    the import in the background, you can reopen the batch job using the
    user menu and the **Batch jobs** menu option.

    []{.fas .fa-check-square} The workspace settings of the imported
    workspace are opened.

    ::: {.note .note-hint .with-title}
    **Role assignments of the workspace are not imported**

    After the import initially only you, as the workspace administrator,
    have access to the workspace.\
    Previous assignments to roles are not applied during the import.\
    Re-add the required "readers", "editors", and "administrators"
    manually to the workspace settings.
    :::

## Importing multiple workspaces

To import a workspace zip with multiple workspaces, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You require the global "Create workspaces" permission.
:::

1.  In the workspace overview, open the drop-down menu next to the
    **\[Create new workspace\]** button.

2.  Click the **Import workspaces** menu option.

    []{.fas .fa-check-square} The "Import multiple workspaces" dialog is
    displayed.

3.  In the "Zip file" option, select the zip file with the previously
    exported workspaces.

4.  Click the **\[Save\]** button to run the import.

    []{.fas .fa-check-square} The import of the workspaces is started.

5.  Reload the workspace overview after the workspaces have been
    imported so that the imported workspaces are displayed.

    ::: {.note .note-hint .with-title}
    **Role assignments of the workspaces are not imported**

    After the import, only you as the workspace administrator initially
    have access to the imported workspaces.\
    Previous assignments to roles are not applied during the import.\
    Re-add the required "readers", "editors", and "administrators"
    manually to the workspace settings.
    :::
::::::
