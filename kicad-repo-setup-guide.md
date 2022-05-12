# How to set up a new KiCad project/repo


### Step 1: Creating the repository
Download [GitHub Desktop](https://desktop.github.com/) and [KiCad 6.0](https://www.kicad.org/) if not already downloaded.
  
1. Open GitHub Desktop
2. Click 'File - New Repository'
3. Name it accordingly (the Allen Synthesis standard naming uses all lowercase and separates words with hyphens, e.g. new-project-example)
4. Add a relevant description
5. Choose a local path where you store all of your projects. I use a single folder which contains all my repositories created using this method.
6. Check 'Initialize this repository with a README'
7. Choose a license. All Allen Synthesis repositories use 'Creative Commons Zero v1.0 Universal' for the actual documentation.
8. Click 'Create repository'

### Step 2: Creating the KiCad project
#### If not already completed, install the Allen Synthesis eurorack template for KiCad:
1. Download [eurorack.zip](eurorack.zip) from this repository, and then move it to 'Documents/KiCad/6.0/template'.
2. Right click on the .zip and click 'Extract All'.
3. Delete the 'eurorack' from the end of the filepath so it ends in '\template\'.

#### Creating a new project using the eurorack template
1. Open KiCad 6
2. Click 'File - New Project from Template'
3. Click the 'User Templates' tab
4. Click 'Eurorack Template'
5. Click 'OK'
6. Navigate inside the folder that you created in step 1, and name your KiCad project the same as the repository name with 'kicad' on the end. In the example used above, the folder would be named 'new-project-example-kicad'
7. Press Enter to create the project

### Step 3: Publishing the repository
1. Go back to GitHub Desktop
2. In the 'Summary (required)' field in the bottom left, name your changes 'Create KiCad project'
3. Click 'Commit to main'
4. Click 'Publish repository' in the top right
5. Click 'Publish repository' in the window that pops up


You can now make any changes you like on your computer, either changes to the KiCad project or adding new files to the folder, and you can just fetch origin, commit the changes, and then 'Push Origin' which is the same as 'Publish repository' but for changes after the very first commit.  

The best part (in my opinion) about this process, is that anyone can clone (download) your repository, with the knowledge that the KiCad file structure will work perfectly, as it's identical to your project.
