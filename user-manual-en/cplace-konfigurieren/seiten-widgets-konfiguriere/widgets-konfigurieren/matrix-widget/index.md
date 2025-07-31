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
/ [\"Matrix\" widget]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/matrix-widget.md){.edit-btn
.float-end}
:::

# "Matrix" widget

Using the "Matrix" widget, you can display the contents of a table in
the form of a matrix.

Follow these steps to configure a "Matrix" widget:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

There must already be a table on the page to which you are adding the
"Matrix" widget.

For information on configuring a table, see the section ["Table"
widget.](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widgets-konfigurieren/tabellen-widget/)
:::

1.  On the page to which you want to add the widget, click **Page
    Settings** in the page navigation bar to display the available tabs.

2.  Click the **Layout** tab.

    []{.fas .fa-check-square} The layout preview for this page is
    displayed.

3.  Add the "Matrix" widget at the desired place. You can find more
    information on this in the section ["Adding a widget to a page
    layout".](/user-manual-en/cplace-konfigurieren/seiten-widgets-konfiguriere/widget-zu-seitenlayout-hinzufuegen/)

    []{.fas .fa-check-square} The widget is added and displayed in
    configuration mode.

4.  In the *Table* field, select the table whose contents you want to
    visualize in the "Matrix" widget.

    ::: {.note .note-hint .with-title}
    **Search/filter setting of the linked table**

    The search of the table must at least be limited to one workspace so
    that attributes for the configuration of the axes of the matrix can
    be offered for selection.\
    You can, however, also restrict the search more specifically to one
    or more types.\
    Note that, when filtering on a whole workspace and/or on several
    types, attributes that you use for the following configuration of
    the X and Y axes must be configured in the same way for all types
    (e.g., same internal name, same values in the case of enumeration
    value attributes) so that a uniform display can be provided in the
    "Matrix" widget.
    :::

5.  Select the attribute for the x-axis.

6.  Select the style in which the x-axis is to be displayed.

The following styles are available for you to choose from:

+-----------------------------------+-----------------------------------+
| Style                             | Output                            |
+===================================+===================================+
| **Plain**                         | ::: md__image                     |
|                                   | []                                |
|                                   | (../../../../graphics/cplace-konf |
|                                   | igurieren/Matrix-Schlicht-de.png) |
|                                   |                                   |
|                                   | ![Buttons labeled with the        |
|                                   | text/value of the X attribute     |
|                                   | without additional                |
|                                   | decorations](../../../../gr       |
|                                   | aphics/cplace-konfigurieren/Matri |
|                                   | x-Schlicht-de.png){loading="lazy" |
|                                   | aria-label="Enlarg                |
|                                   | ed version of the current image"} |
|                                   | :::                               |
+-----------------------------------+-----------------------------------+
| **Label**                         | ::: md__image                     |
|                                   | [](../../../../graphics/cplace-k  |
|                                   | onfigurieren/Matrix-Label-de.png) |
|                                   |                                   |
|                                   | ![Buttons labeled with the        |
|                                   | text/value of the X attribute in  |
|                                   | the form of                       |
|                                   | labels](../../../..               |
|                                   | /graphics/cplace-konfigurieren/Ma |
|                                   | trix-Label-de.png){loading="lazy" |
|                                   | aria-label="Enlarg                |
|                                   | ed version of the current image"} |
|                                   | :::                               |
+-----------------------------------+-----------------------------------+
| **Arrow**                         | ::: md__image                     |
|                                   | [](../../../../graphics/cplace-k  |
|                                   | onfigurieren/Matrix-Pfeil-de.png) |
|                                   |                                   |
|                                   | ![Buttons labeled with the        |
|                                   | text/value of the X attribute in  |
|                                   | the form of                       |
|                                   | arrows](../../../..               |
|                                   | /graphics/cplace-konfigurieren/Ma |
|                                   | trix-Pfeil-de.png){loading="lazy" |
|                                   | aria-label="Enlarg                |
|                                   | ed version of the current image"} |
|                                   | :::                               |
+-----------------------------------+-----------------------------------+
| **User-Profile (horizontal)**     | ::: md__image                     |
|                                   | [](../../../.                     |
|                                   | ./graphics/cplace-konfigurieren/M |
|                                   | atrix-Benutzer-Horizontal-de.png) |
|                                   |                                   |
|                                   | ![Buttons with profile picture    |
|                                   | and user names next to each       |
|                                   | other](../../../../graphics/cpla  |
|                                   | ce-konfigurieren/Matrix-Benutzer- |
|                                   | Horizontal-de.png){loading="lazy" |
|                                   | aria-label="Enlarg                |
|                                   | ed version of the current image"} |
|                                   | :::                               |
+-----------------------------------+-----------------------------------+
| **User-Profile (vertical)**       | ::: md__image                     |
|                                   | [](../../..                       |
|                                   | /../graphics/cplace-konfigurieren |
|                                   | /Matrix-Benutzer-Vertikal-de.png) |
|                                   |                                   |
|                                   | ![Buttons with profile picture    |
|                                   | and names of users on top of each |
|                                   | other](../../../../graphics/cp    |
|                                   | lace-konfigurieren/Matrix-Benutze |
|                                   | r-Vertikal-de.png){loading="lazy" |
|                                   | aria-label="Enlarg                |
|                                   | ed version of the current image"} |
|                                   | :::                               |
+-----------------------------------+-----------------------------------+

::: {.note .note-hint .with-title}
**User profile (horizontal) and user profile (vertical)**

The "profile (horizontal)" and "profile (vertical)" function only if the
attribute selected for the axis refers to a user.
:::

7.  Choose the attribute and style for the y-axis in the same way as
    in 5. and 6.

8.  Select the maximum number of results. 500 is selected as the
    default.

9.  (Optional) Define *title*, *height* (of the widget), *minimum width
    of the matrix*, *maximum row height*, the *labeling of the
    X-axis/Y-axis* and *attributes for icons* as required. The
    *Attributes for icons* are used for displaying icons on the matrix
    entries.

10. Click the **\[Save\]** button.

[]{.fas .fa-check-square} The widget configuration is saved and the
matrix is refreshed. You can see an example of a configured matrix
below.

::: md__image
[](../../../../graphics/kapitel-unabhaengig/Matrix-Widget-de.png)

![\"\"](../../../../graphics/kapitel-unabhaengig/Matrix-Widget-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::
:::::::
