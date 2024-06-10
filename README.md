This repository is where people who want to contribute to Scratchapixel by writing lessons can push their files.

At least for the time being, the historical lessons are kept in a private repo. However, as Scratchapixel gains popularity and as more people realize it makes sense to have a single repository/website where content related to computer graphics programming is stored, more and more people with specific experience want to contribute by sharing their knowledge with others on Scratchapixel.

This is great because it aligns with what Scratchapixel is for and what it aims to become. However, while the project is still in its early stages and since it was initially created under the impulse of a single person, until there is significant community momentum, we will keep things separate: the historical lessons are part of a private repo that is not accessible to the public. This is the public repo to which anyone can contribute.

## Rules

While external contributions are welcome, there are certain rules and processes to follow:

- Your content will be reviewed before being published. Unfortunately, you can't see the content online until we review and publish it.
- Scratchapixel tries its best to provide the following:
  - Explain things from the ground up. Do not leave an equation unexplained.
  - Write in plain English. Don't throw an equation without explaining what it is, where it comes from, how, and why it works.
  - Provide derivations for given results when necessary.
  - Provide a C/C++ implementation of any algorithm/technique provided. No dependencies or external libraries. The file, if possible, should be a single file, easily compilable from the command line, with a checkable, if possible, visual result. Technically, the file should compile with a single command line on the terminal. Of course, system libraries can be used. For example, if you write a program that uses a Windows window, it's okay to use Windows Win32 libs. The command line used to compile the program should be displayed at the top of the program.
  - External links: can only be to websites that support a non-profit, open-source approach. Links to commercial services or products are not allowed unless justified. If we feel someone writes a lesson with the intent to redirect the reader to his/her website, it will not pass the review process. However, if you are the developer of commercial or free software and want to share your experience in a given domain, we will allow you to make a reference to your work (assuming you share knowledge with the community).

### Ownership

The name of the author will be added to the articles. Authors need to be clear on the fact that Scratchapixel aims to function as a non-profit activity but remains the sole ownership of its founder(s). While Scratchapixel is committed to never exploit the work of others commercially, external contributors need to acknowledge that Scratchapixel may receive donations to support its work, including contributions from external authors.

## Formatting

All lessons should be organized into chapters, with one file per chapter. Scratchapixel expects the lessons to be stored in Markdown format with the `.md` extension. When we build the website, we convert these MD files into `.html` pages. Note that we support most MD tags though there are some exceptions and additions:

- No table support: because they don't display well on small screens.
- We do support lists but not numbered lists. For a list, start each section with a `- `. You can have nested lists. To create a sublist, leave 2 spaces in front of the `- `.
- 0 trailing space on empty lines; otherwise, files won't convert.

### LaTeX Equations

Scratchapixel uses MathJax. Inline equations can be inserted like so `\(insert here\)`. For non-inline equations, use `$$ equation $$` (not `[ ]`).

## Contact

If you have any further questions, please get in touch with us on the [Discord server](https://discord.gg/bmWVasTduj).
