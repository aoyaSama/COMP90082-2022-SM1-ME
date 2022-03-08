# COMP90082 Missing Mezuzot (code: ME) Project

The Missing Mezuzot of Zdunska Wola is an interactive exhibition/installation of 3,000 mezuzot created as a metaphor evoking the memory of Jewish families living in Poland before 1939.

This project will extend the existing software so it is extensible, maintainable, and can be deployed in museums around the world.

## Table of contents
- [COMP90082 Missing Mezuzot (code: ME) Project](#comp90082-missing-mezuzot-code-me-project)
  - [Table of contents](#table-of-contents)
  - [Project Information](#project-information)
  - [Requirement](#requirement)
  - [Solution components](#solution-components)
    - [Architecture:](#architecture)
  - [Contributing](#contributing)
    - [Gitflow workflow](#gitflow-workflow)
      - [Publishing changes](#publishing-changes)
      - [Managing conflicts](#managing-conflicts)
  - [Authors](#authors)

## Project Information

The Missing Mezuzot of Zdunska Wola is an interactive exhibition/installation of 3,000 mezuzot created as a metaphor evoking the memory of Jewish families living in Poland before 1939.

This project will extend the existing software so it is extensible, maintainable, and can be deployed in museums around the world.

## Requirement
| Requirement | |
|-|-

## Solution components

The solution consists in the following containers:

1. `1`
2. `2nd`
3. `third`

### Architecture:



## Contributing

Code should adhere to the [Android Style Guide](https://developer.android.com/kotlin/style-guide)
wherever possible. All code should have docstrings.

The `app` folder is where the raw code of project stored in.

The `app/java` folder is the location for all substantive code. Runnable
code should have a debug configuration for easy use and debugging.

The `app/res` folder is the location for all UI resource. 
All newly added resources should not violate any copyright infringement laws.

### Gitflow workflow
We recommend a Gitflow workflow as detailed here:
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

#### Publishing changes
`git push origin main`

#### Managing conflicts
If your local history has diverged from the central repository, this is the result of changes
made by another person on the same files you've made changes on.
Git will refuse the request with a rather verbose error message:

`error: failed to push some refs to '/path/to/repo.git' hint: Updates were rejected because the tip of your current branch is behind hint: its remote counterpart. Merge the remote changes (e.g. 'git pull') hint: before pushing again. hint: See the 'Note about fast-forwards' in 'git push --help' for details.`

To proceed you need to pull everyone else's updates into your local
repository and resolve the diverging history:
`git pull --rebase origin main`

If you are working on unrelated features, it’s unlikely that the
rebasing process will generate conflicts. But if it does, Git will
pause the rebase at the current commit and output the following message,
along with some relevant instructions:

`CONFLICT (content): Merge conflict in [XXXX]`

Now run a git status to see where the problem is. Conflicted files will
appear in the Unmerged paths section:

`# Unmerged paths: # (use "git reset HEAD ..." to unstage) # (use "git add/rm ..." as appropriate to mark resolution) # # both modified: `

Edit the file(s) to your liking. Once you're happy with the result, you
can stage the file(s) in the usual fashion and let git rebase do the rest:

`git add git rebase --continue`

Git will move on to the next commit and repeat the process for any other
commits that generate conflicts.

If you get to this point and realize and you have no idea what’s going
on, don’t panic. Just execute the following command and you’ll be
right back to where you started:

`git rebase --abort`

## Authors

* **Qunzhi Wang 900884**@frankie-adam - [University of Melbourne](https://www.unimelb.edu.au/)
* **Hoang Viet Mai 813361**@hmai2139 - [University of Melbourne](https://www.unimelb.edu.au/)
* **Sriram Kumar Rao 1110639**@sriram-kalekar - [University of Melbourne](https://www.unimelb.edu.au/)
* **Daniel Coleman 994887**@dccol - [University of Melbourne](https://www.unimelb.edu.au/)
* **Takemitsu Yamanaka 757038**@aoyaSama - [University of Melbourne](https://www.unimelb.edu.au/)