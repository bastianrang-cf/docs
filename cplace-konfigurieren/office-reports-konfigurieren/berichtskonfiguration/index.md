::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Office
Reports](/user-manual-en/cplace-konfigurieren/office-reports-konfigurieren/){.docs-subsubtopic-page}
/ [Report configuration]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/office-reports-konfigurieren/berichtskonfiguration.md){.edit-btn
.float-end}
:::

# Report configuration

The "cplace Office Reports" app offers you the option of creating a
report configuration. The created report configuration is then
integrated in the "Report Creation" widget.

::: {.note .note-prerequisite .with-title}
**Requirements for the creation of a report configuration**

- The "cplace Office Reports" app has been added to the workspace.
- A template has already been created in the appropriate format
  (PowerPoint, Word, Excel®).
- You have [Low-Code
  knowledge](https://docs.cplace.io/lowcode/features/reporting/){target="_blank"
  rel="noopener"} for creating the script.
:::

## Creating a report configuration

To create a report configuration, proceed as follows:

1.  Open the workspace settings of the workspace in which you would like
    to create a report configuration.

2.  Open the "Types" tab.

3.  Click the name of the type "Report configuration".

    []{.fas .fa-check-square} The type definition page is opened.

4.  Click the **\[ New Report Configuration\]** button.

    []{.fas .fa-check-square} The "Provide details for the new Report
    Configuration" dialog is opened.

5.  Enter a name for the report configuration.

6.  Enter an identifier for the report configuration.

7.  Click "New Report Configuration".

    []{.fas .fa-check-square} The newly created report configuration
    appears in the table of the type definition page.

## Configuring a report configuration

To configure the report configuration, proceed as follows:

1.  Open the workspace settings of the workspace in which you would like
    to configure a report configuration.

2.  Open the "Types" tab.

3.  Click the name of the type "Report configuration".

    []{.fas .fa-check-square} The type definition page is opened.

4.  Click the name of the report configuration that you would like to
    configure.

    []{.fas .fa-check-square} The page of the report configuration is
    opened.

    ::: {.note .note-info .with-title}
    **Structure of the "Report configuration" page**

    The following widgets are automatically provided to you on the
    report configuration page. You cannot change the layout of the page.

    - *Settings*: Here you can make settings for the report
      configuration.
    - *Script*: Here you can create a script to fill the template with
      content from cplace.
    - *Template*: Only serves to display the available variables in the
      template and cannot be edited.
    - *Script*: Only serves to display the assigned variables and cannot
      be edited.
    - *Files*: In this widget, you upload the template file for your
      Office Report.
    :::

5.  In the "Settings" widget under "Template" select the template that
    you would like to use for the Office Report and click the
    **\[Save\]** button.

    []{.fas .fa-check-square} The available variables from the template
    are displayed to you in the "Template" widget.

    ::: {.note .note-hint .with-title}
    **No template selectable**

    If, at this point, no template is available to you for selection,
    that is because the template file has not yet been uploaded to
    cplace. Here you have the option of uploading the template file and
    then selecting it using the "Files" widget at the end of the page.\
    You can find more information on uploading files in the following
    section [Uploading a
    file](/user-manual-en/cplace-anwenden/dateien-verwalten/datei-hochladen/).
    :::

6.  In the "Script" widget, click and compose a script which assigns the
    content from cplace to the variables. You can find more information
    on writing a script in the [Low-Code
    documentation](https://docs.cplace.io/lowcode/features/reporting/){target="_blank"
    rel="noopener"}.

    ::: {.note .note-hint .with-title}
    **Add presentation graphic to report**

    Using Low-Code you can integrate a Presentation Graphic in a report
    in the PowerPoint format.\
    For more information on this, see the Low-Code documentation under
    the keyword "PGExportComponent".\
    Information on creating and configuring a presentation graphic can
    be found in the [Presentation
    graphic](/enterprise-scheduling-en/praesentationsgrafik/) section of
    the Enterprise Scheduling documentation.
    :::

7.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} In the second widget with the name
    "Script", you will see a list of the variables that you use in the
    script. For each variable you can also see whether it is available
    in the template.

You can now use the created and configured report configuration in the
"Report Creation" widget.
:::::
