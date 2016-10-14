# Zenodo and DOIs

Zenodo is a repository for storing scientific documents, hosted at CERN.
It’s a great place to deposit your work as, not only will you be guaranteed (in as much as one can guarantee these things) that your documents will always be available for whoever wants them, you will also get a unique DOI (a digital object identifier) that will always point to your document no matter how URLs change in the future.

Zenodo also comes with out-of-the-box integration with GitHub.
This integration is mainly aimed at making it easy for people to cite code, by taking software releases from GitHub as they are produced and automatically assigning them DOIs.
But you can also use this integration to link your raw files with your finished product.
Once you are ready with your document, just export it from Authorea as a PDF (or export it to $\LaTeX$ and tweak it to your heart’s content before saving it as a PDF), and publish a new release on GitHub that includes your PDF as an attachment.
If you have activated your GitHub&harr;Zenodo integration and have enabled the sync for the repository in question, you should automatically have a new entry on Zenodo.
Change the document type and fill in all the metadata, and you’re good to go!
Don’t forget to include a Zenodo badge with the DOI in your `README` file.
