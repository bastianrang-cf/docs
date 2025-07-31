::::::::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Using
cplace](/user-manual-en/cplace-anwenden/){.docs-subtopic-page} / [Forms
Wizard]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-anwenden/forms-wizard.md){.edit-btn
.float-end}
:::

# Forms Wizard

The cplace Forms Wizard offers the possibility to use No-Code to edit
your own display windows or to create step-by-step input forms and link
them to a wizard. In addition, you can dynamically control the dialog
process as well as data display and data processing with all the
possibilities offered by Low-Code scripts.

A configured wizard intercepts the usual creation dialog of defined
types and runs through the configured steps. Wizards can be activated
and disabled to either disable the usual creation dialog or to be able
to run it again. An incomplete wizard cannot be activated.

This section describes how to configure the wizard with No-Code.
Information on configuring the wizard with Low-Code can be found in the
[Low-Code
documentation.](https://docs.cplace.io/lowcode/features/forms-wizard/){target="_blank"
rel="noopener"}

## Creating a wizard

To create a wizard, proceed as follows:

1.  Open the workspace settings.

2.  In the context menu, click "Types".

3.  Click the "Wizard" type.

4.  Click the **\[+ Create wizard\]** button.

5.  Enter a unique internal name for the wizard in the "Name" field.

6.  In the "Display name" field, enter a name for the wizard to be
    displayed on the interface.

7.  Activate the "Display all attributes" checkbox.

8.  In the "Target workspaces" field, select the workspaces where you
    want the wizard to be available.

9.  In the "Types to trigger" field, select the types for which the
    wizard is to be triggered when they are created.

::: {.note .note-info .with-title}
For the selected types, the wizard is triggered instead of the usual
creation dialog. The attributes of the selected types are displayed
during the configuration of the wizard.
:::

11. Optional: To display the progress of the wizard as a bar while it is
    running, select the "Show progress" checkbox.

12. If no steps have been defined yet, leave the fields "Start step",
    "End steps", and "Summary" empty.

13. Optional: To make the wizard available externally, activate the
    "External wizard" checkbox.

14. Optional: If you make the wizard available externally, add the users
    who should have access to the wizard in the "External access users"
    field.

::: {.note .note-info .with-title}
**Provide wizard externally**

