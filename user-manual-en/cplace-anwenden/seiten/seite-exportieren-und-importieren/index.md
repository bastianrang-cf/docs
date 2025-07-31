:::::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Using
cplace](/user-manual-en/cplace-anwenden/){.docs-subtopic-page} /
[Pages](/user-manual-en/cplace-anwenden/seiten/){.docs-subsubtopic-page}
/ [Exporting and importing a page]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-anwenden/seiten/seite-exportieren-und-importieren.md){.edit-btn
.float-end}
:::

# Exporting and importing a page

On this page you will find out how to export one or more page(s). How
you can import pages to cplace is also demonstrated.

## Exporting pages to Excel® or CSV

To export the displayed pages in a table to Excel® or CSV, proceed as
follows:

::: {.note .note-prerequisite .with-title}
**Prerequisites**

You must have at least the "reader" permission for the pages to be able
to export them. The number of pages to be exported does not exceed the
limit for exportable pages that has been set in the application
settings.
:::

1.  Activate the checkboxes of all pages of a table that you want to
    export. If you do not activate any checkbox, you can export all
    pages displayed in the table at once.

::: {.note .note-info .with-title}
**Only displayed columns are exported**

Note that when you export to Excel® or CSV only the displayed columns
are exported, even if the relevant type has more attributes (=columns).
This is, in particular, relevant if you would like to use the export
file as a template for future imports of the same (page) type.
:::

2.  Click the "Export menu" button above the table.

3.  In the menu, select the format in which you want to export the
    pages.

    []{.fas .fa-check-square} The "Export from table" dialog is opened.

4.  Select whether you also want to export the formatting of text
    attributes.

::: {.note .note-info .with-title}
**Export formatting of text attributes**

When exporting formatting from text attributes, the formatting is
included in the export as HTML markup. If you disable this checkbox, the
attributes will be exported filtered and the formatting will be lost
upon re-import.
:::

5.  Select whether you want to export the display names.

::: {.note .note-hint .with-title}
**Export with display names**

When exporting pages with display names, the pages cannot be
re-imported.
:::

6.  Select whether you want to export unsupported languages.

7.  Click the **\[OK\]** button.

    []{.fas .fa-check-square} The export is started as a batch job.

8.  After the batch job has ended, click the **\[Download\]** button to
    download the exported file. If the batch job requires a longer
    period of time, you can close the "Export from table" dialog. After
    the batch job has finished, you can download the export file using
    the **User settings \> Batch jobs** menu.

## Importing pages using an Excel® file

To import the rows of an Excel® table as new pages of a certain type
into cplace, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisites**

You must be the "administrator" of the workspace to which pages are to
be imported. You have an Excel® file that corresponds to the expected
import format (see section ["Creating an importable Excel®
file"](#creating-an-importable-excel-file)).
:::

1.  Open the workspace to which you would like to import the new pages.

2.  Open the workspace settings.

3.  In the page navigation bar, click the "More" button .

    []{.fas .fa-check-square} The drop-down menu is opened.

4.  Click the **Import Excel®** option.

    []{.fas .fa-check-square} The "Import an Excel® file to workspace"
    page is opened.

5.  Click the **\[Upload file\]** button.

6.  Select the Excel® file to be imported. You also have the option of
    importing references that are not resolvable as simple text (string
    values).

7.  Click the **\[Submit\]** button to run the import.

    []{.fas .fa-check-square} The import is run.

## Creating an importable Excel® file

So that an import from an Excel® file works, the cplace importer
requires mapping information. This mapping information is expected on a
"*mapping*" worksheet and has a defined structure.

To receive an Excel® file with the relevant mapping information, export
the table on the type page of this page type. To do this, proceed as
follows:

1.  Click **Workspace settings**.

2.  Click the **Types** tab.

3.  Click the name of the (page) type you would like to import at a
    later stage.

    []{.fas .fa-check-square} The table with all the pages of this type
    is displayed.

4.  Click above the table to open the drop-down menu with the export
    functions.

::: {.note .note-info .with-title}
**Display names cannot be imported**

Please note that you cannot import pages with display names. Importing
pages with display names results in invalid data.
:::

5.  Click the **Export to Excel® (.xlsx)** or **Export to Excel®
    (.xls)** menu option. Both formats can be used for the subsequent
    import.

    []{.fas .fa-check-square} The table is exported.

6.  Open the exported file in Excel® and delete the pages (rows) it
    contains. Retain the header, however. Do not delete any worksheets.

7.  Enter the attributes of the new pages row by row (one row = one page
    in cplace).

    Note that the name in the first column must be unique as this
    represents the identifier for the importer. If a page with this name
    already exists, this is overridden/refreshed with the data of the
    import file.

8.  Save the changed file.

    []{.fas .fa-check-square} You have created an importable file.
::::::::::
