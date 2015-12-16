# FixProjPaths
Small command line program to change all paths in .project files to the correct, current path

If you clone an Eclipse project from GitHub that uses a repo path different from your repo path, then you have to replace the path in the Eclipse .project file before Import-ing it into Eclipse. This searches for all .project files under the specified directory and corrects them. The .project file does not support relative path names.
