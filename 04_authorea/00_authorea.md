# Authorea and exporting

Authorea calls itself “Google Docs for Academics”.
Built on top of git, it is a web-based application for authoring academic documents and exporting them into several styles in a few different formats.
However, the web GUI can be a bit buggy and can sometimes cause problems when working collaboratively on a document.
It also doesn’t have branches and I have not really tried merging anyone else’s changes into my document.
While it has a comments option, it lacks an issue tracker, which can be very useful for managing large authoring projects on GitHub.
I therefore use Authorea mainly as a web-display for my files, choosing to work offline in markdown.
I also using Authorea to export the content into `.docx` in order to circulate it to my supervisors for comments.

**Note**: You don’t need Authorea just to export your files.
In fact, the export option can cause some problems depending on the chosen style.
If you want to use your own templates or CSS or what have you, you can also consider using [`pandoc`](http://pandoc.org/) with this shell script: [https://github.com/lauritzsh/pandoc-markdown-template](https://github.com/lauritzsh/pandoc-markdown-template).
