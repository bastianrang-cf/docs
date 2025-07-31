:::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Application
Settings](/user-manual-en/cplace-administrieren/applikationseinstellungen/){.docs-subsubtopic-page}
/ [General application settings]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/applikationseinstellungen/allgemeine-applikationseinstellungen.md){.edit-btn
.float-end}
:::

# General application settings

Various settings are available to you in the general application
settings (the **General** tab in the [Application
settings.](/user-manual-en/cplace-administrieren/applikationseinstellungen/applikationseinstellungen_oeffnen/))

## General settings

  ----------------------------------------------------------------------------------------------------------
  Setting                             Description
  ----------------------------------- ----------------------------------------------------------------------
  **Title of all pages**              Specifies which page title is pre-pended to the pages (displayed in
                                      the title row of the browser window or tab).

  **Recipient(s) of registration      If the tenant permits users to (self-)register, the users/groups
  notifications**                     selected here receive a notification as soon as a new user has
                                      registered.

  **Membership after Registration**   Newly registered users are automatically assigned to the groups
                                      selected here.

  **Recipient(s) of server            The users/groups selected here receive server notifications, e.g.,
  notifications**                     when restarting or shutting down the system.

  **User Notifications enabled**      If the checkbox is activated, the
                                      [Notifications](/user-manual-en/cplace-anwenden/benachrichtigungen/)
                                      function is activated by the system.\
                                      *Default: Deactivated*

  **Data Exchange activated**         Activating the checkbox opens up access to the functions of the CCP
                                      (Cross-Company Planning).\
                                      *Note:* Please activate this setting only after consultation with the
                                      collaboration Factory.

  **Home URL**                        If a home URL is registered, users are automatically forwarded to this
                                      URL (in cplace) after they log in. In addition, the logo in the top
                                      navigation bar links to this URL.\
                                      *Default value: no URL*
  ----------------------------------------------------------------------------------------------------------

## Email Settings

  Setting                                              Description
  ---------------------------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Alternative email address for support requests**   The email address entered here is displayed within email templates (e.g., for inviting new users, password generation). Leave the field blank to hide the corresponding reference to the support staff/the support address in the specified email templates.

## Expert Server Settings

