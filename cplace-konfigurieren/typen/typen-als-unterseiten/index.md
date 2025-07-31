:::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Types](/user-manual-en/cplace-konfigurieren/typen/){.docs-subsubtopic-page}
/ [Adding a type as a subpage in the workspace
navigation]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/typen/typen-als-unterseiten.md){.edit-btn
.float-end}
:::

# Adding a type as a subpage in the workspace navigation

By default, you can only create text pages and a few other standard
types with hierarchy relations as subpages in the workspace navigation.
To be able to add further types as subpages in the workspace navigation,
the types concerned must be linked to the desired, higher-level types by
means of a reference attribute and the advanced attribute setting
"Hierarchy relation", but at least to the type "Text page".

::: {.note .note-hint .with-title}
**Only one hierarchy relationship allowed per type**

Each type can have several references to other types, but only one of
these references can be a hierarchy relation.
:::

To be able to add a type as a subpage in the workspace navigation,
proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "administrator" of the workspace.
:::

1.  In the workspace settings, open the type you want to make available
    as a subpage in the workspace navigation.

2.  Switch to the attributes of the type.

3.  Add a new reference attribute with the following configuration:

      Property         Value
      ---------------- -------------------------------
      Internal name    parent
      Display Name     Parent
      Multiplicity     At most one value
      Attribute type   Reference
      Entity kind      Page
      Type(s)          Text page (default.page) (\*)

    (\*) Select the page types under which it should be possible to
    create the subpages of the type.

4.  In the **Advanced** tab, activate the checkbox "Hierarchy relation".

5.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The reference attribute is created. You
    can now select the type as a subpage in the context menu of the
    workspace navigation.
::::::
