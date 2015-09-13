# github-bash
Bash commands for calling GitHub APIs from the command line

Setup - Edit github.cfg with your information

Usage
```
# Create a GitHub repo
>./githubcreate my-repo-name "Some Description"

# Add collaborator
>./githubaddcollaborator my-repo-name collaboratorusername

# Create skeleton project locally (README.md, .gitignore)
>./githubskeleton my-repo-name "Some Description"

# Init git locally and push to existing GitHub repo
>./githubpushinitial my-repo-name "Some Description"

# Use all of the above to create and push a skeleton project to GitHub
>./githubinit my-repo-name "Some Description"
```
