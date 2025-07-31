:::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Workspaces](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/){.docs-subsubtopic-page}
/ [Exporting a workspace]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/arbeitsbereiche/arbeitsbereich-exportieren.md){.edit-btn
.float-end}
:::

# Exporting a workspace

You can export a workspace as a zip archive or as an Excel® file. Which
export you choose depends on the intended purpose.

Use the export as a ZIP file to be able to import one or more workspaces
to another tenant. This allows you to transfer cross-workspace
configurations or workspaces that are dependent on each other to other
tenants.

The Excel® export, on the other hand, is useful if you want to export
the pages of one or more types of a workspace in the form of a table.
After modifications have been made to it, the Excel® export can also be
used as a template for importing pages of an individual type.

::: {.note .note-prerequisite .with-title}
**Prerequisites**

- In order to export them, you must be the administrator of the
  workspaces.
- The number of pages of the workspace to be exported does not exceed
  the limits for exportable pages that has been set in the application
  settings.
:::

## Exporting a single workspace as a zip file

To export a workspace as a zip file, proceed as follows:

1.  Open the workspace you would like to export.

2.  In the workspace navigation menu, click **Workspace settings** and
    in the context menu that is then displayed, click any menu option.

    []{.fas .fa-check-square} The page of the selected menu item is
    opened.

3.  In the page navigation bar, click the "More" icon button .

4.  Click the **Export workspace as ZIP** menu option.

    []{.fas .fa-check-square} The "Export workspace" dialog is
    displayed.

5.  In the "Export workspace" dialog, select which elements of the
    workspace you would like to export (types, pages, files).

::: {.note .note-info .with-title}
**Exporting only a configuration**

If you want to export a workspace to transfer only its configuration to
a new workspace on another or the same tenant, activate the checkbox for
"Types" only.
:::

6.  Click the **\[Export\]** button to launch the workspace export.

    []{.fas .fa-check-square} The export of the workspace is started in
    a batch job.

7.  Click the **\[Download\]** button which is displayed after the batch
    job has finished to download the exported workspace as a zip file.

::: {.note .note-tip .with-title}
**Download ZIP file**

If you have closed the dialog in the meantime, open the "Batch jobs"
page in the user menu to download the exported workspace as a zip file.
:::

[]{.fas .fa-check-square} The zip file is downloaded as an export.zip in
your browser.

## Exporting a single workspace as an Excel® file

To export a workspace as an Excel® file, proceed as follows:

1.  Open the workspace you would like to export.

2.  In the workspace navigation menu, click **Workspace settings** and
    in the context menu that is then displayed, click any menu option.

    []{.fas .fa-check-square} The page of the selected menu item is
    opened.

3.  In the page navigation bar, click the "More" icon button .

4.  Click the **Export workspace to Excel® (.xlsx)** or **Export
    workspace to Excel® (.xls)** menu option depending on which file
    format you require the export to be in.

    []{.fas .fa-check-square} The download of the excel_export.xls or
    excel_export.xlsx file is started immediately.

## Exporting several workspaces at once

To export several workspaces in one workspace zip, proceed as follows:

1.  Open the workspace overview.

2.  Click the icon button next to the **\[Create new workspace\]**
    button.

3.  Click the **Export workspaces** menu option.

    []{.fas .fa-check-square} The "Export several workspaces" dialog is
    opened.

4.  Activate the buttons for the items you want to export with the
    workspaces (types, pages, files).

5.  Check the boxes for the workspaces you want to export or the
    checkbox next to the search bar to select all displayed workspaces.

::: {.note .note-tip .with-title}
**Search for workspace**

You can use the search bar to filter the displayed workspaces by name.
:::

6.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The export is run in a batch job. After
    the batch job has finished, the **\[Download\]** button is
    displayed.

7.  Click the **\[Download\]** button to download the zip file with the
    exported workspaces.

    []{.fas .fa-check-square} The selected workspaces have been
    exported.
::::::::
