:::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Attributes](/user-manual-en/cplace-konfigurieren/attribute/){.docs-subsubtopic-page}
/ [Defining attribute dependencies]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/attribute/attribut-abhaenigkeiten-bestimmen.md){.edit-btn
.float-end}
:::

# Defining attribute dependencies

It is possible to assign certain dependencies to attributes, e.g., to
define rule-based input forms. By defining rules for an attribute, other
attributes of the same type can be influenced. This allows you to decide
which attributes of a form should be mandatory fields depending on the
entered value of a master attribute, hide attributes, or assign
predefined values to other attributes.

To assign dependencies to attributes, install the
"cf.cplace.attributeDependencies" plug-in. This plug-in makes it
possible to show or hide specific attributes based on certain
conditions.

The configuration of attribute dependencies is saved as a JSON file in
the app configuration of a workspace. To configure the dependencies of
attributes, the JSON file can be customized either with Pro-Code via the
"AttributeDependencyBuilder" class or directly in the cplace interface
in the "App settings" section.

For more information about creating and customizing attribute
dependencies, see the Platform Development documentation: [Defining
Attribute
Dependencies.](https://docs.cplace.io/dev-docs/platform-plugin/core/datamodel/custom-data-modeler/defining-attribute-dependencies/){target="_blank"
rel="noopener"}
::::
