:::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Attributes](/user-manual-en/cplace-konfigurieren/attribute/){.docs-subsubtopic-page}
/ [Adding an attribute to a type]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/attribute/attribut-zu-einem-typ-hinzufuegen.md){.edit-btn
.float-end}
:::

# Adding an attribute to a type

To add a new attribute to a type, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "administrator" of the workspace.
:::

1.  Open the workspace in which the type to which you would like to add
    an attribute is defined.

2.  Click **Workspace settings** in the workspace navigation menu and
    then click the menu item **Types** in the context menu that is now
    displayed.

    []{.fas .fa-check-square} The table with the types of this workspace
    is displayed.

3.  In the table, search for the type to which you would like to add an
    attribute.

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
    entered within an attribute.

**Explanation of the multiplicity options**

  Multiplicity           Description
  ---------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Any number of values   Entering/selecting an attribute value when creating a page with this attribute is optional. Any number of values (0 to n) can be entered/selected within the attribute.
  Exactly one value      The attribute becomes a mandatory attribute. When creating a page with this attribute you must enter/select exactly one value.
  At most one value      Entering/selecting an attribute value when creating a page with this attribute is optional. You can enter/select no value or one value within the attribute.
  At least one value     The attribute becomes a mandatory attribute. When creating a page with this attribute it is essential that you enter/select one value. You can enter any number of additional values (1 to n).

::: {.note .note-hint .with-title}
**The multiplicity may depend on attribute type**

Note that the multiplicity allowed depends to a certain extent on the
attribute type. If a multiplicity is not compatible with the chosen
attribute type, a corresponding message will be displayed when you
attempt to save the attribute configuration. Example: A checkbox can be
created only with the multiplicity value "Exactly one value".
:::

::: {.note .note-tip .with-title}
An overview of all attribute types can be found in the section
["Attribute
types".](/user-manual-en/cplace-konfigurieren/attribute/attributtypen/)
:::

9.  Select the required attribute type.

    []{.fas .fa-check-square} Further input fields are displayed when
    choosing the attribute types 'Enumeration Value - Text',
    'Enumeration Value - Number', 'Reference' and 'Number'.

10. Complete the attribute type-dependent fields. For enumeration
    values, enter a value in each case and then click the "Add new
    value" button .

(Optional) Within the dialog window, switch to the **Advanced** tab to
be able to enter additional properties and information for the
attribute. The advanced properties also depend on the attribute type.
You can find more information on the [Advanced attribute
settings](/user-manual-en/cplace-konfigurieren/attribute/erweiterte-attributeinstellungen/)
page.

11. Click the **\[Save\]** button.

[]{.fas .fa-check-square} The attribute is added. The overview of the
attributes is displayed.

::: {.note .note-hint .with-title}
**Language-related attribute value display**

If an attribute value is not defined in the language set by the user,
this value is displayed in the language defined under "Default locale".
You can find more information on the default language setting in the
[Defaults](/user-manual-en/cplace-administrieren/applikationseinstellungen/voreinstellungen/)
section.
:::
::::::::
