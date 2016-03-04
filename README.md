# vimrc

Using the great services at github to store my vimrc file

## Sources

I am installing [spf13] (http://vim.spf13.com/) to start with, it is a bit much, but has served me well in the past.
Usually I would just install that and trudge along with that; now however I am going to make a concerted effort to learn vim well.

I am going to base some of my "custom" changes off of [Steve Losh's](https://www.youtube.com/watch?v=xZuy4gBghho) vimrc videos.


### Rational.

Part of the reason I am doing this is that I am busy developing a terminal/console based IDE for my place of employment.
I am going to be using tmux to have multiplexed terminals, but have to have a solid vim instance. Anyone who works at a big corporate company
that does development will know that most of the people, specially your architects, aka: old timers use vim and only vim. Ofcourse there is the
odd emacs psychopath, but lets not judge.

- AvS : March 3, 2016 @ 02h18

## Things to keep in mind

Since I am using [spf13] (http://vim.spf13.com/) as a base, some of my content may not be completely compatible with just dumping it into a ~/.vimrc file,
it should not be that different, but just something to think about.

Most of my changes will be in ~/.vimrc.local :-> This file should be added in the commit that added "Things to keep in mind".

### spf13 bootstrap

I will additionally add a bootstrap.sh script that will stage all the files to your local home directly. I would recomment to
also use [spf13], (http://vim.spf13.com/) so will add a command line option to install that for you.

- AvS : March 3, 2016 @ 02h35

### README tracking

In the sub directory history, there is a README.md, where I will keep track of changes made. This may not be 100% accurate, but will be good enough.
