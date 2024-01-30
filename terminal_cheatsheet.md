# Terminal Commands - Cheat Sheet

---

</br>

## BASIC COMMANDS

### oh-my-zsh

'oh-my-zsh' has been installed for terminal. The package comes with many features which help streamline usage.

Normally, when changing directory, it's necessary to type

`cd "directoryName"`

When using 'oh-my-zsh' - `cd` can be omitted.

`cd -` is the command for returning to the last directory location.

## </br>

### tab key

The tab key can be used to autocomplete various commands in the terminal. If I write the following code then press TAB, it would autocomplete (so long as the instance already exists).

```
cd Doc (press TAB)

cd Document/
```

When multiple directories exist with `Doc` affixed, i.e. `Doc01`, `Doc02`, and `Doc03`, terminal will autocomplete to `Doc0` and present the options that exist in the directory.

## </br>

### pwd

```
cd Documents/

cd bnta_work/

pwd

~ Users/user/Documents/bnta_work
```

`pwd` is used to print the working directory. The command displays the complete path.

## </br>

### ls

`ls` is used to list the files or directories in the current location

`ls -l` is used to display a more detailed view

`ls -a` will show all files, including hidden files

Flags, e.g. `-a`, can also be chained, yeilding a combination of results.

## </br>

### creating & deleting instances

`mkdir` is short for make directory

`touch` is used ti create new files. If not followed by a file extension - a directory will be made instead.

`rm` can be used to remove entire directories or files if explicitly specified. To force you can append the `-f` to the command.

## </br>

### manipulating files

Files can be copied, moved or renamed from the terminal. The `..` command points to the directory appove.

```
# renaming files
mv file.txt file2.txt

# relocating files
mv file.txt ..

# copying files
cp file.txt ..
```

</br>
***
</br>
## GIT COMMANDS

`.git` hidden in nature due to the full stop prefix

`git init` creates a new git folder, storing git related information

`git add -all` adds all changes main to a project to the git records

`git commit -m "first commit"` commits the changes ready for pushing to github

`gst` & `git status` provides updates on VC status

`git push` sends the version to the git hub repo as git is local

`git log` provides access to version control history

```
git remote add origin git@github.com:<your_github_name>/<your_repo>.git
git branch -M main
git push -u origin main
```

The above commands are used to push a local git store to the git hub respository.
