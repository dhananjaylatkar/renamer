# renamer

Simple CLI media rename utility

## Installation

Clone repo and copy `renamer` script in your path.

> For music rename it needs [mutagen](https://pypi.org/project/mutagen/) installed system wide.
>
> python -m pip install mutagen
>
> _OR_
>
> sudo pacman -S python-mutagen

```shell
$ git clone https://github.com/dhananjaylatkar/renamer.git
$ mkdir -p ${HOME}/.local/bin
$ echo "export PATH=${HOME}/.local/bin:${PATH}" > ~/.zshrc && source ~/.zshrc
$ echo "export PATH=${HOME}/.local/bin:${PATH}" > ~/.bashrc && source ~/.bashrc
$ ln -sf ${PWD}/renamer/renamer ${HOME}/.local/bin/renamer
```

## Usage

```shell
$ export TMDB_API_KEY=<your_key>

# rename tv shows
$ renamer tv <dest_dir> <src_file1> <src_file2> <src_dir1> ...

# rename movies
$ renamer mov <dest_dir> <src_file1> <src_file2> <src_dir1> ...

# rename music
$ renamer music <dest_dir> <src_file1> <src_file2> <src_dir1> ...
```
