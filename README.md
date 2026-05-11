# analysis-r-template

(Adapted from the [research-r-template](https://github.com/GlobalFishingWatch/research-r-template))

This repository is intended as an R template from which you can create a new repo
(see *Setup). This template repo is meant to:

1. Make starting a new project easier.
2. Help us to be more consistent across analysis projects.
3. Be a gentle reminder of best practices at different stages of a project.
   Haven't used the `queries/` folder yet? Perhas it's time to pull some queries
   out of those notebooks!

## How does this differ to the `research-r-template`?

This repo is intended as a simplified version of the [research-r-template](https://github.com/GlobalFishingWatch/research-r-template)
that meets the majority of needs for analysts tasked with producing a new report, 
while forgoing some features that are rarely necessary (e.g. a folder for `models/`)
or may sometimes create blockers to simple analysis tasks (many of us have lost some battles
and times to managing the `renv.lock` file). 

For analysts who would prefer to continue using the [research-r-template](https://github.com/GlobalFishingWatch/research-r-template)
and take advantage of the advanced functionalities, including `fishwatchr::make_pkg_proj()` to 
rapidly populate a new R project folder on their devices and github, then that is
absolutely fine. This repo is only intended as a simple alternative for those who wish
to use it. All of the folders included in this repo can also be found in the 
[research-r-template](https://github.com/GlobalFishingWatch/research-r-template).

## Setup

### Creating a new repo from template

1.  Create new repo with template by going to [the repo in
    GitHub](https://github.com/GlobalFishingWatch/analysis-r-template)
    and clicking the `Use this template` button. You can also use the
    GitHub command line tool,
    `gh repo create --template https://github.com/GlobalFishingWatch/research-r-template.git`
    option. More documentation on this library is available
    [here](https://cli.github.com/manual/gh_repo_create).
2.  Rename `analysis-r-template.Rproj` to your project name. The
    convention is to name it the same as your repo.
3.  Update the `README.md` to what is relevant for your project.

## Structure and descriptions

    |- README.md        <- Top-level README on how to use this repo
    |- data             <- Data files. Create subfolders as necessary.
    |- documents        <- Reference documents or draft report documents.
    |- notebooks        <- R notebooks (preferred) or quarto documents.
    |- figures          <- Maps, charts, figures etc. Create  additional subfolders as necessary.
    |- queries          <- BigQuery queries saved as .sql files. Create subfolders as necessary.
    |- .gitignore       <- Modify as necessary.
