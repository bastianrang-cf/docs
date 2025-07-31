:::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Configuring
pages/widgets](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/){.docs-subsubtopic-page}
/ [Configuring
widgets](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/){.docs-subsubtopic-page}
/ [\"Table\" widget]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/tabellen-widget.md){.edit-btn
.float-end}
:::

# "Table" widget

This widget creates a table of search results that you can filter
according to specific criteria.

## Structure of the "Table" widget

The following image provides an overview of the structure of the table:

::: md__image
[](../../../../graphics/cplace-konfigurieren/Tabellen-Widget-Legende.png)

![&ldquo;The figure shows a table widget with the configured title right
at the top, below it within a row, the toolbar, the button for creating
a new element, and at the right border, the \\\"More Options\\\"
button.&rdquo; Below this is the actual table with the pages as rows and
the attributes as columns. The number of hits, the selected rows and the
selected cells are displayed at the bottom of the table, with the
filters set to the
right.\"](../../../../graphics/cplace-konfigurieren/Tabellen-Widget-Legende.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

  No.     Content                           Description
  ------- --------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **1**   Title of the table                If a title is not defined, the search configuration is entered.
  **2**   Toolbar                           Offers various functions (e.g., filters).
  **3**   Create new content                Button for creating content of the type that is entered in the search. If the table is configured for several types, you can select using the dropdown menu to which type the new element is to belong.
  **4**   More options                      Offers export, delete or copy options depending on the table entries currently selected.
  **5**   Header                            Shows the names of the attributes displayed.
  **6**   Item names                        Shows the title of the respective table entry.
  **7**   Active sortings                   Shows the search filter that is currently active.
  **8**   Hits/Selected rows/Marked cells   Displays the number of hits, selected rows and marked cells.

## Configuring the "Table" widget

Follow these steps to configure a table:

1.  On the page to which you want to add the widget, click **Page
    Settings** in the page navigation bar to display the available tabs.

2.  Click the **Layout** tab.

    []{.fas .fa-check-square} The layout preview for this page is
    displayed.

3.  Add the widget with the name "List" at the desired position (see the
    section ["Adding a widget to a page
    layout"](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widget-zu-seitenlayout-hinzufuegen/)).

    []{.fas .fa-check-square} The widget is added and displayed in
    configuration mode.

4.  Define a search that contains all the objects that you want to
    display in the table. Information on the detailed search can be
    found in the section ["Detailed and advanced
    search".](/user-manual-en/cplace-anwenden/inhalte-suchen-und-wiederfin/detail-und-erweiterte-suche/)

5.  Select the attributes to be displayed in the table.

6.  Specify whether the table contents are to be displayed single-spaced
    by selecting or deselecting the checkbox.

7.  Decide whether to display the header, toolbar, links in the name
    column, name, and the "Create new" button.

8.  (Optional) Make adjustments to the sorting of table contents.

9.  (Optional) In the "Group" option, select the attribute by which the
    table contents should be grouped by default.

10. Click the **\[Save\]** button.

[]{.fas .fa-check-square} The widget configuration is saved and the
table refreshed.

## Configuring a linked table

You can use a linked table to output relative search hits in another
table, starting from the selection of a page in a table.

Follow these steps to configure a linked table:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

There must already be another table on the page on which you want to add
the linked table.
:::

1.  Open the page where you would like to make the widget available.

2.  Switch to the **Layout** tab.

3.  Add the widget with the name "List" at the desired position (see the
    section ["Adding a widget to a page
    layout"](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widget-zu-seitenlayout-hinzufuegen/)).

    []{.fas .fa-check-square} The widget is added and displayed in
    configuration mode.

4.  Under **Linked table**, choose the table to which the new table is
    to relate.

5.  Define a search that contains all the objects that you want to
    display in the table. Information on the detailed search can be
    found in the section ["Detailed and advanced
    search".](/user-manual-en/cplace-anwenden/inhalte-suchen-und-wiederfin/detail-und-erweiterte-suche/)

    ::: {.note .note-hint .with-title}
    **Relative search criterion "Selection in linked table" required**

    In order for the search results of the new table to refer only to
    the selected object in the linked table, you must proceed as
    follows:

    1.  Limit the search to the desired type.
    2.  Expand the "Attributes" filter criterion.
    3.  Expand the "Parent object" filter criterion.
    4.  In the "Relative search criterion" drop-down menu, choose the
        option "Selection in linked table".
    5.  Click to confirm the selection.
    6.  Click the **\[Save\]** button to complete the search definition.
    :::

6.  Complete the rest of the configuration as described under
    [Configuring the "Table" widget.](#configuring-the-table-widget)

    []{.fas .fa-check-square} The linked table has been successfully set
    up.
::::::
