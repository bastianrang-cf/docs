::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Configuring
cplace](/user-manual-en/cplace-konfigurieren/){.docs-subtopic-page} /
[Attributes](/user-manual-en/cplace-konfigurieren/attribute/){.docs-subsubtopic-page}
/ [Advanced attribute settings]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-konfigurieren/attribute/erweiterte-attributeinstellungen.md){.edit-btn
.float-end}
:::

# Advanced attribute settings

On the "Advanced" tab you will find additional properties and
information, depending on the type of the attribute. The following
tables give you an overview of the advanced attribute settings.

The following settings are available for all attribute types:

  Setting                                    Description
  ------------------------------------------ ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Read-only**                              When you activate this checkbox, you cannot edit the value of this attribute.
  **Help for Editors**                       Enter a message here which is to be displayed to a user editing this attribute.
  **Show in "Create new" dialog**            When you activate this checkbox, this attribute is always displayed when a page of the associated type is being created.
  **Show multiple values with line break**   When you activate this checkbox, values of this attribute will be displayed in multiple rows if there are several values.
  **Show in tables**                         When you activate this checkbox, the attribute is displayed by default in tables that are searching for the associated type. You can also display the attribute in a table when the checkbox is deactivated by adding it via the ["Column selection"](/user-manual-en/cplace-anwenden/tabellen/#changing-the-column-selection) dialog.
  **Column width in tables**                 Here specify the column width for tables in pixels.
  **Show in Attributes widget**              When you activate this checkbox, this attribute is displayed in the "Attributes" widget.
  **Show in column configuration**           When you activate this checkbox, this attribute is displayed in the column selection of tables. You can find out how to change the column selection of tables in the section ["Changing the column selection".](/user-manual-en/cplace-anwenden/tabellen/#changing-the-column-selection)
  **Show in User Details**                   \*Only available for attributes of the type "User": If you activate this checkbox, the attribute is displayed in the user details.

The following settings are only available for specific attribute types:

  -----------------------------------------------------------------------------------------------------------------------------------------------
  Setting                 Available for           Description
  ----------------------- ----------------------- -----------------------------------------------------------------------------------------------
  **Default value(s)**    Enumeration value -     If you do not adjust the attribute value manually, the values entered here are automatically
                          text;\                  selected as the value for the attribute when a new page is created.
                          Enumeration value -     
                          number;\                
                          Checkbox; Long text;\   
                          Reference; Text; Number 

  **Regular expression**  Text                    You can define the specific form the content of the attribute value may take using a regular
                                                  printout. For more information, see [Validating the content of text
                                                  attributes](#validating-contents-of-text-attributes).

  **Date specification**  Date                    The date specification defines which unit is to be assigned to the date attribute. Available
                                                  for selection:\
                                                  - Day\
                                                  - Week (KW)\
                                                  - Month\
                                                  - Quarter\
                                                  - Year

  **Date format**         Date                    Specifies in which format the date attribute is to be displayed. Which formats are available to
                                                  you depends on which date specification you have set. The "Default" setting value depends on
                                                  your [Date language
                                                  setting](/user-manual-en/cplace-anwenden/benutzereinstellungen-aendern/spracheinstellungen/).

  **Show date with time** Date                    When you activate this checkbox, you can also specify a time in addition to the date. This
                                                  function is only available if you have selected the unit "Day" under "Date specification".

  **Hierarchy Relation**  Reference               When you activate this checkbox, the page with the reference attribute is subordinated to the
                                                  referenced page. The page with the reference attribute is therefore directly related in the
                                                  hierarchy. If the superordinate page is deleted, the subordinate page is also deleted as a
                                                  result of the hierarchy relation. If, on the other hand, there is no hierarchy relation, the
                                                  page can be deleted without deleting the other page at the same time. A hierarchy relationship
                                                  allows the creation of subpages of a type below pages of the configured types in the workspace
                                                  navigation, see [Adding a type as a subpage in workspace
                                                  navigation](/user-manual-en/cplace-konfigurieren/typen/typen-als-unterseiten/).

  **Show as Subpage in    Reference               When you activate this checkbox, the page with the reference attribute is displayed in the menu
  Menu**                                          as a subpage of the referenced page. This option is only available if you have activated the
                                                  checkbox "Hierarchy relation".

  **Inverse Attribute     Reference               Here you can define an alternative name for the attribute which is displayed in the "Incoming
  Name**                                          references" widget instead of the standard grouping "%type name% as %name of the reference
                                                  attribute%".

  **Show Inverse Role as  Reference               When you activate this checkbox, all incoming references of this reference are displayed in the
  List**                                          widget of the same name as a simple list instead of in tabular form.

  **Enable "Create new"** Reference               When you activate this checkbox, you can create a new page of the referenced type using the
                                                  selection dialog of the reference attribute. This function can only be used if the type to
                                                  which you are adding the reference attribute and the referenced type are located in the same
                                                  workspace.

  **Additional Filter     Reference               Here you can define further filter criteria for the selection dialog of the reference attribute
  Criteria**                                      to restrict the selection options in the dialog to pages which comply with these filter
                                                  criteria.

  **Sort order**          Reference               Here you can define a sort order for the selection dialog of the reference attribute.

  **Validate Additional   Reference               When you activate this checkbox, the system automatically checks whether the selected pages
  Filter Criteria**                               comply with the defined filter criteria under "Additional filter criteria".

  **Hide link to the      Reference               When you activate this checkbox, a link to the referenced page is not displayed on the page
  reference page**                                with the reference attribute.

  **Text appendix**       Enumeration - Number;   Here you can define a text appendix which is displayed after the attribute value. For more
                          number                  information, see [Text appendix for number attributes](#text-appendix-for-number-attributes)

  **Show multilined**     Localized Text          When you activate this checkbox, you can also display the values of this attribute with one or
                                                  more line breaks.
  -----------------------------------------------------------------------------------------------------------------------------------------------

## Validating contents of text attributes

You can define for simple text attributes what form their (text)
contents may take. This is done using what are known as "regular
expressions\*". These are a type of pattern that can be used to define
the exact composition of the content that has been entered. You will
find an introduction to the use of regular expressions on the following
page (external link):
[ https://regexone.com/](https://regexone.com/){target="_blank"
rel="noopener"}

::: {.note .note-prerequisite .with-title}
**Prerequisite**

You must be the "administrator" of the workspace.
:::

Attributes of the "Text" type can be given a formal requirement through
these regular expressions, i.e., they can be validated. To set up a
requirement of this kind, proceed as follows:

1.  Create or edit an attribute of the "Text" type.

2.  Switch to the **Advanced** tab.

3.  Now enter in the "Regular expression" field the desired form against
    which the content of the attribute is to be checked.

    []{.fas .fa-check-square} Two more fields are shown, which you can
    use to specify your own error message for the event that the
    specified text content does not match the regular expression.

    ::: md__image
    [](../../../graphics/cplace-konfigurieren/RE-Feld-mit-Fehlermeldung-de.png)
    ![\"\"](../../../graphics/cplace-konfigurieren/RE-Feld-mit-Fehlermeldung-de.png){loading="lazy"
    aria-label="Enlarged version of the current image"}
    :::

4.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} If a text that does not match the defined
    format is now entered for the attribute, the previously defined
    error message appears.

## Text appendix for number attributes

You can add a text appendix to an attribute of the type "Number" or
"Enumeration value - number". This appendix is displayed after the
attribute value. To add a text appendix to an attribute, proceed as
follows:

1.  Create or edit an attribute of the type "Number" or "Enumeration
    value - number".

2.  Switch to the **Advanced** tab.

3.  Now in the "Text appendix" field enter the text which is to be
    displayed after the attribute value.

4.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} Values of this attribute are now displayed
    with the desired attachment.
:::::