For more information about making the wizard available externally, see
the section ["Making the wizard available
externally".](#making-the-wizard-available-externally)
:::

16. Optional: If you do not want to persist the pages or want to persist
    them dynamically via a script, deactivate the checkbox "Automatic
    persistence".

::: {.note .note-info .with-title}
**Persisting automatically**

When the "Persist automatically" checkbox is activated, all attributes
must have valid values and thus pass all validations.
:::

17. Click the **\[Create Wizard\]** button.

[]{.fas .fa-check-square} You have created a wizard.

## Creating steps

The wizard usually consists of several steps that go through a defined
sequence. You can choose between different step types when creating a
step. You can see which step types exist and which functions they
contain in the chapter [Step types.](#step-types) To create steps,
proceed as follows:

1.  Open the workspace settings.

2.  In the context menu, click "Types".

3.  Click the "Wizard" type.

4.  Click the wizard for which you want to create the steps.

5.  In the "Step Manager" window, click the **\[+ Create step\]**
    button.

6.  In the "Name" field, enter a unique internal name for the step.

7.  Enter a name for the step in the "Title" field.

8.  In the "Type" field, select the kind of step you want to create.

9.  If a successor step has already been created, select the possible
    next steps in the "Possible next steps" field.

10. Enter a unique internal name for the step in the "Identifier" field.

11. Click the **\[Create step\]** button.

[]{.fas .fa-check-square} You have created a step.

## Step types

The function of a step is defined by its step type. To edit steps, click
the corresponding step in the "Step Editor" window.

### "Input mask" step type

For steps of the "Input mask" type, a window is available in the "Step
Editor" to edit an input mask to be displayed in the step.

In the left column "Available attributes" all attributes of the selected
target type are displayed. Attributes in the right column "Displayed
attributes" are displayed in the step. To add or remove the attributes
of the input mask, proceed as follows:

**Move attributes between columns:** Click on the icons or .

**Add text between displayed attributes:** Click in the lower part of
the left column "Available layout elements" next to "Text" on .

**Add separator between attributes:** Click in the lower part of the
left column "Available layout elements" next to "Separator".

**Change the order of attributes or layout elements:** Click an
attribute or layout element in the "Attributes displayed" column on the
right and drag and drop it into the desired position.

### "Table" step type

The "Table" step type provides the possibility to display a table of
search results in the step. Configure the table using the options in the
"Step Editor".

To edit a table, perform the following steps:

1.  To the right of the "Search" field click .

2.  Limit the search using the displayed parameters.

3.  To remove or add columns, click next to the "Columns" field.

4.  In the "Table result mode" field, select the desired mode of the
    displayed table.

5.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} You have configured a step of the type
    "Table".

### "Script" step type

::: {.note .note-hint .with-title}
**Low-Code required** Steps of this type must be configured with
Low-Code. Further information can be found in the corresponding section
of the [Low-Code
documentation.](https://docs.cplace.io/lowcode/features/forms-wizard/script-step/){target="_blank"
rel="noopener"}
:::

The "Script" step type triggers the script specified in the "Step
Editor" when the step is reached.

### "Info" step type

The "Info" step type gives the user a text when the step is reached. The
text can either be defined in the "Step Editor" or created dynamically
via a script. Low-Code is required to use a script.

### "Decision" step type

The "Decision" step type gives the user the option to choose between two
different options.

To edit a "Decision" step type, perform the following steps:

1.  In the editor, add a text to be displayed above the two selection
    options.

2.  Click in the "Option 1 Step" field and select an option.

3.  Click in the "Option 1 Button Label" fields and enter a text for the
    button label.

4.  Click in the "Option 2 Step" field and select an option.

5.  Click in the "Option 2 Button Label" fields and enter a text for the
    button label.

6.  Click the **\[Save\]** button.

    []{.fas .fa-check-square} You have edited a step of the type
    "Decision".

## Configure the wizard flow

When you have created all the necessary steps for the wizard, edit the
sequence of steps so that these are performed in the correct order. To
edit the flow of the wizard, perform the following steps:

1.  Open the workspace settings.

2.  In the context menu, click "Types".

3.  Click the "Wizard" type.

4.  Click the wizard whose sequence you want to edit.

5.  In the "Start step" field of the "Attribute" window, select the
    first step of the wizard.

6.  In the "End Step" field of the "Attribute" window, select the last
    step of the wizard.

7.  In the "Step Manager" window, click the step you want to edit.

8.  Select the possible next steps in the "Possible next steps" field of
    the "Attribute" window.

9.  In the "Wizard Analysis" window, check if all steps are edited
    correctly.

    []{.fas .fa-check-square} You have configured a wizard.

## Activating a wizard

Before a wizard can trigger, you must activate it. To activate a wizard,
perform the following steps:

::: {.note .note-prerequisite .with-title}
A wizard can be activated only if all the requirements in the "Wizard
Analysis" window are met.
:::

1.  Open the workspace settings.

2.  In the context menu, click "Types".

3.  Click the "Wizard" type.

4.  Click the wizard you want to activate.

5.  In the "Wizard Activation" window, click the **\[Activate\]**
    button.

    []{.fas .fa-check-square} You have activated a wizard.

## Wizard deactivation

To prevent a wizard from triggering, you must disable it. To deactivate
a wizard, perform the following steps:

1.  Open the workspace settings.

2.  In the context menu, click "Types".

3.  Click the "Wizard" type.

4.  Click the wizard you want to deactivate.

5.  Click the **\[Deactivate\]** button in the "Wizard Activation"
    window.

    []{.fas .fa-check-square} You have deactivated the wizard.

## Making the Wizard available externally

A wizard can be configured in such a way that it can be called up by
users outside cplace. To enable this, proceed as follows:

::: {.note .note-prerequisite .with-title}
**Requirements for the external provision of the wizard**

- Anonymous access must be allowed in the server configuration, see
  configuration option
  [cplace.security.general.enable-anonymous-access](https://docs.cplace.io/ops/configuration/reference/#cplace.security.general.enable-anonymous-access){target="_blank"
  rel="noopener"} in the Operations Manual.
:::

1.  Create a separate user who has access to all the data required for
    the wizard.

::: {.note .note-info .with-title}
**Separate, technical user for external access**

The technical user serves as a proxy for actual external users.
:::

2.  Enter the created user in the "External access user" field in the
    configuration of the wizard.

3.  Activate the "external Wizard" checkbox in the configuration of the
    wizard.

4.  In the configuration of the wizard, click the icon next to the
    "external wizard" checkbox.

    []{.fas .fa-check-square} The wizard for external access opens in
    the browser window. You can copy the URL from the address bar of the
    browser to make the wizard available to external users via this URL.
:::::::::::
