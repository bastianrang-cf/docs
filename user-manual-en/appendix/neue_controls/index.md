:::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} /
[Appendix](/user-manual-en/appendix/){.docs-subtopic-page} / [Status
overview of the migration to the new frontend]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/appendix/neue_controls.md){.edit-btn
.float-end}
:::

# Status overview of the migration to the new frontend

The controls in cplace (cplace Controls) will be successively modernized
by migrating them to the new frontend. cplace Controls allow you to view
and edit data in cplace. The new controls offer a number of improvements
compared to the old controls, such as editing data during the display or
intuitive and more user-friendly operation. The new controls must be
activated for some widgets, while they automatically replace the old
controls in other places. In this section you will find an overview of
the availability of the new controls.

The new controls are already fully available for the development of
custom Pro-Code solutions and make the use of legacy controls
unnecessary. In this section you will find an overview of the platform
components and widgets/plug-ins in which the new controls have already
been integrated.

::: {.note .note-note .with-title}
**Simultaneous use of new controls and legacy controls not possible**

It is not technically possible to use the legacy controls and the new
controls in the same cplace component at the same time.
:::

## Platform components

The controls for platform components are gradually migrated to the new
frontend and thus automatically replaced by the new controls.

  Platform component     Migration status
  ---------------------- ------------------------------
  Login                  Migrated since release 24.2
  Page creation dialog   Planned
  System Information     Migrated since release 24.2
  User profile page      Migrated since release 24.2
  Group profile page     Migrated since release 24.2
  Data Privacy           Migrated since release 24.1
  Workspace overview     Planned

## Widgets and Plug-Ins

The new controls must be activated for widgets and plug-ins via the
respective widget settings. To do this, activate the "Enable new user
interface" checkbox in the widget settings. When you use the new
controls for the "Grouped Attributes of a Page" or "Table" widgets, no
legacy controls can be displayed in these widgets. In this case, an
error message with the affected legacy controls is displayed in the
table.

  Widget/Plug-In                           Legacy       Frontend 2.0
  ---------------------------------------- ------------ -------------------------------
  "Grouped Attributes of a Page" widget    Available    Available since release 23.4
  "Grouped Attributes of a Table" widget   Available    Available since release 24.1
  "Attributes" widget                      Available    Planned
  "Tags" widget                            Available    Planned
  "Text" widget                            Available    Available since release 25.1
  Attribute Dependencies                   Available    Planned
  Forms Wizard App                         Available    Planned
  Forms Wizard Execution App               Available    Planned
  Workflow Transitions                     Available    Available since release 24.4
  Office Reports                           Available    Planned
  Report Generation                        Available    Available since release 24.4
  Board                                    Available    Planned

::: {.note .note-info .with-title}
**Overview of new controls**

An overview of the release status of the new controls can be found in
the section ["Overview of new
Controls"](/frontend-applications/guides/controls/#overview-of-new-controls)
in the frontend documentation.
:::
::::::
