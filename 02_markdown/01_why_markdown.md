# Why markdown

And, more importantly, **why not $LaTeX$?**

Without making this a terribly long chapter, I’ll briefly let you know why I am a markdown fan.
For one, its syntax is MUCH simpler than $LaTeX$.
Come to think of it, most of us don’t use or need everything that the latter brings.
But more importantly, $LaTeX$ syntax works perfectly within markdown documents, as you can see here, so you can use it when needed, including for inserting page breaks and whatnot.
For inline $LaTeX$, just enclose your text with `$` on both sides, like this: `$LaTeX$`.

Another feature that I find useful is that single line breaks are not treated as line breaks (unless they have two trailing spaces at the end).
This means that I can record each new sentence on a new line and have them stay part of the same paragraph.
This feature is quite useful when reviewing documents as you can refer to individual sentences and even comment on them in GitHub’s web interface.
It also avoids the need for forced linebreaks, which I, personally, hate.

Markdown is also beautifully diff-able.
It allows you to visualise all the differences between two versions of a particular file.
That, along with your commit messages, helps keep an audited record of every change you’ve made.

My way of working is to create individual directories for individual chapters with sub-chapters contained in individual files.
I also name my directories and files with numbers as prefixes for easy sorting.
