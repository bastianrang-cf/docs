:::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Application
Settings](/user-manual-en/cplace-administrieren/applikationseinstellungen/){.docs-subsubtopic-page}
/ [System Administration]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/applikationseinstellungen/system-administration.md){.edit-btn
.float-end}
:::

# System Administration

You have direct access to various administrative functions (actions) in
the **System administration** tab of the application settings:

+-----------------------------------+-----------------------------------+
| Action                            | Description                       |
+===================================+===================================+
| **Clear all caches**              | Empties the in-memory caches      |
+-----------------------------------+-----------------------------------+
| **Deleting expired group          | Removes all users for whom the    |
| memberships**                     | expiry date set for the group     |
|                                   | membership has been reached       |
+-----------------------------------+-----------------------------------+
| **Re-built searchable index**     | Runs a batch job for rebuilding   |
|                                   | the document index                |
+-----------------------------------+-----------------------------------+
| **Show all stack traces**         | Shows all the stack traces of the |
|                                   | threads currently available       |
+-----------------------------------+-----------------------------------+
| **Create Performance Snapshot**   | Creates a performance snapshot    |
|                                   | which is written to the file      |
|                                   | /                                 |
|                                   | data/log/performanceSnapshots.log |
+-----------------------------------+-----------------------------------+
| **Show all connection stack       | Shows all the stack traces of     |
| traces**                          | threads with a currently active   |
|                                   | database connection               |
+-----------------------------------+-----------------------------------+
| **Check the consistency of all    | Executes a validation of the      |
| entities**                        | attribute values of all entities  |
+-----------------------------------+-----------------------------------+
| **Delete all types of widget      | Deletes all types of widget       |
| configurations**                  | configurations used internally by |
|                                   | the system (not visible to users, |
|                                   | if necessary, use after updates   |
|                                   | in the event of problems)         |
+-----------------------------------+-----------------------------------+
| **Show document filter status**   | Displays all system tools and     |
|                                   | their status which are used to    |
|                                   | extract the full-text content of  |
|                                   | files                             |
+-----------------------------------+-----------------------------------+
| **Filter all Files again**        | Runs the full-text extraction of  |
|                                   | all files uploaded to cplace once |
|                                   | again so that these are captured  |
|                                   | by the full-text search           |
+-----------------------------------+-----------------------------------+
| **Run job for permanently         | All deleted objects that are      |
| deleting deleted objects**        | older than the set storage period |
|                                   | are deleted permanently.          |
|                                   | Permanently deleted batch jobs    |
|                                   | are no longer displayed in the    |
|                                   | history of the executed batch     |
|                                   | jobs and can no longer be         |
|                                   | searched.                         |
+-----------------------------------+-----------------------------------+
| **Clean up old jobs**             | All concluded jobs are            |
|                                   | permanently removed.              |
+-----------------------------------+-----------------------------------+
| **Run an Admin Script**           | Using this function, you can run  |
|                                   | Admin Scripts (Java classes) for  |
|                                   | the runtime and through the user  |
|                                   | interface. In order to display    |
|                                   | this function, a                  |
|                                   | `admin-scripts-token.txt` file    |
|                                   | must have been saved in the       |
|                                   | 'properties' directory in the     |
|                                   | installation path. The file may   |
|                                   | contain only the token, a random  |
|                                   | number and letter value. The      |
|                                   | token is requested when the admin |
|                                   | script is entered and before it   |
|                                   | is sent, and the execution of     |
|                                   | Java code is thus limited only to |
|                                   | users who know the token.         |
+-----------------------------------+-----------------------------------+
| **Set system message**            | You can set a system-wide message |
|                                   | here that is shown on all pages.\ |
|                                   | Example:                          |
|                                   |                                   |
|                                   | ::: md__image                     |
|                                   | [](../../../graphics/cpla         |
|                                   | ce-administrieren/Administrations |
|                                   | -Dashboard-system-message-de.png) |
|                                   |                                   |
|                                   | ![\"\"](../.                      |
|                                   | ./../graphics/cplace-administrier |
|                                   | en/Administrations-Dashboard-syst |
|                                   | em-message-de.png){loading="lazy" |
|                                   | aria-label="Enlarg                |
|                                   | ed version of the current image"} |
|                                   | :::                               |
+-----------------------------------+-----------------------------------+
::::
