::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Configuring
pages/widgets](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/){.docs-subsubtopic-page}
/ [Configuring
widgets](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/){.docs-subsubtopic-page}
/ [Drag and drop prioritization]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/drag-and-drop-priorisierung.md){.edit-btn
.float-end}
:::

# Drag and drop prioritization

The "Drag-and-drop Prioritization" widget displays pages (instances of
types) in a sortable list. In the widget, you can change the order of
the list entries using drag and drop. You can remove the sorting of an
entry by moving an entry to the "Unsorted entries" column.

Follow these steps to configure the "Drag-and-drop Prioritization"
widget:

::: {.note .note-prerequisite .with-title}
**Prerequisites**

- The "Drag and drop list" app must be added to the workspace.
- The page type you display in the list must have at least one number
  attribute that has the "Read Only" permission set in the extended
  attribute properties.
:::

1.  On the page to which you want to add the widget, click **Page
    Settings** in the page navigation bar to display the available tabs.

2.  Click the **Layout** tab.

    []{.fas .fa-check-square} The layout preview for this page is
    displayed.

3.  Add the "Drag-and-drop Prioritization" widget at the desired place.
    For more information on adding widgets, see the page ["Adding a
    widget to a page
    layout".](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widget-zu-seitenlayout-hinzufuegen/)

    []{.fas .fa-check-square} The widget is added and displayed in
    configuration mode.

4.  In the "**Search**" field, configure a search for the types that you
    want to display and sort in the widget.

5.  In the "**Sortable attribute**" field, select the attribute that
    will be used for sorting. This attribute must necessarily be of the
    "Number" attribute type and be configured as "read only" in the
    advanced attribute properties (see prerequisite).

6.  (Optional) Select an "**Attribute that can be used to highlight that
    a draggable item is blocked**".

    Only attributes of the "Checkbox" type can be selected here. Pages
    that have this checkbox activated will only be highlighted in color
    in the widget, but sorting is nevertheless possible.

7.  (Optional) Select an "**Attribute for displaying a 'Type' icon**".

    Only attributes of the "Enumeration - Text" type can be selected
    here. If an appropriate attribute is selected and a value for this
    attribute is set on the pages of a type, the icon of the relevant
    enumeration value will be displayed in the list instead of the icon.

8.  (Optional) In the "**Responsible user**" field, select a reference
    attribute that references the "User" type. The profile image of a
    referenced user is displayed in the relevant list entry.

9.  (Optional) Select a "**Reference attribute whose values will be
    displayed as labels**".

    Only attributes of the "Reference" type can be selected here. Select
    an attribute that references the "Page" content type in order to get
    a meaningful label in the list. The labels are saved in the list
    under the page name.

10. (Optional) Deactivate the "**Show unsorted entries**" option in
    order to hide pages that still do not have a sorting value (default:
    activated i.e., unsorted entries are displayed below the sorted
    entries).

11. (Optional) Activate the "**Show unsorted entries as second column**"
    option in order to display pages that still do not have a sorting
    value in a separate column instead of underneath the sorted entries
    (default: deactivated i.e., the second column is not displayed).

12. Click the **\[Save\]** button.

[]{.fas .fa-check-square} The configuration is saved.
:::::
