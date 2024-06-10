This repository is where people that want to contribute to scratchapixel by writing lessons can push their files.

At least for the time being, the historical lessons are kept in a private repo. Though as Scratchapixel is gaining popularity and as more and more people understand it makes sense to have a single repositiry / website where content realted to computer graphics programming is being store, more and more people with specific experience want to contribute by sharing their knowledge with others on Scratchapixel.

THis is great because this is essentially waht Scratchapixel is for and what it aims to become. Though while still fragile and as this was initially created under the impulson of a single person, until there's a real momomentim un terms of commuynity contributions, we will for the time being keep things speperate: the history lessons are part of a priovate repo that is not accessible to the puiblic. THis is the public repo to which anybody can contribute.

## Rules

xx

## Formatting

All lessons should be organized in chapters where there should be 1 file per chapter. Scratchapixel expects the lessons to be stored in Markdown format and have extension `.md`. When we build the website, we convert these MD files into `.html` pages. Note that we support most MD tags though they are some exceptions and some additions:

- No table support: because they don't display well on small screens
- We do support list but no numbered list. For a list start each section with a `- `. You can have nested lists. To do so, leave 2 spaces in front of the `- ` to create a sublist.
- 0 trailing space on empty lines otherwise files won't convert.

### Latex Equations

Scratchapixel uses Mathjax. Inlines equations can be inserted like so `\(insert here\)`. For non-inlined equations using `$$ equation $$` (`[ ]` is not supported).


## File Structure and Organization

If you want to create a new lesson:

- you need to create a folder under the lesson folder, whose name if possible is self-explanatory while not being too long. E.g. "intro-to-quaternion". This needs to be lower case, with words seperated with a `-`. So: `/lessons/intro-to-quaternion`.
- All images needs to be stored in the images folder, in a folder having the same name than the one you used for the lesson content itself. So: `/images/intro-to-quaternion`. There you can store you iamges in the .png, jpg, gif, etc. format. If possible follow a simple rule which is to prepend all your image files with some prefix that relates to the lesson. For example `intro-quat-rotation-2d.png`, `intro-quat-rotation-3d.png`, etc.


