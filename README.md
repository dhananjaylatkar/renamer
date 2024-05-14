# renamer

Simple CLI media rename utility

## Installation

Clone repo and copy `renamer` script in your path.

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
$ renamer tv <dest_dir> <src_file1> <src_file2> <src_dir1> ...
```
