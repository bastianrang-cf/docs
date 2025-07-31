::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Workspaces](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/){.docs-subsubtopic-page}
/ [App definition workspace]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/arbeitsbereiche/app-definitions-arbeitsbereich.md){.edit-btn
.float-end}
:::

# App Definition Workspace (ADW)

::: {.note .note-info .with-title}
**App Definition Workspaces will be replaced by Solution Management**

The end of support for App Definition Workspaces (ADW) is planned for
cplace Release 25.2. Use Solution Management instead and migrate your
existing solutions to Solution Management. For more information on
Solution Management, see the section ["Solution
Management"](https://docs.cplace.io/app-dev/solution-management/){target="_blank"
rel="noopener"} in the documentation "cplace Solution Playbook". A guide
for migrating App Definition Workspaces to Solution Management can be
found in the section ["Guideline for Migrating an ADW to Solution
Management"](https://docs.cplace.io/app-dev/solution-management/ada-migrations){target="_blank"
rel="noopener"} in the documentation "cplace Solution Playbook".
:::

An app definition workspace is a workspace that contains a data model of
types, attributes, and layouts but no pages. The data model of the app
definition workspace can be reused in any number of other workspaces in
identical or adapted form by playing it out as an app. An app definition
workspace therefore serves as a template for a data model that does not
have to be recreated time and time again as a result of importing the
app.

Changes which you make to an app definition workspace will be visible in
all workspaces containing this app.

## Creating an app definition workspace (ADW)

To create an app definition workspace, proceed as follows:

1.  Open the workspace overview.

2.  Click beside the **\[+ Create new workspace\]** button.

3.  Choose "Create new app definition workspace".

    []{.fas .fa-check-square} The "Create app definition workspace"
    dialog is opened.

4.  Enter the name of the new workspace.

    ::: {.note .note-hint .with-title}
    **Subsequent name change not possible**

    Note that you cannot change the name of the app definition workspace
    after it has been created.
    :::

5.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The app definition workspace is created.
    The app settings of the new app definition workspace are opened.

## Integrating an app definition workspace in another workspace

To integrate an app definition workspace in another workspace, you must
export the app definition workspace as an app. To do this, proceed as
follows:

1.  Open the app settings of the app definition workspace.

2.  In the page navigation bar, click the "More" button .

    []{.fas .fa-check-square} The drop-down menu opens.

3.  Click the "Deploy App" menu option.

    []{.fas .fa-check-square} The "Deploy app" dialog is opened.

4.  Deactivate the checkbox if the settings are not to be applied.

5.  Click the **\[OK\]** button.

To integrate the app in another workspace, proceed as follows.

1.  Open the workspace settings of the workspace in which you want to
    integrate the app.

2.  Click the **Apps** tab.

3.  Search through the list of available apps for the desired app.

4.  In the "Actions" column beside the desired app, click the **\[Add to
    workspace\]** button.

    []{.fas .fa-check-square} The app is added to the workspace.
:::::
