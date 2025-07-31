:::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} /
[Appendix](/user-manual-en/appendix/){.docs-subtopic-page} / [Overview
of export and import functions]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/appendix/import-export.md){.edit-btn
.float-end}
:::

# Overview of export and import functions

Data can be exported and also imported at various points in cplace. An
overview of the various export and import functions is provided below.

## Export functions

  Function                                        Description                                                                    Format(s)        Permission                                                                                                   Plug-in/app
  ----------------------------------------------- ------------------------------------------------------------------------------ ---------------- ------------------------------------------------------------------------------------------------------------ -------------
  **User table**                                  Exporting one or more entries from the global user table                       xlsx, xls, csv   Global permission "Editing the types Users and Groups"                                                       Platform
  **Group table**                                 Exporting one or more entries from the global group table                      xlsx, xls, csv   Global permission "Editing the types Users and Groups"                                                       Platform
  **Exporting workspaces** (workspace overview)   Exporting one or more workspaces from the workspace overview                   zip              Administrator permission for the affected workspaces                                                         Platform
  **Exporting a workspace** (in the workspace)    Export of a workspace via its homepage                                         zip, xls, xlsx   Administrator permission for the workspace                                                                   Platform
  **Downloading files** (page, "Files" widget)    Download all attachments of a page                                             zip              Reader permission for the page                                                                               Platform
  **"Table" widget**                              Export of the pages that are displayed in a table                              xlsx, xls, csv   Reader permission for the page with the widget and reader permission for the pages displayed in the widget   Platform
  **Type tables**                                 Export a type (including all pages and attributes) to the workspace settings   xlsx, xls, csv   Reader permission for the type                                                                               Platform

## Import functions

  Function                                        Description                            Format(s)   Permission                                   Plug-in/app
  ----------------------------------------------- -------------------------------------- ----------- -------------------------------------------- -------------
  **Types** (workspace settings)                  Import type configurations and pages   xlsx, xls   Administrator permission for the workspace   Platform
  **Importing workspaces** (workspace overview)   Import one or more workspaces          zip         Member of global administrator group         Platform
  **Uploading files** ("Files" widget)            Upload files in the "Files" widget     Any         Editor permission for the page               Platform
::::
