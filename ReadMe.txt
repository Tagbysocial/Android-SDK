This archive contains the Tag’By Demo Application
sources, i.e. Android Eclipse projects:
 - com.tagby.sdk.resources     : the resources required by the Tag’By SDK
 - com.tagby.sdk.simpleapp     : the basic components (like sharing screens) used
                                 by the most of Tag’By apps
 - it.sephiroth.android.library: helper library that delivers some Android controls
 - TagBy DemoApp               : your demo application code which consist of four items:
     - MyDocument.java         : defines the contents of the offers designed for and
                                 supported by your demo application
     - MyApplication.java      : application code, its main job is to instantiate offers
                                 configuration
     - MainActivity.java       : represents demo application workflow
     - MyMainFragment.java     : represents demo application main screen

Please note, that the demo application reuses most of its UI components 
from the com.tagby.sdk.simpleapp. If you need to change or customise its parts
you can do it in many ways:
 - customising resources found in the projects
 - changing part or all the sharing screens.

You should avoid making any changes to the following projects:
 - com.tagby.sdk.resources
 - com.tagby.sdk.simpleapp.
in order to have an easy way to update your existing project to the newest Tag’By SDK
by simply replacing these projects with newer versions. Use resources in your 
TagBy DemoApp in order to replace / change anything found in these projects.

In order to create this demo app you need to follow the steps:
 01. setup you Android Eclipse development environment based on the instructions
     provided by Google
 02. extract TagBy Demo App_1.0.zip
 03. open Eclipse
 04. select File -> Import from the menu
 05. select General -> Existing projects into Workspace
 06. click Next
 07. make sure “Select archive file” is checked and click “Browse…” next to it 
 08. navigate to the folder containing the extracted files
 09. select TagBy Demo App Eclipse Sources.zip
 10. select all the projects from the archive and import it
