<!---
The page title should not go in the menu
-->
<p class="page-title"> IGV 3.0 Preview </p>


IGV 3.0 Preview is work in progress! Some features are still under development and testing has not been completed. 

We appreciate your feedback before we release. Please post bug reports and other feedback on GitHub at [https://github.com/igvteam/igv/issues](https://github.com/igvteam/igv/issues) and include *IGV 3.0 Preview* in the title.

# Download IGV 3.0 Preview

[![Windows snapshot with java](img/DownloadIGV3.0PreviewWindowsWithJava.png){width=300}](https://data.broadinstitute.org/igv/projects/downloads/snapshot/IGV_Win_snapshot-WithJava-installer.exe) 
[![Windows snapshot no java](img/DownloadIGV3.0PreviewWindowsNeedsJava17.png){width=300}](https://data.broadinstitute.org/igv/projects/downloads/snapshot/IGV_Win_snapshot-installer.exe) 
<BR>
[![Linux snapshot with Java](img/DownloadIGV3.0PreviewLinuxWithJava.png){width=300}](https://data.broadinstitute.org/igv/projects/downloads/snapshot/IGV_Linux_snapshot_WithJava.zip)
<BR>
[![Command line snapshot no java](img/DownloadIGV3.0PreviewCmdLine.png){height=80}](https://data.broadinstitute.org/igv/projects/downloads/snapshot/IGV_snapshot.zip)

!!! Note "For Mac users:"
Mac apps are not provided for the IGV 3.0 Preview build. To **run the IGV 3.0 Preview on a Mac**: 

1. Click on the *command line* version above and unzip the downloaded distribution file to a directory of your choice. You will see that several launcher scripts are provided in the distribution. The Mac version is named *igv.sh*.

2. Open a *Terminal* window and enter `<Full path to the IGV 3.0 Preview directory>/igv.sh`. For example, if the IGV 3.0 Preview files are in */Users/jane/IGV-3.0-Preview*, enter `/Users/jane/IGV-3.0-Preview/igv.sh`. Alternatively, enter `cd /Users/jane/IGV-3.0-Preview` to go to that directory, and then `./igv.sh`.

# What's in IGV 3.0 Preview

##Track hubs

UCSC track hubs in the [useOneFile](https://genome.ucsc.edu/goldenPath/help/hgTracksHelp.html#UseOneFile) format can now
be loaded directly into IGV to define a reference genome and associated tracks. Notably this includes the more than
3,600 genome assemblies and associated tracks hosted at the [UCSC GenArk](https://hgdownload.soe.ucsc.edu/hubs/) site.
See the [Reference genome](/UserGuide/reference_genome/#load-a-track-hub) section for more details on how to use a track hub for IGV's reference genome.

For more information on the GenArk resource see `Clawson, H., Lee, B.T., Raney, B.J. et al. GenArk: towards a million UCSC genome browsers. Genome Biol 24, 217 (2023).`
[https://doi.org/10.1186/s13059-023-03057-x](https://doi.org/10.1186/s13059-023-03057-x)

