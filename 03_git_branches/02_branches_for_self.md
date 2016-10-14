## Using branches for oneself

Many people tend to work in `master` when they’re working alone, committing their changes and pushing to their remote(s).
I’ve found, through bad experience, that this approach can be problematic.
Sometimes, I work on different machines and end up having all kinds of merge conflicts when pulling from my origin.
So, I tend to work in a separate branch called `updates`, which I generally only keep local.
When I’m satisfied with my work, I merge the changes into `master` and then push the changes to my remote(s).
