#InterMapper MIB Viewer Probes

The MIB Viewer probe builder is a web page tool that creates an InterMapper probe automatically from a MIB. You can see an example of a MIB Viewer probe at: http://forums.intermapper.com/viewtopic.php?t=1871 This is the resulting status window. ![Status Window showing the MIB-2 MIB Viewer Probe](http://download.dartware.com/images/MIBViewer-rfc1213.png)

We use the MIB Viewer page to create a probe quickly when a customer sends us a MIB file. You can check out the MIB Viewer tool at: http://bit.ly/InterMapperMIBViewer That page also has instructions for downloading the tool and running it on your own system. 

## The MIB Viewer Probe Collection

We have begun to collect a number of probes from MIBs that we use or from customer-supplied MIBs. We plan to make them available as part of an upcoming release of InterMapper, but you can get a preview of them now. 

The collection of MIB Viewer probes is available at this URL: https://github.com/richb-intermapper/MIBViewerProbes

It is a repository on Github.com. You can either download all the files as a Zip archive, or use a **git** program to retrieve the files. (See "About Git" below for more information.)

To use the files, follow these steps:

1. Download the zip file and unzip it, or use git to retrieve the files to your local disk.
2. Copy all the files from the MIBs directory into the InterMapper Settings : MIB Files directory on your InterMapper server.
3. Copy all the files from the Probes directory into the InterMapper Settings : Probes directory.
4. Stop and restart the InterMapper server.
5. The probes will be available in the Set Probe… window, in the MIB Viewers category.

If you have probes that you would like added to this collection, send them to us at support@intermapper.com.

##About Git

*git* is a distributed source control system. It allows groups of people to maintain and update repositories of text, such as source files for programs, documentation, or as with this repository, git can handle special purpose files such as MIBs and probes for InterMapper.

Although you could download a .zip archive of these files from this site (by clicking the button at the top of the page), it's better use a git client. Here's why:

* A git *pull* command retrieves all the files from the repository to create an identical copy on your local disk. There's no fumbling with various zip utilities. You can save the files in any directory you desire.
* git also makes it easy to get updates when the collection is expanded or updated. git automatically tracks all the changes to the repository, and can let you know when there are updates. A subsequent *pull* command retrieves only the updated files from the other repository, leaving the others untouched.
* If the repository maintainer allows it, you can make  modifications to your local files and *push* them back into the repository.

All operating systems have a git program that runs from the command line. Atlassian offers an excellent (and free) graphical client called SourceTree both for Windows and MacOSX. You can get them at: http://www.atlassian.com/software/sourcetree/overview
