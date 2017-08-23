# emoflon-ibex-democles
Democles-specific component for emoflon-ibex

## Installation
0. Install GraphViz
1. Get current version of the Eclipse Modeling Tools:  http://www.eclipse.org/downloads/packages/eclipse-modeling-tools/neon3
2. Install Ibex from this update site: https://emoflon.github.io/emoflon-ibex-democles/  Make sure you enable "contact all update sites" in the update manager so all dependencies are automatically installed.
3. From this repository, import the ```org.emoflon.ibex.tgg.workspace_configuration``` project into your workspace.  Let's refer to this project as our workspace-config from now on.
4. Check encoding for Xtend Files
  - In Eclipse: Go to ```Window->Preferences->General->Workspace```
  - Change the text file encoding to 'Other: UTF-8'
5. Set up your developer workspace
  - Choose the PSF file ```devProjectSet.psf``` in the workspace-config, right-click and select ```Import Project Set...```.
6. Execute MWE2
  - Open project ```org.moflon.ibex.tgg.editor```
  - Go to package ```src/org.moflon.tgg.mosl```
  - Right-click on GenerateTGG.mwe2
  - Press ```Run As -> MWE2 Workflow```
7. Set up your runtime and test workspaces by starting a runtime Eclipse workspace from your dev workspace, and importing the other PSF files in the workspace-config.  Run the JUnit tests to ensure that all is well (everything should be green).
