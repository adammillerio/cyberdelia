---
{"dg-publish":true,"dg-path":"obsidian/style.md","permalink":"/obsidian/style/"}
---

*A one or two line overview of what the document is about and what it is meant for.*
# Main Section
A main section that will contain a general grouping of ideas or procedures together for easy location via Table of Contents.
## Main Section Segment
A segment of the main section, going over some portion of the overall procedure or idea that is self contained in terms of it's domain, but may be composed of multiple technologies or tools, etc.
### Technology/Idea/Tool Specific Sub-Section
A technology or domain specific sub-section, going over the specific information related to a given tool or technology that is relevant to this segment of the document. There may even be multiple alternative tools or means of achieving what is needed for this section segment. For example, you may have a Segment "Configuring X" and then two specific sub-sections that cover doing it via the GUI and CLI.

---
# Other Notes
## Naming
The name of a page needs to be uniquely identifiable in a given path. For example, the name `Setup Spec` is frequently repeated in places like:
```
/Hardware/amana/Setup Spec
/Hardware/izalith/Setup Spec
```

This is fine, since you can just type "amana Setup Spec" and Cmd+P will know to show you that.

One place where you need to be cognizant of this is if you want just like a "Landing Page" for your folder. You should make that page just be named the exact same as the folder. For example:
```
Projects/Personal Writing Website
Projects/Personal Writing Website/Personal Writing Website.md
```

This is because Cmd+P does not show folders, so if you named it something like `Overview`, you would have to type `Personal Writing Website Overview`, which is redundant.
## Writing Shell Commands
The format for a shell command is the following:
```bash
/path/to/working/dir>
echo command
```

ie:
```bash
~/aesource>
red utils ipython
```

If it is a machine other than the local machine, add an @ with some relevant information about the location it is being ran:
```bash
~/aesource@ravenholm>
red utils ipython
```

## Line Breaks
Line breaks should only be manually placed when they are breaking up multiple paragraphs in a single section.

Note how a line break is added between these two paragraphs, but not between this paragraph and the next section.
## Next Section
Foobar

For code, there should be no line break before, and one line break after the code like so:
```
This is my code block.
```

Anything that is intended to be ran or copied should be in a 3 backtick code block, not an inline single backtick code block. Even if it is a single line it's much easier to copy when it is in a block. Single backtick code blocks are best for things like method names or file paths when writing docs.
## Bulleted Lists
* A sentence at the end of a bulleted list line should never have a period
* A line with multiple sentences can use periods of course. However, the last line should always not have one