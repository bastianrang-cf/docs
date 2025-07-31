:::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Types](/user-manual-en/cplace-konfigurieren/typen/){.docs-subsubtopic-page}
/ [Defining name generation]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/typen/namensgenerierung-definieren.md){.edit-btn
.float-end}
:::

# Defining name generation

You can automatically generate the name of a new page of a type. To do
this, a pattern must be defined to generate the name.

To define a pattern for generating the name, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "administrator" of the workspace.
:::

1.  Open the workspace in which the type for which you would like to
    define a name generation pattern is located.

2.  Click **Workspace settings** in the workspace navigation menu and
    then click the menu item **Types** in the context menu that is now
    displayed.

    []{.fas .fa-check-square} The table with the types of this workspace
    is displayed.

3.  Click the name of the type for which you want to define a naming
    pattern.

    []{.fas .fa-check-square} The type definition page is opened.

4.  On the type definition page, switch to the **Properties** tab.

5.  Click to open the "Name generation pattern" item for editing.

    ::: md__image
    [](../../../graphics/cplace-konfigurieren/Arbeitsbereichseinstellungen-Muster-zur-Erzeugung-eines-Namens-bearbeiten-de.png)
    ![\"\"](../../../graphics/cplace-konfigurieren/Arbeitsbereichseinstellungen-Muster-zur-Erzeugung-eines-Namens-bearbeiten-de.png){loading="lazy"
    aria-label="Enlarged version of the current image"}
    :::

6.  Enter the required pattern in the "Name generation pattern" option.

    ::: md__image
    [](../../../graphics/cplace-konfigurieren/Arbeitsbereichseinstellungen-Muster-zur-Erzeugung-eines-Namens-Eingabe-de.png)
    ![\"\"](../../../graphics/cplace-konfigurieren/Arbeitsbereichseinstellungen-Muster-zur-Erzeugung-eines-Namens-Eingabe-de.png){loading="lazy"
    aria-label="Enlarged version of the current image"}
    :::

    ::: {.note .note-info .with-title}
    **Attribute values as variables**

    You can combine static texts with variables in the name generation
    pattern. The values of attributes of the respective page can be used
    as the variable. Simply enter the internal attribute name in angle
    brackets, for example, `<cf.cplace.task.priority>`.

    You can use the variable `<#>` as the name generation counter
    (consecutive number).

    **Example: Automatic name generation for an "Issue" type**

    Pattern: `ISSUE-<#>`

    Page names: "ISSUE-1", "ISSUE-2", ...
    :::

    ::: {.note .note-tip .with-title}
    \
    **Optional attribute values as variables**

    You have the option of adding optional attribute values to the
    automatic name generation. To do this, write the internal name of an
    optional attribute in angle brackets and then place this expression
    in round brackets, e.g., `(<cf.cplace.task.baselineStartDate>)`.

    If no value is set for this attribute for a page when it is created,
    the page name is generated without the attribute name. If such a
    page is subsequently assigned a value for this attribute, the page
    name is adjusted accordingly.
    :::

7.  Click the **\[Save\]** button to save the new name generation
    pattern.

8.  If necessary, reset the "Name generation counter" if, for example,
    you would like to continue the numbering from a higher number or to
    reset the counter back to zero.

9.  Click the **Properties** tab again to refresh the page.

    Alternatively: Press **\[F5\]** on the keyboard to reload the entire
    page.

    []{.fas .fa-check-square} The **\[Refresh the names of all pages\]**
    button is displayed below the "Name generation pattern" field.

    ::: md__image
    [](../../../graphics/cplace-konfigurieren/Arbeitsbereichseinstellungen-Namen-aller-Seiten-anpassen-de.png)
    ![\"\"](../../../graphics/cplace-konfigurieren/Arbeitsbereichseinstellungen-Namen-aller-Seiten-anpassen-de.png){loading="lazy"
    aria-label="Enlarged version of the current image"}
    :::

10. Click the **\[Refresh the names of all pages\]** button so that the
    names of existing pages of this type are changed to the new naming
    pattern.

[]{.fas .fa-check-square} The new naming pattern is applied to the
existing pages and their names are automatically adapted.

::: {.note .note-info .with-title}
**Localized page names**

When you use an attribute as a variable in the naming pattern you define
that has multilingual display names, the page names are adjusted
according to your locale.

Analogously, this also applies to date attributes. In a naming pattern
in which you use a date attribute as a variable, the page name is
adjusted according to your date locale.
:::

## Attribute formats in name generation

You can format the attribute values within the name generation. The
following formats are available to you:

  Format                                               Description
  ---------------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  \<#\\\|numberFormat:\"00000\"\>                      The counter is displayed with leading zeros. The number of zeros in numberFormat defines the length of the total number with a leading zero.
  \<*Numbers attribute*\\\|numberFormat:\"000000\"\>   You can also display decimal places in this format. The number of zeros after the decimal point determines the number of decimal places that are shown in the name.
  \<*Date attribute*\\\|dateFormat:\"MM/yy\"\>         The date specified in the selected date attribute is appended to the static text in your desired date format. The following date abbreviations are permitted: Day: *dd*, month: *MM*, year: *yy* or *YY*
  \<*Text attribute*\\\|transform:\"uppercase\"\>      The attribute you have selected is displayed in upper case letters.
  \<*Text attribute*\\\|transform:\"lowercase\"\>      The attribute you have selected is displayed in lower case letters.
  \<*Any attribute*\\\|limit:\"#\"\>                   The attribute you have selected is limited to a specified number of characters. To do this, replace the **\#** character with the required character limit.
::::::
