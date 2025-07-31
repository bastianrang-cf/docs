:::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Workspaces](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/){.docs-subsubtopic-page}
/ [Cloning a workspace]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/arbeitsbereiche/arbeitsbereich-klonen.md){.edit-btn
.float-end}
:::

# Cloning a workspace

To clone an existing workspace, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisites**

You require the global "Create workspaces" permission. You must be the
"administrator" in the workspace that you would like to clone.
:::

::: {.note .note-hint .with-title}
**Set export page limit**

If you have defined a page limit for the export of a workspace, this
also applies to the cloning of a workspace.
:::

1.  Open the workspace that you would like to clone.

2.  Click **Workspace settings** in the workspace navigation menu and
    then click the name of any tab of the workspace settings in the
    context menu that is now displayed.

    []{.fas .fa-check-square} The selected tab of the workspace settings
    is opened.

3.  In the page navigation bar, click the "More" button .

    []{.fas .fa-check-square} The drop-down menu is opened.

4.  Click the **Clone workspace** menu option.

    []{.fas .fa-check-square} The "Clone workspace" dialog is opened.

5.  In the "Clone workspace" dialog enter a name for the new workspace.

6.  Click the **\[Clone\]** button.

    []{.fas .fa-check-square} The workspace to be cloned is
    (automatically) exported and re-imported. For this purpose, a batch
    job is run and the title of the dialog changes to "Import to
    workspace".

7.  After the import has been completed, click the **Go to the imported
    workspace** link to open the clone of the previous workspace.

    If you have closed the import dialog in the meantime in order to run
    the batch job for cloning the workspace in the background, you can
    reopen this batch job using the user menu and the **Batch jobs**
    menu option.

    []{.fas .fa-check-square} The workspace settings of the cloned
    workspace are opened.

    ::: {.note .note-hint .with-title}
    **Role assignments of the workspace are not adopted**

    After the cloning, only you, as the workspace administrator, have
    access to the workspace to begin with.\
    Previous assignments to roles are not applied during the import.
    Re-add the required "readers", "editors", and "administrators"
    manually to the workspace settings.
    :::
::::::
