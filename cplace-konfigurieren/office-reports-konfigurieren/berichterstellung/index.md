::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Office
Reports](/user-manual-en/cplace-konfigurieren/office-reports-konfigurieren/){.docs-subsubtopic-page}
/ [Report Creation]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/office-reports-konfigurieren/berichterstellung.md){.edit-btn
.float-end}
:::

# Report Creation

The "Report Creation" widget gives you the option of creating and
downloading Office Reports. By selecting a data source in cplace, you
can define which data in the Office Report is evaluated.

By specifying further data types and data type attributes, you can use
these data types or data type attributes in your report using the report
configuration.

::: {.note .note-prerequisite .with-title}
**Prerequisites for creating a report**

- The "cplace Report Creation" app has been added to the workspace.
- A report configuration has already been created.
:::

## Configuring the Report Creation

To configure the "Reporting Creation" widget, proceed as follows:

1.  On the page to which you want to add the widget, click **Page
    Settings** in the page navigation bar to display the available tabs.

2.  Click the **Layout** tab.

    []{.fas .fa-check-square} The layout preview for this page is
    displayed.

3.  Add the "Report Creation" widget at the desired place. More
    information can be found in the section ["Adding a widget to a page
    layout".](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widget-zu-seitenlayout-hinzufuegen/)

    []{.fas .fa-check-square} The widget is added and displayed in
    configuration mode.

4.  Select a report configuration under "Report configuration". You can
    find more information under [Report
    configuration](/user-manual-en/cplace-konfigurieren/office-reports-konfigurieren/berichtskonfiguration/).

5.  Under "Data source", select which data source you would like to use
    to create the Office Report.

6.  Under "File name", specify a file name for your Office Report. If
    you do not specify a file name, a name is automatically generated.

7.  Activate the "Fixed filename" checkbox if an ID is not to be added
    to the specified file name. If you have not specified a file name,
    activating the checkbox will not have any effect and a file name
    will be automatically generated.

    ::: {.note .note-warn .with-title}
    **Overwriting Office Reports**

    When you activate the "Fixed filename" checkbox, any files existing
    at the target location are overridden without a confirmation prompt.
    :::

    ::: {.note .note-hint .with-title}
    **Version history for Office Reports**

    If you would like to use the version history in cplace when creating
    new Office Reports, assign a file name and activate the "Fixed
    filename" checkbox. Every time you create an Office Report, a file
    with the same name is created and saved in the version history in
    cplace.
    :::

8.  Activate the checkbox if a PDF document of the Office Report is to
    be created. If you do not activate the checkbox, the Office Report
    is created in the file format of the template.

9.  Activate the checkbox if the Office Report is to be attached to the
    embedding page of the report creation. When the Office Report is
    created, the file is then automatically uploaded to the embedding
    page and you can find the Office Report in the "Files" widget.

    ::: {.note .note-hint .with-title}
    **Create Office Report as attribute value**

    You have the option of adding the Office Report as the value of an
    attribute of the embedding page. To do this, select the
    corresponding attribute from the "Target attribute on embedding
    page" drop-down menu. The attribute must be a reference attribute
    with the content type "File".\
    When you create an Office Report, the generated Office Report is
    created directly as an attribute value of the attribute you have
    chosen. However you will still find all the Office Reports created
    on this page in the "Files" widget.

    The Office Report is only added as an attribute value of the page if
    the "Attach to embedding page" checkbox is activated. If the
    checkbox is not activated, this setting is ignored.
    :::

10. (Optional) In the drop-down menu "Target type of the generated
    report", choose the type the generated report is to have. The
    selection of the types depends on the page to which the report is to
    be attached. This setting is only relevant if the "Attach to
    embedding page" checkbox is activated.

11. Enter a title for the widget.

12. Deactivate the checkbox if the widget frame is not to be displayed.

13. Under "Label for button" enter a label for the button for generating
    the Office Report. If you do not enter a label, the label "Bericht
    erstellen" will be displayed for the German user interface and
    "Generate Report" for the English user interface on the button by
    default.

14. Under "Additional data type" select a data type that you would like
    to use in the report configuration. You can then assign this data
    type in the script to a variable which corresponds to a placeholder
    in the template.

15. Under "Additional data type attributes" select attributes of a data
    type that you would like to use in the report configuration. You can
    then assign each of these attributes in the script to a variable,
    each of which corresponds to a placeholder in the template.

16. Click the **\[Save\]** button.

[]{.fas .fa-check-square} The configuration mode of the widget closes.
:::::
