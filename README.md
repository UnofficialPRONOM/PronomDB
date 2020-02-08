# PronomDB
This repository contains the PRONOM database underlying the Droid software.  If you want to submit a new file format signature.  You are welcome to submit a new file format description.

## How to submit

If you are familliar with Github and pull requests, skip to [the quick instructions](#summary-instructions).

### Editing a subission

To make edits, you need a github account.  To make one, click "Sign Up" in the top right corner, and then come back here.  If you already have one, just log in.

Next, find the format you want to edit.  That can be done by clicking `database` above, and then the category, and then the file format you're after.   Alternatively, you can use the search box at the top, and choose "This repository".

When you have found a file to edit, click the "pencil" icon in the top right of the file.   Make any changes you need, and then, at the bottom, type a description of your changes, for example "Add history of DIB format", and click "Propose File Change".

You will be shown a summary of the change you have made, and if you're happy, click "Create pull request".  No need to fill in more details - just click "Create Pull Request" again.

Your change will now be reviewed by the National Archives team - and if alls good, they'll add it to the next release.   If they have questions, youll receive an email from Github which you can click and see their question, and make a reply or edit your submission.


### Submitting a new file format

Create a directory containing all details of the file format.  You can see an example [here](example/).

When you have all the files in the right place, log in or sign up to github, and then choose "upload files", and drag and drop the files in, and then "Propose File change" as above.


## Summary Instructions

Formats are located in directories named `database/category/formatname/`.  If a specific format has multiple distinct formats, the formatname can have a relevant version suffix - eg. MicrosoftWord2007.

Each directory should contain:

 * `signature.sig`  This contains the list of fileformat signatures
 * `description.md` A markdown document specifying metadata about the file format.  Copy [an example](example/description.md) as a starting point.
 * All other files are example files of the format.  They should have representative filenames, and example data if possible.  All submitted example files should be considered public domain.
