::::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Using
cplace](/user-manual-en/cplace-anwenden/){.docs-subtopic-page} / [Visual
Domain Model]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-anwenden/visual-domain-model.md){.edit-btn
.float-end}
:::

# Visual Domain Model

The visual domain model enables you to display different types and their
relations to each other in a clear data model. The visualization of the
data model is done as a class diagram and is based on UML notation.
Types, attributes and connections are represented according to the [ UML
specification](https://www.omg.org/spec/UML/2.5.1/PDF#page=63){target="_blank"
rel="noopener"}.

::: md__image
[](../../graphics/cplace-anwenden/VDM_Beispiel-de.png)

![image](../../graphics/cplace-anwenden/VDM_Beispiel-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

::: {.note .note-prerequisite .with-title}
**Prerequisite**

The "Visual Domain Model" app must be installed.

For more information on installing apps, see the section ["Adding an app
to a
workspace".](/user-manual-en/cplace-konfigurieren/apps/app-zu-arbeitsbereich-hinzufuegen/)
:::

## Creating a new visual domain model

To create a new Visual Domain Model, proceed as follows:

1.  Open the "Visual Domain Model" type page.

2.  Click the **\[+ Create Visual Domain Model\]** button.

    []{.fas .fa-check-square} The "Create Visual Domain Model -
    Attributes" dialog is opened.

3.  Enter a name for the new model.

4.  Click the **\[Create Visual Domain Model\]** button.

    []{.fas .fa-check-square} The visual domain model has been created.

## Functions in the Visual Domain Modeller

After you have created and opened a visual domain model, you can adapt
the model in the Visual Domain Modeller as required. The following
configuration options are available to you:

::: {.note .note-hint .with-title}
**Navigation in the Visual Domain Modeler**

Hold your right mouse button down within the modeller to change your
view to fields which have already been positioned.
:::

### Adding a new type using the list of types

To add a type using the modeller's list of types, proceed as follows:

1.  On the left side of the modeller, click .

2.  Click the workspace in which the type that you would like to add is
    located. You can add types from as many workspaces as you want to
    your visual domain model.

    []{.fas .fa-check-square} All types of the workspace are listed
    alphabetically.

3.  Click the type you would like to add, and using drag and drop drag
    it to the place where you want to place the type in the model.

    *Alternatively:* Enter the name of the type you want to add in the
    search bar and then drag and drop it to the position where you want
    to place the type in the model.

4.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The type has been added to the model.

### Moving and removing fields

To move a field, proceed as follows:

1.  Click the field you would like to move.

    []{.fas .fa-check-square} The borders of the field are highlighted
    in blue.

::: {.note .note-tip .with-title}
**Select multiple fields at the same time**

You can select several fields at the same time by clicking a field and
then while you hold down the [\[Ctrl\]]{.kbd} key, clicking another
field.
:::

2.  Drag the field to the position you want, using the drag and drop
    function.

3.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The field has been moved.

To remove a field from the Visual Domain Model, proceed as follows:

1.  Click the field you would like to remove.

    []{.fas .fa-check-square} The borders of the field are highlighted
    in blue.

2.  Press the Delete key.

3.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The field has been removed.

### Toolbar of the Visual Domain Modeller

The Visual Domain Modeler toolbar offers you the following functions:

::: md__image
[](../../graphics/cplace-anwenden/VDM_Symbolleiste-de.png)

![Illustration of the Visual Domain Modeler toolbar with all
buttons](../../graphics/cplace-anwenden/VDM_Symbolleiste-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

+-----------------------------------+-----------------------------------+
| Icon                              | Short description                 |
+===================================+===================================+
| ::: md__image                     | Undoes the last unsaved change    |
| [](../../graphics                 | you have made.                    |
| /cplace-anwenden/VDM_zurueck.png) |                                   |
|                                   |                                   |
| ![ima                             |                                   |
| ge](../../graphics/cplace-anwende |                                   |
| n/VDM_zurueck.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Restores a change which you have  |
| [](../../graphics/c               | undone.                           |
| place-anwenden/VDM_vorwaerts.png) |                                   |
|                                   |                                   |
| ![image                           |                                   |
| ](../../graphics/cplace-anwenden/ |                                   |
| VDM_vorwaerts.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Adds a new section to the model.  |
| [](../../graphics                 |                                   |
| /cplace-anwenden/VDM_Bereich.png) |                                   |
|                                   |                                   |
| ![ima                             |                                   |
| ge](../../graphics/cplace-anwende |                                   |
| n/VDM_Bereich.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Adds a new note to the model.     |
| [](../../graphi                   |                                   |
| cs/cplace-anwenden/VDM_Notiz.png) |                                   |
|                                   |                                   |
| ![i                               |                                   |
| mage](../../graphics/cplace-anwen |                                   |
| den/VDM_Notiz.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields         |
| [](../../graphics/cplace-a        | horizontally in such a way that   |
| nwenden/VDM_einruecken_links.png) | the left border of all fields is  |
|                                   | lying on a vertical line. The     |
| ![image](../..                    | position of this line is defined  |
| /graphics/cplace-anwenden/VDM_ein | by the left border of the field   |
| ruecken_links.png){loading="lazy" | which previously was the furthest |
| aria-label="Enlarg                | to the left.                      |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields         |
| [](../../graphics/cplace-a        | horizontally in such a way that   |
| nwenden/VDM_einruecken_mitte.png) | their center points are lying on  |
|                                   | a vertical line. The position of  |
| ![image](../..                    | this line is selected by the      |
| /graphics/cplace-anwenden/VDM_ein | center point of the field which   |
| ruecken_mitte.png){loading="lazy" | you clicked first.                |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields         |
| [](../../graphics/cplace-an       | horizontally in such a way that   |
| wenden/VDM_einruecken_rechts.png) | the right border of all fields is |
|                                   | lying on a vertical line. The     |
| ![image](../../                   | position of this line is defined  |
| graphics/cplace-anwenden/VDM_einr | by the right border of the field  |
| uecken_rechts.png){loading="lazy" | which previously was the furthest |
| aria-label="Enlarg                | to the right.                     |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields         |
| [](../../graphics/cplace-         | vertically in such a way that the |
| anwenden/VDM_einruecken_oben.png) | upper border of all fields is     |
|                                   | lying on a horizontal line. The   |
| ![image](../.                     | position of this line is defined  |
| ./graphics/cplace-anwenden/VDM_ei | by the upper border of the field  |
| nruecken_oben.png){loading="lazy" | which previously was the furthest |
| aria-label="Enlarg                | to the top.                       |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields         |
| [](../../graphics/cplace-anw      | vertically in such a way that     |
| enden/VDM_einruecken_zentral.png) | their center points are lying on  |
|                                   | a horizontal line. The position   |
| ![image](../../g                  | of this line is selected by the   |
| raphics/cplace-anwenden/VDM_einru | center point of the field which   |
| ecken_zentral.png){loading="lazy" | you clicked first.                |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields         |
| [](../../graphics/cplace-a        | vertically in such a way that the |
| nwenden/VDM_einruecken_unten.png) | lower border of all fields is     |
|                                   | lying on a horizontal line. The   |
| ![image](../..                    | position of this line is defined  |
| /graphics/cplace-anwenden/VDM_ein | by the lower border of the field  |
| ruecken_unten.png){loading="lazy" | which previously was the furthest |
| aria-label="Enlarg                | to the bottom.                    |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields to the  |
| [](../../graphics/cplace-         | highest level.                    |
| anwenden/VDM_Ebene_ganz_oben.png) |                                   |
|                                   |                                   |
| ![image](../.                     |                                   |
| ./graphics/cplace-anwenden/VDM_Eb |                                   |
| ene_ganz_oben.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields one     |
| [](../../graphics/cp              | level up.                         |
| lace-anwenden/VDM_Ebene_hoch.png) |                                   |
|                                   |                                   |
| ![image]                          |                                   |
| (../../graphics/cplace-anwenden/V |                                   |
| DM_Ebene_hoch.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields one     |
| [](../../graphics/cpla            | level down.                       |
| ce-anwenden/VDM_Ebene_runter.png) |                                   |
|                                   |                                   |
| ![image](.                        |                                   |
| ./../graphics/cplace-anwenden/VDM |                                   |
| _Ebene_runter.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Moves all selected fields to the  |
| [](../../graphics/cplace-a        | lowest level.                     |
| nwenden/VDM_Ebene_ganz_unten.png) |                                   |
|                                   |                                   |
| ![image](../..                    |                                   |
| /graphics/cplace-anwenden/VDM_Ebe |                                   |
| ne_ganz_unten.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Shows/hides a grid pattern in the |
| [](../../graphic                  | background.                       |
| s/cplace-anwenden/VDM_Raster.png) |                                   |
|                                   |                                   |
| ![im                              |                                   |
| age](../../graphics/cplace-anwend |                                   |
| en/VDM_Raster.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Opens a drop-down menu in which   |
| [](../../graphics                 | you can select the language of    |
| /cplace-anwenden/VDM_Sprache.png) | the visual domain model.          |
|                                   |                                   |
| ![ima                             |                                   |
| ge](../../graphics/cplace-anwende |                                   |
| n/VDM_Sprache.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Zooms in closer to the model.     |
| [](../../graphics                 |                                   |
| /cplace-anwenden/VDM_Zoom_in.png) |                                   |
|                                   |                                   |
| ![ima                             |                                   |
| ge](../../graphics/cplace-anwende |                                   |
| n/VDM_Zoom_in.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Zooms out from the model.         |
| [](../../graphics/                |                                   |
| cplace-anwenden/VDM_Zoom_out.png) |                                   |
|                                   |                                   |
| ![imag                            |                                   |
| e](../../graphics/cplace-anwenden |                                   |
| /VDM_Zoom_out.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Runs a batch job which creates a  |
| [](../../graphics/                | downloadable file containing the  |
| cplace-anwenden/VDM_Download.png) | content of the visual domain      |
|                                   | model. You can select whether you |
| ![imag                            | want to create a PNG or a PDF     |
| e](../../graphics/cplace-anwenden | file.                             |
| /VDM_Download.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
| ::: md__image                     | Saves all changes made since the  |
| [](../../graphics/cpla            | last saving process.              |
| ce-anwenden/VDM_Speichern-de.png) |                                   |
|                                   |                                   |
| ![image](.                        |                                   |
| ./../graphics/cplace-anwenden/VDM |                                   |
| _Speichern-de.png){loading="lazy" |                                   |
| aria-label="Enlarg                |                                   |
| ed version of the current image"} |                                   |
| :::                               |                                   |
+-----------------------------------+-----------------------------------+
:::::::::
