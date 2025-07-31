::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Administering
cplace](/user-manual-en/cplace-administrieren/){.docs-subtopic-page} /
[Administration Dashboard]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-administrieren/administration-dashboard.md){.edit-btn
.float-end}
:::

# Administration Dashboard

The primary purpose of the Administration Dashboard is to provide
detailed (status) information relating to the instance. This section
therefore tells you what information you can find and read off in the
Administration Dashboard area. In addition the functions which can be
executed in the Administration Dashboard area are described.

## System Status

Status information of the instance is displayed on the **System status**
tab. In multi-node operation (cluster), the information of the other
cluster nodes is also displayed here in addition to the information of
the local node (server), in other words the node on which your own user
session is located.

### Cluster Status

  Information              Description
  ------------------------ ---------------------------------------------------------------------------------------------------------------------------------------------------------
  **Cluster Status**       Specifies the overall status of the cluster. The statuses of the individual servers/nodes of the cluster are used for this purpose (see *Node status*).
  **Time on local node**   Specifies the system time of the server node to which you are connected.

#### Status of the local (server) node and the remote (server) nodes

  Information                     Description
  ------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Node status**                 Specifies the status of the local node. The node status is determined on the basis of the status of the involved components, such as Elasticsearch, Hazelcast and the database.
  **Build Info**                  Information on the installed release, including the (main) release version, the build ID and the repository identifiers
  **Java Info**                   Information on the Java version being used
  **Java Threads**                Information on the number of running and started Java threads
  **Java Heap**                   Information on the Java Heap memory (currently in use, free, total available and maximum available)
  **Java Memory**                 Detailed information on the allocation of the Java memory
  **ES Cluster**                  Status of the Elasticsearch cluster
  **Database**                    Status of the database connection
  **Document space for cplace**   Information on the hard disk space being used (caused inter alia by uploaded documents, the Elasticsearch index, log files)

#### Status of the full-text index

  Information                Description
  -------------------------- ---------------------------------------------------------------------------------------------------------------------------------------
  **Elements**               Information on the multiplicity of elements in the index and the multiplicity of elements in the database
  **Elasticsearch status**   Detailed information on the status of the Elasticsearch index, comprises all nodes of the Elasticsearch cluster and all index shards.

#### Index Inconsistencies

The "Index Inconsistencies" option shows whether there are index
inconsistencies.

1.  Click the **\[Recompute visualisation\]** button to run a check for
    index inconsistencies.

[]{.fas .fa-check-square} The check is executed as a batch job.

If there are "incorrect segments" and/or index errors, you can repair
these by clicking the **\[Fix inconsistencies\]** button.

### External process-based engines

Currently only the status/the executability of PhantomJS is shown in the
"External process-based engines" option. PhantomJS is required primarily
for the CSS compiling in cplace.

If there is a problem with PhantomJS and the status is set to "NOT
READY", you can check the status/executability of PhantomJS once again
by clicking the **\[Reset\]** button.

## Plugins

In the "Plugins" tab, you can see all activated and non-activated
plugins, including the repository name, the Java artifact version, and
the frontend artifact version. In addition, all activated apps are
displayed for the activated plugins as well as the reason for the
deactivation for the deactivated plugins. To export a component list of
all installed plug-ins and the associated information as an Excel® file,
proceed as follows:

1.  In the "Plugins" tab, click the **\[Export component list\]**
    button.

[]{.fas .fa-check-square} The "Export component list" dialog is
displayed.

2.  Click the **\[OK\]** button.

[]{.fas .fa-check-square} A batch job for exporting the component list
is run.

3.  After the batch job has been successfully completed, click the
    **\[Download\]** button.

4.  To close the dialog, click the **\[OK\]** button.

[]{.fas .fa-check-square} The component list has been successfully
exported as an Excel® file.

## Libraries

::: {.note .note-hint .with-title}
**Library information visible to all users**

The library information can also be viewed by users who are not
administrators. Users without administrator permissions can call up the
overview of the libraries via the "System Information" page in the user
menu.
:::

All open source libraries contained in the installed build including the
following library information are displayed on the **Libraries** tab:

- Plugin
- Produkt
- Component
- Version
- Copyright
- Project URL
- License
- License URL
- Modified
- Download source code

You have the option of exporting a list containing all used libraries
and library information. To do this, proceed as follows:

1.  On the **Libraries** tab navigate to the **Export library
    information** button and click this.

[]{.fas .fa-check-square} The "Export library information" dialog is
displayed.

2.  Click **OK**.

[]{.fas .fa-check-square} A batch job for exporting the library
information is run.

3.  After the batch job has been completed successfully, the
    **Download** button is displayed. Click the button to download the
    library information as an Excel® file.

4.  Click **OK** to close the dialog.

[]{.fas .fa-check-square} The library information has been exported
successfully.

## (Effective) System Configuration

The effective system configuration is displayed on the **System
Configuration** tab. This encompasses both all (adjusted) settings of
the *configuration.txt* and all default settings which have not been
changed in the configuration.txt.

## Job Queue Status

All batch jobs, both those being currently run and those pending, are
shown on the **Job Queue Status** tab. For jobs relating to the current
tenant, the job class is displayed whereas jobs relating to other
tenants are displayed without details on the job class or tenant.
:::::
