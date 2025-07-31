::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Application
Settings](/user-manual-en/cplace-administrieren/applikationseinstellungen/){.docs-subsubtopic-page}
/ [Look and Feel]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/applikationseinstellungen/ansichtseinstellungen.md){.edit-btn
.float-end}
:::

# Look and Feel

You can edit the layout and the look and feel of the tenant in the
**Look and feel** tab.

## Logos

  Logo type                          Description
  ---------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------
  **Logo**                           Defines the logo which is displayed in the header at the top left of the screen and on the login screen Document type: png
  **Favicon**                        Defines the favicon which is displayed in the title row of the browser window for pages and saved bookmarks/favorites Document type: ico
  **Touch icon**                     Defines the touch icon which is used when pages are added to the home screen of a smartphone/tablet (iOS/Android)
  **Background of the login page**   Defines the background image which is displayed on the login screen Document type: png

## LESS - Expert Settings

In the LESS settings for experts, adjustments can be made to LESS
variables and thus the look and feel of the tenant can be changed. As
soon as you have saved the configuration in the "Customized LESS
variables for CSS" field, the variables are converted and can be used in
the "CSS settings for experts".

You can set the following variables in the field "Adjusted LESS
variables for CSS":

## General

  Variable                                               Description                                                                                                                                      Default value
  ------------------------------------------------------ ------------------------------------------------------------------------------------------------------------------------------------------------ ---------------------------------------------------
  `@brand-default`                                       Background color for secondary buttons.                                                                                                          `@white`
  `@brand-primary`                                       (Background) color for links and other important buttons, such as primary buttons. Other color variables are often derived from this color.      `@bayern-90`
  `@brand-primary-components`                            Alternative color for primary, interactive elements and widgets. Can be set if `@primary-color` has a different meaning (e.g., red).             `@brand-primary`
  `@brand-info`                                          Base and background color for normal information texts (text color for notes is derived).                                                        `@neutral-40`
  `@brand-success`                                       Base and background color for success messages (text color for notes is derived).                                                                `@success-90`
  `@brand-warning`                                       Base and background color for warnings (text color for notes is derived).                                                                        `@warning-90`
  `@brand-danger`                                        Base and background color for error messages (text color for hints is derived) and critical interaction elements, such as delete buttons.        `@danger-90`
  `@body-bg`                                             Background color for created pages and most system pages.                                                                                        `@white`
  `@text-color`                                          Default text color.                                                                                                                              `@neutral-90`
  `@link-color`                                          Color for icon and text links.                                                                                                                   `@brand-primary`
  `@font-family-sans-serif`                              The system font used. If there are multiple entries, they will be prioritized in bulleted order if a font cannot be displayed.                   `"Roboto", Arial, Helvetica, Sans-Serif`
  `@border-radius-base`                                  Rounding radius for the corners of various elements, such as buttons. Can be specified in absolute (e.g., `px`) or relative (e.g., `%`) units.   `3px`
  `@input-border-radius`                                 Rounding radius for the corners of input fields. Can be specified in absolute (e.g., `px`) or relative (e.g., `%`) units.                        `0px`
  `@modal-border-radius`                                 Rounding radius for the corners of modal dialogs. Can be specified in absolute (e.g., `px`) or relative (e.g., `%`) units.                       `@border-radius-large`
  `@modal-content-bg`                                    Background color for modal dialogs.                                                                                                              `@body-bg`
  `@widget-header-bg`                                    Background color for the headers of widget containers.                                                                                           `@neutral-40`
  `@widget-border-radius`                                Rounding radius for the corners of widget containers. Can be specified in absolute (e.g., `px`) or relative (e.g., `%`) units.                   `0px`
  `@widget-padding`                                      Inner offset of the content of widget containers.                                                                                                `10px`
  `@cf-cplace-cboard-swimlane-separator-bar-thickness`   Thickness of the dividing lines in the "Board" widget.                                                                                           `2px`
  `@cf-cplace-cboard-swimlane-separator-bar-color`       Color of the dividing lines in the "Board" widget.                                                                                               `darken(@cf-cplace-cboard-board-bg-color-2, 15%)`

### L-Navigation

