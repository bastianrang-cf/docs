::::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Workspaces](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/){.docs-subsubtopic-page}
/ [Workspace settings]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/arbeitsbereiche/arbeitsbereichseinstellungen.md){.edit-btn
.float-end}
:::

# Workspace settings

In the workspace settings you can configure the permissions of the
workspace, add and remove apps as well as configure types and
attributes.

## Opening workspace settings

You can open the workspace settings in two different ways:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "workspace administrator" or "layout editor" in the
workspace to be able to see and open the workspace settings.
:::

A\) **"Workspace settings" icon:**

1.  Open the "All workspaces" overview.

2.  In the tile of the desired workspace, click the "Workspace Settings"
    button .

    []{.fas .fa-check-square} The **Permissions** tab of the workspace
    settings is opened.

B\) **Workspace navigation:**

1.  Open the workspace.

2.  In the workspace navigation, click **Workspace settings** and click
    on the name of the tab of the workspace settings that you want to
    open in the context menu that now appears.

[]{.fas .fa-check-square} The selected tab of the workspace settings is
opened.

::: {.note .note-tip .with-title}
**Quick access to the workspace settings**

You can hold down the Control key (Windows) or Command key (macOS) when
clicking **Workspace Settings** to go directly to the **Permissions**
tab.
:::

## "Permissions" tab

In the **Permissions** tab, you manage the permissions of the workspace
for the roles "Administrators", "Layout Editors", "Editors", and
"Readers". You can find more information on roles and the assignment of
rights in the section ["Managing
permissions".](/user-manual-en/cplace-administrieren/berechtigungen-verwalten/)

### Setting page permissions when creating new pages

You can set that the page permissions must be defined when creating new
pages. To do this, proceed as follows:

1.  Open the workspace for which you want to make the settings.

2.  Open the workspace settings.

3.  In the "Set Permissions on Page Creation" field, click the "Edit"
    button .

4.  Activate the checkbox.

5.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} The page permissions must now be defined
    when creating new pages.

### Custom Look and Feel

To customize the look and feel of workspaces, you can assign CSS classes
to workspaces, which can be managed centrally via the application
settings. You can assign the same CSS class to several workspaces or use
separate CSS classes for each workspace. It is also possible to assign
several CSS classes to a workspace.

To assign a CSS class to a workspace, proceed as follows:

1.  In the "Permissions" tab, open up the "Look and Feel" menu.

2.  Click the "Edit" button in the "Custom CSS class names" field.

3.  Enter the name of an existing CSS class or enter the name for a new
    CSS class.

::: {.note .note-hint .with-title}
**Assign multiple CSS classes to a workspace**

If you want to assign several CSS classes to the workspace, separate the
class names with a space, for example: `class0 class1`.
:::

4.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} You have assigned one or more CSS classes
    to the workspace. You can find out how to define CSS class rules in
    the section ["Custom CSS class rules for
    workspaces".](/user-manual-en/cplace-administrieren/applikationseinstellungen/ansichtseinstellungen/#custom-css-class-rules-for-workspaces)

## "Apps" tab

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the administrator of the workspace to be able to view and
open the **Apps** tab.
:::

You can see the installed and available apps in the **Apps** tab of a
workspace. Read more about this in the section
["Apps".](/user-manual-en/cplace-konfigurieren/apps/)

## "App settings" tab

This tab is only displayed if apps which permit special configurations
are installed in the workspace. For example, display names or background
colors can be configured, depending on the installed apps.

## "Types" tab

You configure types and their attributes in the **Types** tab of a
workspace. You can find more information under
["Types"](/user-manual-en/cplace-konfigurieren/typen/) and
["Attributes".](/user-manual-en/cplace-konfigurieren/attribute/)

## "UML view" tab

In the **UML view** tab, the current configuration of the types is
displayed graphically in the form of a UML view.

::: md__image
[](../../../graphics/cplace-konfigurieren/UML-Diagramm-de.png)

![\"\"](../../../graphics/cplace-konfigurieren/UML-Diagramm-de.png){loading="lazy"
aria-label="Enlarged version of the current image"}
:::

## "UML reference view" tab

This tab is displayed only if a workspace has been selected in the
application settings in the "Workspace with global types" option in the
section
["Defaults".](/user-manual-en/cplace-administrieren/applikationseinstellungen/voreinstellungen/)

Global and common types are also displayed in the UML reference view in
addition to the local types of the current workspace.

## "Versions" tab

As with all other pages, the workspace configuration is also versioned
so that a change made previously, for example to the permissions, can
easily be undone. In principle, restoring a previous configuration works
in the same way as for pages (see
["Versions"](/user-manual-en/cplace-anwenden/seiten/versionen/)).
:::::::::
