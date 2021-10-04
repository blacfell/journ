% JOURN(1)
% kitty fangz
% October 2021

# NAME

journ - do a journal. in The Shell

# SYNOPSIS

**journ** [*OPTION... *] [**-e** *editor*] [**-m** *message*]

# DESCRIPTION

**journ** is a journal keeper written in bash. By default it opens a Markdown file named with the date in $EDITOR.

By default, **journ** uses the folder "$HOME/.journ". To change the folder used, set the environment variable $JOURN\_DIR.

# OPTIONS

**-e**
:	Use an editor other than the one in the shell variable $EDITOR.

**-m**
:	Provide text to write into the file instead of opening an editor, like git commit -m.

**-s**
:	Read from stdin instead of opening the editor.

**-t**
:	Use a normal text file instead of a Markdown file.
