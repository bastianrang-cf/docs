:::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Application
Settings](/user-manual-en/cplace-administrieren/applikationseinstellungen/){.docs-subsubtopic-page}
/ [Defaults]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/applikationseinstellungen/voreinstellungen.md){.edit-btn
.float-end}
:::

# Defaults

You can carry out settings for workspaces and users in the **Defaults**
tab of the application settings:

## Workspace settings

  Setting                                        Description
  ---------------------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Default Workspace Navigation State**         Defines the default expansion state of the Workspace Navigation.
  **Workspace with Global Types**                (Optional) Select a workspace here. The types of this workspace are displayed as global types in the UML reference view in the workspace settings.
  **Limit for the number of exportable pages**   Define here the maximum number of pages that may be exported during a single table or workspace export operation. When the number of pages to be exported in one export exceeds the set limit, the export is not executed and a corresponding message is shown. The value "0" stands for "no limit". More information on exporting workspaces can be found in the section [Exporting a workspace.](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/arbeitsbereich-exportieren/)
  **Edit Workspace Order**                       You define here the order of the workspaces that is displayed in the workspace overview.

## User default settings

These default settings can be overridden by the user in the profile:

  -----------------------------------------------------------------------
  Setting                             Description
  ----------------------------------- -----------------------------------
  **Watching of user's contributions  When this function is activated,
  allowed by default**                you can watch the activity
                                      streams/changes made by users
                                      explicitly. \*Default value:
                                      Deactivated

  **Available languages**             Specify here which languages are
                                      available on the tenant. The first
                                      language you list in the
                                      **Available languages** field is
                                      set as the tenant's default
                                      language. *Note:* Language-specific
                                      attribute values are preserved even
                                      if you remove one of the available
                                      languages.\
                                      *Input: Language abbreviation
                                      consisting of two letters according
                                      to ISO 639-1; separated by a comma*

  **Default Locale**                  The default locale defines the
                                      language in which the user
                                      interface is displayed. The value
                                      of this field cannot be changed
                                      manually, but is determined by the
                                      first language specified in the
                                      "Available languages" field.

  **Default Date Locale**             The date locale defines how date
                                      values and times are displayed. Any
                                      change made to the setting only
                                      takes effect the next time you log
                                      in.

  **Default Number Locale**           The default number locale defines
                                      how numbers are displayed in cplace
                                      (e.g., decimal and thousands
                                      separators). Any change made to the
                                      setting only takes effect the next
                                      time you log in.
  -----------------------------------------------------------------------

## Table default settings

  Setting                                                 Description
  ------------------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------------
  **Default view single spaced**                          When activated, all tables (including on type pages) are opened by default in single-spaced mode. \*Default value: Deactivated
  **Maximum number of displayed values per table cell**   Define here how many values are displayed at most in one table row. Set the value to **0** to display all values. *Default value: 100*

## Control Settings

  Setting                                                  Description
  -------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------------------------------------
  **Maximum of displayed entries for reference control**   Define here how many entries are displayed at most in reference controls. Set the value to **0** to display all entries. *Default value: 500*

## Scripting configuration

  Setting                                        Description
  ---------------------------------------------- ----------------------------------------------------------------------------------------------
  **Maximum script runtime (in milliseconds)**   Define here the maximum runtime of the cplaceJS scripts. *Default value: `No limit defined`*

## Alternative Excel® header settings

  Setting                        Description
  ------------------------------ ------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Excel® header text**         Enter here the header you want to use in Excel® files generated by cplace.
  **Excel® header font name**    Enter a font family supported by Excel® that you want to use for the Excel® header.
  **Excel® header font style**   Enter a font style. You can choose from "regular", "italic", "bold", "italic bold" and "bold italic".
  **Excel® header font size**    Specify the font size of the Excel® header.
  **Excel® header font color**   Enter the color you want using hex codes. Alternatively, you can open the color palette by left-clicking in the field and then select the color using the mouse.

## Project planning configuration

Here you can edit general settings of the "Project planning (Basic)" and
"Project planning (Extended)" apps. Further information can be found in
the section ["Application settings for project
planning"](/enterprise-scheduling-en/applikationseinstellungen-zur-projektplanung/)
of the Enterprise Scheduling documentation.

## Presentation Graphic

Here you can edit the general settings of the "Presentation Graphic"
app. Further information can be found in the section ["Global PG
application
settings"](/enterprise-scheduling-en/praesentationsgrafik/globale-pg-applikationseinstellung/)
of the Enterprise Scheduling documentation.
::::
