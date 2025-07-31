::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Attributes](/user-manual-en/cplace-konfigurieren/attribute/){.docs-subsubtopic-page}
/ [Adding a reference attribute]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/attribute/relationsattribut-hinzufuegen.md){.edit-btn
.float-end}
:::

# Adding a reference attribute

You can create a link to another type by means of an attribute of the
type "Reference".

You must observe certain settings when creating a reference attribute.

In the following paragraphs, you will learn how to add a reference
attribute to a type:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "administrator" of the workspace.
:::

1.  Open the workspace in which the type to which you would like to add
    a reference attribute is defined.

2.  Click **Workspace settings** in the workspace navigation menu and
    then click the menu item **Types** in the context menu that is now
    displayed.

    []{.fas .fa-check-square} The table with the types of this workspace
    is displayed.

3.  In the table, search for the type to which you would like to add a
    reference attribute.

4.  Click the name of the type.

    []{.fas .fa-check-square} The type definition page is opened. All
    the pages of this type are displayed in a table.

5.  On the type definition page, click the **Attributes** tab to open
    the overview of all attributes of this type.

    []{.fas .fa-check-square} The attribute overview of the type is
    displayed.

6.  Click the **\[+ New attribute\]** button.

    []{.fas .fa-check-square} The "Create a new attribute" dialog is
    opened.

7.  Enter an internal name, a display name and a display short name.

    The internal name is used to identify the attribute uniquely within
    a type.

    The attribute is displayed with the display name in the table and
    the "Attributes" widget. If the attribute is displayed as a column
    in a table and the width of the column is narrow, the display short
    name may be used. You should therefore enter an abbreviated name or
    an abbreviation as the display short name.

8.  In the "Multiplicity" field choose how many values can or must be
    selected within the reference attribute.

9.  Select the type "Reference" under "Attribute type".

    []{.fas .fa-check-square} The additional fields "Content type", "In
    this space", and "Type(s)" are displayed.

10. In the "Content type" drop-down menu choose the value "Page".

You can also create references to other content types (system-related
types) of the tenant, e.g., to files, users or groups.

11. Activate the "In this workspace" checkbox. As a result, only types
    of the same workspace will be displayed in the "Type(s)" field.

Remove the checkmark if you want to create a reference to types outside
the current workspace.

[]{.fas .fa-check-square} In accordance with the checkmark you have set,
the "Type(s)" selection list is filled with the types of the same
workspace or the types of all workspaces.

12. In the "Type(s)" field, select the types to which you want to set a
    reference.

You can also select several types if you want to set references to pages
of different types within the same attribute. In most cases, however, it
is wise to separate references into different attributes. To do this,
simply create more references.

13. Click the **\[Save\]** button.

[]{.fas .fa-check-square} The attribute is added. The overview of the
attributes is displayed.
:::::
