::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Types](/user-manual-en/cplace-konfigurieren/typen/){.docs-subsubtopic-page}
/ [Low-Code]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/typen/low-code.md){.edit-btn
.float-end}
:::

# Low-Code

In the Low-Code tab, you can add new functionalities to cplace using
cplaceJS scripts you yourself have defined. For more information on how
to handle cplaceJS, see the Low-Code documentation in the cplace
Knowledge Base at
[docs.cplace.io/lowcode.](https://docs.cplace.io/lowcode/){target="_blank"
rel="noopener"}

## Change listener

::: {.note .note-prerequisite .with-title}
**Prerequisite**

To be able to create change listeners, you will require the permission
"Permission to edit cplaceJS scripts, which can call actions". This
permission cannot be assigned via the interface but only by executing
the `AddRemoveCplaceJSEditPermissionsAction` on the server (the user
email must be entered accordingly in the action).
:::

You can add a change listener to a type. With a change listener you can
define actions which are executed when the values of the selected
attributes are changed. The script is always run after the values have
been changed. For more information on change listeners, see the context
help and the [Low-Code
documentation.](https://docs.cplace.io/lowcode/features/change-listeners/){target="_blank"
rel="noopener"}
:::::