**General**

  Variable                                Description                                                                                                                                                                                                                                                                                                    Default value
  --------------------------------------- -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------------------
  `@l-nav-wm-background`                  Background color of the workspace menu and the logo section of the navigation bar. Also colors the star icon in the favorites menu.                                                                                                                                                                            derived from `@brand-primary`.
  `@l-nav-wm-element-hover`               Background color of the branches in the tree structure, as well as of the workspace settings button and the entries of overflow menus during a mouseover.                                                                                                                                                      derived from `@brand-primary`.
  `@l-nav-wm-element-active`              Background color of the branches in the tree structure, as well as of the workspace settings button, if active.                                                                                                                                                                                                `@brand-primary`
  `@l-nav-tnb-button-text-color`          Text color of the "New", "Workspaces", and "Recents" buttons of the navigation bar.                                                                                                                                                                                                                            `@neutral-90`
  `@l-nav-tnb-button-text-active-color`   Text color of the "New", "Workspaces", and "Recents" buttons of the navigation bar, as well as background color of the buttons of the content header during a mouseover.                                                                                                                                       `@l-nav-wm-element-hover`
  `@l-nav-tnb-icon-button-color`          Color of the icon buttons on the right side of the navigation bar.                                                                                                                                                                                                                                             `@brand-primary`
  `@l-nav-tnb-icon-button-active-color`   Color of the icon buttons on the right side of the navigation bar during a mouseover.                                                                                                                                                                                                                          `@l-nav-wm-element-hover`
  `@l-nav-text-light`                     Light text color for high-contrast display on dark backgrounds. Affects the navigation bar, content header, and overflow menus, in addition to the text and line color of the tree structure in the workspace menu. Text colors are chosen automatically, depending on the contrast of the background color.   `@white`
  `@l-nav-text-dark`                      Dark text color for high-contrast display on light backgrounds. Affects the navigation bar, content header, and overflow menus, in addition to the text and line color of the tree structure in the workspace menu. Text colors are chosen automatically, depending on the contrast of the background color.   `@text-color`
  `@l-nav-overflow-light-background`      Switch to change the color of the overflow menus to white if mouseover colors are not easily visible on a dark background. Can be either `true` or `false`.                                                                                                                                                    `false`

### Explanations of terms

  Term              Explanation
  ----------------- ---------------------------------------------------------------------------------------------------------------------------------
  "mouseover"       A mouseover is the event that is triggered when you hover your mouse pointer over a navigation element.
  "Overflow menu"   An overflow menu is a menu which is displayed adjacent to the clicked element after a button or a menu option has been clicked.

## CSS - Expert Settings

With the help of the "CSS - Expert Settings", you can further customize
the interface of cplace by adding corresponding CSS rules.

### Using LESS variables as CSS variables

You can also use all LESS variables as CSS variables and thus reuse them
for custom CSS settings and for Highcharts. Only variables that are
defined in `customizing-variables.less` or the LESS expert settings can
be used. These variables are only available after successful generation
of customized CSS.

::: {.note .note-example .with-title}
**Example for LESS variables as CSS variables**

``` {tabindex="0"}
:root {
    --surface-a: #ffffff;
    --surface-b: #f8f9fa;
    --content-padding: .5rem .5rem;
    --focus-ring: inset 0 0 0 .1rem, #a4deff;
    --widget-header.bg: #e1e4ea;
    --login-sso-background-color: #EEEFF2;
}
```
:::

::: {.note .note-example .with-title}
**Example for CSS variables in Highcharts**

``` {tabindex="0"}
return {
   chart: {
     backgroundColor: 'var(--surface-section)',
     type: 'line'  
   },
   title: {
     text: "Chart with CSS Color Variables",
     align: 'center',
     margin: 0,
     useHtml: true,
     style: {
        color: 'var(--text-color)'
     }
   },
   series: [{
     data: [1, 2, 5, 10, 20, 50, 100, -100, 100, -100],
     color: 'var(--brand-primary)'
   }]
}
```
:::

### Custom CSS class rules for workspaces

In the "CSS - Expert Settings", you can define CSS class rules which
contain CSS properties for workspaces. The workspaces can be assigned to
these CSS class rules via the workspace settings.

To define a CSS rule for a class, proceed as follows:

1.  Open up the "CSS - Expert Settings" menu.

2.  In the "Custom CSS" field define one or more CSS class rules.

    ::: {.note .note-example .with-title}
    **Example for the definition of CSS class rules**

    For example, to define a CSS rule for the class "class0" in which
    all second-level headings are red and a CSS rule for the class
    "class1" in which all second-level headings are green, enter the
    following code:

    `.class0 h2 { color: red; }`

    `.class1 h2 { color: green; }`
    :::

3.  Click the **\[Save\]** button.

[]{.fas .fa-check-square} You have defined one or more CSS class rules.
You can find out how to assign CSS classes to workspaces in the section
["Custom Look and
Feel".](/user-manual-en/cplace-konfigurieren/arbeitsbereiche/arbeitsbereichseinstellungen/#custom-look-and-feel)

## JavaScript - Expert Settings

Using the "JavaScript - Expert Settings", you can further customize the
behavior of the cplace interface or add additional functions by adding
JavaScript code.

For the "JavaScript - Expert Settings" to be available, the following
requirements must be met:

::: {.note .note-prerequisite .with-title}
The configuration parameter
[`cplace.security.general.user-added-java-script-enabled`](/ops/configuration/reference/#cplace.security.general.user-added-java-script-enabled)
must be activated in the server configuration.
:::

## Chart settings

In the chart settings, you can define the color palette which is used
for displaying pie and bar charts. If you do not enter any color values,
the default color palette is used.
:::::::
