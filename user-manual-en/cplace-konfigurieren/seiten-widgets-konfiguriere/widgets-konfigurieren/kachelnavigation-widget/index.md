::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Configuring
pages/widgets](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/){.docs-subsubtopic-page}
/ [Configuring
widgets](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/){.docs-subsubtopic-page}
/ [\"Tile Navigation\" widget]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/kachelnavigation-widget.md){.edit-btn
.float-end}
:::

# "Tile Navigation" widget

The "Tile Navigation" widget allows you to navigate from one page to
another without using the workspace navigation menu.

::: md__image
[](../../../../graphics/kapitel-unabhaengig/Kachel-Navigation.png)

![\"\"](../../../../graphics/kapitel-unabhaengig/Kachel-Navigation.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You have to have installed the **Tile Navigation** app.

For more information on installing apps, see the section ["Adding an app
to a
workspace".](/user-manual-en/cplace-konfigurieren/apps/app-zu-arbeitsbereich-hinzufuegen/)
:::

To configure the "Tile Navigation" widget, proceed as follows:

1.  On the page to which you want to add the widget, click **Page
    Settings** in the page navigation bar to display the available tabs.

2.  Click the **Layout** tab.

    []{.fas .fa-check-square} The layout preview for this page is
    displayed.

3.  Add the "Tile Navigation" widget at the desired place. You can find
    more information in the section ["Adding a widget to a page
    layout".](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widget-zu-seitenlayout-hinzufuegen/)

    []{.fas .fa-check-square} The widget is added and displayed in
    configuration mode.

4.  Select a reference page using the drop-down menu. The reference page
    serves as the starting point for the tile navigation. **Workspace
    homepage**, **parent page** and **embedding page** are available to
    be selected.

5.  Deactivate the checkbox "Include reference page in navigation" if
    the reference page is not to be part of the navigation.

6.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The configuration has been completed.

# Adding a page to the tile navigation

::: {.note .note-hint .with-title}
**Add page to tile navigation that is not of type "text page"**

If you would like to add a page which is not of the type "text page" to
the tile navigation, you must first create an "Add to tile navigation"
attribute with the following configuration for this page type:

- Internal name: cf.cplace.navigationTileWidget.showInNavigationWidget
- Attribute type: Checkbox

More information on creating an attribute can be found in the section
["Adding an attribute to a
type".](/user-manual-en/cplace-konfigurieren/attribute/attribut-zu-einem-typ-hinzufuegen/)
:::

To ensure that a page is displayed in the "Tile Navigation" widget,
proceed as follows:

1.  In the page navigation bar, click **Page Settings** to display the
    available tabs.

2.  Click the **Properties** tab.

    []{.fas .fa-check-square} The properties of this page are displayed.

3.  Activate the "Include in tile navigation" checkbox.

4.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The page is added to the tile navigation.
:::::::
