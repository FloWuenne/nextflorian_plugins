# nextflorian_plugins
A collection of small, hacky Nextflow plugins.

## nf-workdir-sizes
This plugin is a simple Nextflow plugin that prints the size of the work directory to the log as a DEBUG statement.
To find all workdir sizes, you can simply grep for `workdirsize.WorkdirSizeObserver` in the `.nextflow.log` file.
The reported value is: taskHash,task workdir size in bytes,task workdir size in human readable format.