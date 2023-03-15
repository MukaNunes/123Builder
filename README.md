# **<font color="#FF5920">1</font><font color="#FFB600">2</font><font color="#00AD3A">3</font>** Builder ✈
*Project builder for packages based on [@Plataforma13/Alkhema-SDK](https://github.com/Plataforma13/Alkhema-SDK)*

### Main guidelines:
- Keep your upstream pointing to the Platform 13 repositories on your remotes before using this script.
- If in doubt, read the development environment preparation documentation on our confluence page: [Prepare Environment](https://grupo123.atlassian.net/wiki/spaces/INI/pages/45382467585/Prepare+Environment).
- Before running, make sure that the constant PROJECTS_FOLDER value at the beginning of the script is pointing to your project folder.
- If you don't know how to get the path of your project folder, copy the return of the following commands:

``` bash
cd your/projects/folder
echo "$PWD"
```

### Usage:
``` bash
./123builder **-b** "branch-name" **-f** **-h**
```

- **-b** *Branch*: Git branch to build. (Will use the main branch if the informed branch does'nt exists).
- **-f** *Force*: *(Optional)* Ignores the hash check and forces the build.
- **-h** *Help*: *(Optional)* Show this help screen.