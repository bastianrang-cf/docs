::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Low-Code Dashboard]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/low-code-dashboard/low-code-dashboard.md){.edit-btn
.float-end}
:::

# Low-Code Dashboard

The Low-Code dashboard enables you to obtain an overview of all Low-Code
scripts of the current instance, to make settings and deactivate
scripts. For more information on how to handle Low-Code, see the
Low-Code documentation in the cplace Knowledge Base at
[docs.cplace.io/lowcode.](https://docs.cplace.io/lowcode/){target="_blank"
rel="noopener"}

::: md__image
[](../../graphics/cplace-administrieren/Low-Code_Dashboard_Home-de.png)

![\"\"](../../graphics/cplace-administrieren/Low-Code_Dashboard_Home-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

## Script types

Under "Script Types" you will find overviews of the individual Low-Code
script types. Click the corresponding tile to display the available
scripts of the respective type.

## Script monitor

Under the "Script monitor" tile you can monitor scripts of all script
types.

### "Script monitor" tab

Under the "Script monitor" tab you will find a table with all Low-Code
scripts of the current instance. In this table you will find the
following information on the scripts:

- Name of the script
- Script type
- Workspace in which the script was created
- Date on which the script was created
- Date of the last change
- Date of the last test run carried out
- Result of the test run with the GraalJS engine
- Status of the script (activated/deactivated)

In addition you can define one or more users under the table in the
field "Recipient for notifications in the event of failed scripts" who
are notified if it has not been possible to run scripts correctly.

### "Running Scripts" tab

Under the "Ongoing Scripts" tab you will find a table of all Low-Code
scripts of the tenant that are currently being run. In this table you
will find the following information on the scripts:

- Start time of the script
- Script type
- Name of the script
- User who has started the script

## Settings

The following settings are available to you in the Low-Code dashboard:

### Script configuration

  ---------------------------------------------------------------------------------------------------------------------------------------------
  Setting                             Description
  ----------------------------------- ---------------------------------------------------------------------------------------------------------
  **Maximum script runtime (in        Define the maximum runtime of the Low-Code scripts here. Scripts which exceed this runtime are canceled.\
  milliseconds)**                     *Default: 'No limit defined\`*\
                                      **Attention:** This is the same setting as under
                                      ["Defaults".](/user-manual-en/cplace-administrieren/applikationseinstellungen/voreinstellungen/)

  **Standard engine for Low-Code      Define which Javascript engine is to be used for the Low-Code scripts. Information on configuring GraalJS
  scripts**                           can be found in the [Operations
                                      Manual.](https://docs.cplace.io/ops/installing-cplace/configuration-for-using-graaljs/){target="_blank"
                                      rel="noopener"}

  **Recipient for notifications in    Define which users are to be notified if a script has not been run correctly.\
  the event of failed scripts**       **Attention:** This is the same setting as under [Script monitor](#script-monitor)
  ---------------------------------------------------------------------------------------------------------------------------------------------

### Permissions

  -----------------------------------------------------------------------------------
  Permission                          Short description
  ----------------------------------- -----------------------------------------------
  **Permission to edit cplaceJS       The users/groups selected here can edit,
  scripts, which can call actions**   activate, deactivate Low-Code scripts and check
                                      them for syntax errors.\
                                      **Please note that this permission can only be
                                      added and removed if the Admin script
                                      "AddRemoveCplaceJSEditPermissionsAction.java"
                                      is run on the server.**

  -----------------------------------------------------------------------------------

## Actions for users with "Write permission for cplaceJS scripts which can call actions"

In the Low-Code dashboard, users with the permission "Write permission
for cplaceJS scripts which can call actions" also have the option of
activating and deactivating scripts and checking them for syntax errors.
To do this, proceed as follows:

### Activating/deactivating scripts

1.  Open the Low-Code dashboard.

2.  Click the "Script monitor" tile.

*Alternatively:* Click the tile of the script type relating to the
script that you want to deactivate.

3.  Navigate in the table to the script that you want to deactivate.

4.  In the **Activated** column, click .

[]{.fas .fa-check-square} The cell is opened for editing.

5.  Activate the checkbox to activate the script.

*Alternatively:* Deactivate the checkbox to deactivate the script.

6.  Click the **\[Save\]** button.

[]{.fas .fa-check-square} The script has been activated/deactivated.

### Checking scripts for syntax errors

1.  Open the Low-Code dashboard.

2.  Click the "Script monitor" tile.

3.  Under the table, click the **\[Run syntax check\]** button.

[]{.fas .fa-check-square} All scripts are checked for syntax errors.
:::::
