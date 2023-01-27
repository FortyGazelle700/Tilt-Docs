---
order: 4
icon: file-directory
label: "Setting up the Project"
---

# Setting up the Project

While it's not required, it is highly recommended to organize your files in a structured manner for easy maintenance and management of your project.

Begin by navigating to the desired directory for your project and using the Tilt CLI command tilt init to initialize the project structure and generate a base template for your project.

```
mkdir my-tilt-project
cd my-tilt-project
tilt init
```

This will set up a basic file structure and provide you with the necessary files to start building your Tilt project.

Your project's folder structure should resemble the following:
||| Directory: my-tilt-project

!!!primary
Files / Directories that end with `(*)` may not appear because of the options you choose during initialization
!!!
!!!warning
Files starting with `.` may be hidden in your file manager

To disable this check the box in your file manager settings that says `Show Hidden Files`
!!!

- :icon-file-directory: .tilt
- :icon-file-directory: test (\*)
- :icon-file-directory: src
- :icon-file: .gitignore (\*)
- :icon-file: tilt.config.json

|||

Change directories into `src`.
