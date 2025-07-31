:::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Types](/user-manual-en/cplace-konfigurieren/typen/){.docs-subsubtopic-page}
/ [Type properties]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/typen/typen-eigenschaften.md){.edit-btn
.float-end}
:::

# Type properties

## Editing type properties

To edit the properties of a type after it is created, proceed as
follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "administrator" of the workspace.
:::

1.  Open the workspace in which the type whose properties you would like
    to edit is defined.

2.  Click **Workspace settings** in the workspace navigation menu and
    then click the menu item **Types** in the context menu that is now
    displayed.

    []{.fas .fa-check-square} The table with the types of this workspace
    is displayed.

3.  In the table search for the type whose properties you would like to
    edit.

4.  Click the name of the type.

    []{.fas .fa-check-square} The type definition page is opened. All
    the pages of this type are displayed in a table.

5.  Click the **Properties** tab.

    []{.fas .fa-check-square} The properties of the type are displayed.

6.  Edit the required property individually, or click the **\[Edit
    all\]** button to edit several or all properties at once.

7.  After editing one or all properties, click the **\[Save\]** button
    to save the changes made to the type properties.

## Overview of type properties

The following table shows you the properties which you can configure for
a type:

  -----------------------------------------------------------------------------------------------------------------------------
  Property                            Description
  ----------------------------------- -----------------------------------------------------------------------------------------
  **Internal name**                   The internal name is used to identify the type uniquely.

  **Display Name (Singular)**         A type is displayed in the cplace interface with this designation (default: German,
                                      English, possibly other languages).

  **Display Name (Plural)**           The type is displayed in the cplace interface with this designation (default: German,
                                      English, possibly other languages).

  **Icon Name**                       Icon with which instances of this type are displayed. Icons from [ Font
                                      Awesome](http://fontawesome.io/icons/){target="_blank" rel="noopener"} can be used by
                                      default.

  **Name generation pattern**         Specifies the pattern according to which the name of a new page of this type is
                                      automatically formed. You can find more information under ["Defining name
                                      generation".](/user-manual-en/cplace-konfigurieren/typen/namensgenerierung-definieren/)

  **Pattern for details in search     Define a pattern which specifies with which additional information (attribute values) a
  suggestions**                       search hit/suggestion is displayed.

  **Counter for name generation**     The instances of a type are incremented consecutively. The name generation counter shows
                                      the current status. It can also be edited, however.

  **Page names are unique**           If this checkbox is activated, the page names for pages of this type must be unique
                                      within the workspace. In this case, there can be no pages in the workspace with the same
                                      name.

  **Using localized display names for This option defines whether multi-lingual display names are to be used. It provides four
  pages of this type**                settings:\
                                      "No multilingual display names",\
                                      "Optional multilingual display names",\
                                      "Optional names incl. display in new creation dialog",\
                                      "Mandatory multilingualism"

  **Applies to**                      Shows which system type (page, user, file, group, system group) the type applies to. This
                                      field can only be set when you are creating a type. You can only create type definitions
                                      for pages and files.

  **Is tuple**                        If this checkbox is activated, the type becomes a tuple. This means that pages of this
                                      type can no longer be created separately, but can only exist below another type. When the
                                      reference to the tuple pages is deleted, these pages are automatically deleted. Using the
                                      "tuple" widget, the instances of a "tuple" type can be displayed on the pages of the
                                      parent type.

  **Show in workspace navigation**    When activated, the type definition page is displayed in the workspace navigation menu.

  **Show "New" button**               When activated, a "Create new" button is displayed in page tables (with a configured
                                      search for this type) and in embedded searches.

  **Show in global "New" dialog**     When activated, the type is displayed in the "Create new" global dialog (in the header).

  **Link to overview page**           If you have opened a page of the type, the icon of the type is displayed in the title. If
                                      this option is activated, clicking the icon takes you to the type definition page. If an
                                      alternative overview page has been selected, clicking the icon takes you to this page.

  **Custom overview page**            (Optional) Select an existing page as the alternative overview page. When you open a page
                                      of this type, this overview page is opened in the workspace navigation menu.

  **Hide Versions Tab on all Pages**  When activated, the "Versions" tab is not displayed on pages of this type.

  **Allows divergent Layouts**        When activated, members of the "Editor" role are permitted to configure divergent layouts
                                      for individual pages of this type. When deactivated, only the workspace "administrators"
                                      are permitted to configure a divergent layout on a page of this type.

  **Show in global search**           When activated, pages of this type are displayed in global searches. When deactivated,
                                      pages of this type are not displayed in global searches despite the fact that they might
                                      match. The detailed search is not affected by this. \*Default value: Activated

  **Prefix of internal attribute      Define a prefix here that is entered as standard in the internal name when new attributes
  names**                             (of the type) are created. You can change the internal name and therefore also the prefix
                                      while a new attribute is being created.
  -----------------------------------------------------------------------------------------------------------------------------

## Type permissions

::: md__image
[](../../../graphics/cplace-konfigurieren/Typen-Berechtigungen-de.png)

![\"\"](../../../graphics/cplace-konfigurieren/Typen-Berechtigungen-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

You can assign divergent permissions for types that are different from
the workspace permissions. In this way, you can allow or exclude access
to pages of a specific type for individual users or groups. Two roles
are available for type permissions:

- **Editors**: Editors can create, edit, and delete pages and files of
  this type. However, editors cannot edit the attributes and layouts of
  the type.
- **Readers**: Readers have read access to all pages of the type.

::: {.note .note-hint .with-title}
**Restrict permissions of editors**

By deactivating the checkbox "Editors may delete pages" you can prevent
editors from deleting pages of this type.
:::

Deviating permissions are displayed in the permissions of the workspace:

::: md__image
[](../../../graphics/cplace-konfigurieren/Arbeitsbereichs-Berechtigungen-ueberschrieben-von-Typ-Berechtigung-de.png)

![\"\"](../../../graphics/cplace-konfigurieren/Arbeitsbereichs-Berechtigungen-ueberschrieben-von-Typ-Berechtigung-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

You can find more information on permissions in the section [Managing
permissions](/user-manual-en/cplace-administrieren/berechtigungen-verwalten/).
::::::::
