# {Repo Name}
Description of the repo.

# Setup
Working with this repo as a library or a standalone repo.

## Library
Use as a library and install as a dependency into an existing project.

```
uv add git+<full path to GitHub Repo>@<release tag>
```

```
uv add "library[option_1,option2] @ git+<full path to GitHub Repo>@<release tag>"
```

```
pip install git+<full path to GitHub Repo>@<release tag>
```

```uv add library``` installs only [project.dependencies]  
```uv add "library[phi4]"``` installs [project.dependencies] plus the phi4 optional deps  
```uv add "library[phi4,gpt_oss]"``` installs baseline plus union of both extras  
```uv add "library[all]"``` baseline plus whatever you put in all

## Repo
Run locally for development of this repo.

# Usage
...

# Notes
...
