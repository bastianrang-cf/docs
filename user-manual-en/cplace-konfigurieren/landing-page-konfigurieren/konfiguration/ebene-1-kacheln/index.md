:::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Configuring a landing
page](/user-manual-en/cplace-konfigurieren/landing-page-konfigurieren/){.docs-subsubtopic-page}
/
[Configuration](/user-manual-en/cplace-konfigurieren/landing-page-konfigurieren/konfiguration/){.docs-subsubtopic-page}
/ [Level 1 tiles]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/landing-page-konfigurieren/konfiguration/ebene-1-kacheln.md){.edit-btn
.float-end}
:::

# Level 1 tiles

The level 1 tiles map links to other pages or any other URLs. They are
only displayed as part of level 0 tiles and must therefore be assigned
to at least one level 0 tile. You can also define level 1 tiles as
"divider tiles" to optimize the display within tile 0.

## Creating a clickable level 1 tile

To create a level 1 tile, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "administrator" of the workspace.
:::

1.  Open the workspace where the "Landing Page" app was added.

2.  Open the workspace settings.

3.  In the context menu, click "Types".

4.  Click the "Level 1 tile" type.

5.  Click the **\[+ New level 1 tile\]** button.

    []{.fas .fa-check-square} The "Provide details for the new level 1
    tile" dialog is displayed.

6.  In the "Name" field, enter an internal name for the level 1 tile.

7.  To set the title of the level 1 tile, enter a name in the "Display
    name" field in each of the languages used.

8.  In the "Assigned level 0 tile" field, select the level 0 tile(s) on
    which you want to display the level 1 tile.

    ::: {.note .note-hint .with-title}
    **Find tiles via search function**

    If the desired tile is not displayed, use the integrated search
    function to search through all available tiles. You can create a new
    level 0 tile using the **\[Create level 0 tile\]** button. For more
    information on creating level 0 tiles, see the section [Level 0
    tiles.](/user-manual-en/cplace-konfigurieren/landing-page-konfigurieren/konfiguration/ebene-0-kacheln/)
    :::

9.  Select a target page to be called up via the level 1 tile.

    ::: {.note .note-info .with-title}
    **Permissions for level 1 tile**

    The permissions of the target page also apply to the level 1 tile.
    Users who do not have read rights for the specified target page
    cannot see the level 1 tile.
    :::

10. (Optional) To link to an external website or web application, insert
    the relevant URL in the "Alternative target URL" field.

11. (Optional) Activate the "Display all attributes" checkbox.

[]{.fas .fa-check-square} All editable attributes of the level 1 tile
are displayed.

12. (Optional) Select how to open the linked page in the drop-down menu
    of the target type.

13. (Optional) To define the display order of the tile within the level
    0 tile, enter a digit in the "Order" field.

14. (Optional) To change the number of tiles per row, set the width of
    the tile in the "Width" field.

15. Click the **\[New level 1 tile\]** button.

[]{.fas .fa-check-square} You have created a level 1 tile.

## Creating a divider tile

A divider tile is a special level 1 tile. Its lower height and
contrasting color mean it has a different display from that of other
tiles. To create a divider tile, proceed as follows:

1.  Open the workspace where the "Landing Page" app was added.

2.  Open the workspace settings.

3.  In the context menu, click "Types".

4.  Click the "Level 1 tile" type.

5.  Click the **\[+ New level 1 tile\]** button.

    []{.fas .fa-check-square} The "Provide details for the new level 1
    tile" dialog is displayed.

6.  Enter an internal name for the divider tile in the "Name" field.

7.  To set the title of the divider tile, enter a name for each of the
    languages used in the "Display name" field.

8.  In the "Assigned level 0 tile" field, select the level 0 tile(s) on
    which you want to display the divider tile.

    ::: {.note .note-hint .with-title}
    **Find tiles via search function**

    If the desired tile is not displayed, use the integrated search
    function to search through all available tiles. You can create a new
    level 0 tile using the **\[Create level 0 tile\]** button. For more
    information on creating level 0 tiles, see the section [Level 0
    tiles.](/user-manual-en/cplace-konfigurieren/landing-page-konfigurieren/konfiguration/ebene-0-kacheln/)
    :::

9.  Select a target page that is to be linked to the divider tile.

    ::: {.note .note-info .with-title}
    **Target page also required for divider tiles**

    The permissions of the target page also apply to the divider tile.
    Users who do not have read rights for the specified target page
    cannot see the divider tile.

    Even if the divider tile is only being created as a dividing element
    between the different level 1 tiles, you still have to specify a
    target page.\
    Using the "None" option in the "Target type" attribute, you can
    configure the divider tile in such a way that it is not displayed as
    a link.
    :::

10. Activate the "Display all attributes" checkbox.

[]{.fas .fa-check-square} All editable attributes of the level 1 tile
are displayed.

11. To prevent the divider tile from being displayed as a link, select
    the option "none" as the target type.

12. (Optional) If you want to display the divider tile as a link, select
    a target type other than "none".

13. Enter a number in the "Order" field to determine the position of the
    divider tile within the level 0 tiles.

14. Change the width of the tile to *1*.

::: {.note .note-hint .with-title}
**Note the width of the predecessor and successor tiles**

Note the width of the tiles preceding and succeeding the divider tile.
The total of the values for the width of the tiles in a row should
always add up to 1 in order to achieve a consistent display.
:::

:::: {.note .note-tip .with-title}
**Dividing separator tiles**

To get a clear outline of the level 1 tiles, use the divider tiles with
a width of 1.

::: md__image
[](../../../../graphics/cplace-konfigurieren/Landing_Page-Beispiel-Trennkacheln-de.png)

![\"\"](../../../../graphics/cplace-konfigurieren/Landing_Page-Beispiel-Trennkacheln-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::
::::

11. Activate the "Divider tile" checkbox.

12. Click the **\[New level 1 tile\]** button.

[]{.fas .fa-check-square} You have created a divider tile.
::::::::
