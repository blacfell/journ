% JOURN(1)
% kitty fangz
% October 2021

# NAME

journ - do a journal. in The Shell

# SYNOPSIS

**journ** [**-t**] [**-e** *editor*]

# DESCRIPTION

**journ** is a journal keeper written in bash. By default it opens a Markdown file named with the date in $EDITOR.

By default, **journ** uses the folder "$HOME/.journ". To change the folder used, set the environment variable $JOURN\_DIR.

# OPTIONS

**-e**
:	Use an editor other than the one in the shell variable $EDITOR.

**-t**
:	Use a normal text file instead of a Markdown file.
