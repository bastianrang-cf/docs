::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Attributes](/user-manual-en/cplace-konfigurieren/attribute/){.docs-subsubtopic-page}
/ [Adding a linked attribute]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/attribute/verlinktes-attribut-hinzufuegen.md){.edit-btn
.float-end}
:::

# Adding a linked attribute

You can use the
["Reference"](/user-manual-en/cplace-konfigurieren/attribute/relationsattribut-hinzufuegen/)
attribute type to link to another type within a type. To display one or
more attributes of the respective linked page in the current type, you
must add these attributes explicitly as linked attributes in advance.

To add a linked attribute, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisites**

You must be the "administrator" of the workspace. At least one reference
attribute to another type is defined in the type.
:::

1.  Open the workspace in which the type to which you would like to add
    a linked attribute is defined.

2.  In the workspace navigation menu, click **Workspace settings** to
    open these.

3.  Click the **Types** tab.

    []{.fas .fa-check-square} The table with the types of this workspace
    is displayed.

4.  In the table, search for the type to which you would like to add a
    linked attribute.

5.  Click the name of the type.

    []{.fas .fa-check-square} The type definition page is opened. All
    the pages of this type are displayed in a table.

6.  On the type definition page, click the **Attributes** tab to open
    the overview of all attributes of this type.

    []{.fas .fa-check-square} The attribute overview of the type is
    displayed.

7.  Click the **\[+ New linked attribute\]** button.

    []{.fas .fa-check-square} The "Create a new attribute" dialog is
    opened.

8.  Enter an internal name, a display name and a display short name.

    The internal name is used to identify the attribute uniquely within
    a type.

    The attribute is displayed with the display name in the table and
    the "Attributes" widget. If the attribute is displayed as a column
    in a table and the width of the column is narrow, the display short
    name may be used. You should therefore enter an abbreviated name or
    an abbreviation as the display short name.

9.  In the "Linked attribute" selection field, select the required
    attribute of a type linked by way of a reference.

    Only attributes of types for which a reference attribute has already
    been added in the current type are displayed in the selection.

    You can only select one attribute within a linked attribute in each
    case.

    The notation in the selection list is structured as follows:

    internal name of the reference attribute (of your own type) \>
    internal name of the attribute (of the linked type) \`

    (Optional) In the "Create new attribute" dialog, click the
    **Advanced** tab to define further settings for the linked
    attribute.

10. Click the **\[Save\]** button.

[]{.fas .fa-check-square} The linked attribute is created. The attribute
overview is displayed.
:::::