+-----------------------------------+-----------------------------------+
| Setting                           | Description                       |
+===================================+===================================+
| **Read-only Mode**                | This setting enables you to block |
|                                   | all write operations on the       |
|                                   | tenant. This mode is useful for   |
|                                   | executing migration operations    |
|                                   | without interruption.\            |
|                                   | *Default value: deactivated*      |
+-----------------------------------+-----------------------------------+
| **Number of days after which      | Using this setting, you can       |
| deleted items are permanently     | define the number of days after   |
| removed**                         | which deleted contents are        |
|                                   | deleted permanently. Once a day,  |
|                                   | all contents that were deleted    |
|                                   | longer than the value specified   |
|                                   | here are deleted permanently.\    |
|                                   | *Default value: 30 (days)*\       |
|                                   | A change to this value only takes |
|                                   | effect with the next nightly      |
|                                   | batch job execution.              |
+-----------------------------------+-----------------------------------+
| **Number of days activities are   | Using this setting, you can       |
| visible in the activity stream**  | define for how long the           |
|                                   | activities of deleted contents    |
|                                   | are stored. Activities of deleted |
|                                   | contents are not removed          |
|                                   | immediately so that they continue |
|                                   | to be visible in the activity     |
|                                   | stream among other contents.\     |
|                                   | *Default value: 37 (days)*\       |
|                                   |                                   |
|                                   | :                                 |
|                                   | :: {.note .note-hint .with-title} |
|                                   | This value must be at least as    |
|                                   | large as the "Number of days      |
|                                   | after which deleted elements are  |
|                                   | permanently removed".             |
|                                   | :::                               |
|                                   |                                   |
|                                   | \                                 |
|                                   | A change to this value only takes |
|                                   | effect with the next nightly      |
|                                   | batch job execution.              |
+-----------------------------------+-----------------------------------+
| **Number of days after which      | You can define the number of days |
| deactivated users are             | after which deactivated users are |
| anonymized**                      | anonymized using this setting.\   |
|                                   | *Default value: -1 (deactivated,  |
|                                   | i.e., deactivated users are never |
|                                   | anonymized)*                      |
+-----------------------------------+-----------------------------------+
| **Email address suffix for        | With this setting you determine   |
| deactivated users after           | which suffix is​used for the email |
| anonymization**                   | addresses of the anonymized       |
|                                   | users. After anonymization, each  |
|                                   | deactivated user receives a       |
|                                   | randomly created identifier,      |
|                                   | which is combined with the suffix |
|                                   | specified here to form an email   |
|                                   | address.\                         |
|                                   | *Note: The anonymized email       |
|                                   | address must still correspond to  |
|                                   | the structure of an email         |
|                                   | address. The input for the suffix |
|                                   | must therefore always begin with  |
|                                   | the character `@`.*\              |
|                                   | *Example: \@domain name*          |
+-----------------------------------+-----------------------------------+
| **Number of days in global        | Specifies how far back in the     |
| activity stream**                 | past an activity is displayed in  |
|                                   | the global activity stream. Note: |
|                                   | Regardless of this setting, a     |
|                                   | maximum of 25 pages are displayed |
|                                   | in the activities, even if older  |
|                                   | activities exist.\                |
|                                   | *Default value: 30 (days)*        |
+-----------------------------------+-----------------------------------+
| **Number of days old jobs are     | Using this setting, you can       |
| kept before being deleted**       | define the number of days after   |
|                                   | which old batch jobs are          |
|                                   | deleted.\                         |
|                                   | *Default value: -1 (deactivated,  |
|                                   | old jobs are never deleted)*      |
+-----------------------------------+-----------------------------------+
| **Activate Feedback Feature**     | Defines whether users can send    |
|                                   | feedback to the collaboration     |
|                                   | Factory feedback system at        |
|                                   | [http://central.collaboration-fa  |
|                                   | ctory.de](http://central.collabor |
|                                   | ation-factory.de){target="_blank" |
|                                   | rel="noopener"} Prerequisite:     |
|                                   | [                                 |
|                                   | https://central.collaboration-fac |
|                                   | tory.de](https://central.collabor |
|                                   | ation-factory.de){target="_blank" |
|                                   | rel="noopener"} can be reached    |
|                                   | from your instance.\              |
|                                   | *Default value: deactivated*      |
+-----------------------------------+-----------------------------------+
| **Trusted servers**               | Only the server names specified   |
|                                   | here are permitted as URL         |
|                                   | parameters for the                |
|                                   | \[*embed*()\]{.math .inline}      |
|                                   | function.\                        |
|                                   | *Input: separated by comma, lower |
|                                   | case only*\                       |
|                                   | *Example:                         |
|                                   | youtube.com,                      |
|                                   | slideshare.net,slidesharecdn.com* |
+-----------------------------------+-----------------------------------+
| **Allowed file extensions**       | Provided that this field is       |
|                                   | empty, any kind of file can be    |
|                                   | uploaded. If you specify file     |
|                                   | extensions here, you can only     |
|                                   | upload files with these file      |
|                                   | extensions.\                      |
|                                   | *Input: separated by comma or     |
|                                   | space*\                           |
|                                   | *Default value: empty*            |
+-----------------------------------+-----------------------------------+
| **File extensions to be opened in | Files with the file extensions    |
| the browser**                     | entered here are opened directly  |
|                                   | in the browser by clicking on the |
|                                   | file name. Files with other file  |
|                                   | extensions are downloaded when    |
|                                   | you click the file name.\         |
|                                   | *Input: separated by comma or     |
|                                   | space*\                           |
|                                   | *Default value: empty*            |
+-----------------------------------+-----------------------------------+
| **Alternative footer**            | An alternative footer text can be |
|                                   | entered here; entry as HTML       |
|                                   | mark-up.                          |
+-----------------------------------+-----------------------------------+
| **Limit for loading initial       | Using this setting, you can       |
| values for column filters**       | define the maximum number of      |
|                                   | values that can be loaded in the  |
|                                   | column filter.\                   |
|                                   | *Default value: 100 (values)*     |
+-----------------------------------+-----------------------------------+
::::
