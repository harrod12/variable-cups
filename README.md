# Variable cups

A free, single page tool for teaching and practicing variable assignment in AP Computer Science Principles pseudocode.

**Explore** mode runs statements one at a time with cups and sticky notes. The old note is thrown away, a copy of the new value goes in, and a trace table fills in as you step.

**Practice** mode generates problems for students to trace by hand. It checks each cell and names the likely misconception, such as treating a copy as a link or expecting a swap.

Everything runs in the browser. Nothing is sent, saved, or tracked, and no account is needed.

## Use it

Open `index.html` in any modern browser. There is nothing to install.

## Put it online with GitHub Pages

1. Create a new repository on GitHub and upload `index.html`, `README.md`, and `LICENSE`.
2. Open the repository's Settings, choose Pages, and set the source to your main branch and the root folder.
3. After a minute, the tool is live at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## For teachers

* Ask students to predict final values on paper, then check in Explore.
* In Practice, share the problem code so a whole class works the same program.
* The "This session" panel shows which error patterns came up in that browser session. It is not saved.
* Pair the tool with real cups and sticky notes. The physical model builds understanding, and the tool gives students more practice.

## Standards alignment

AP Computer Science Principles Big Idea 3, learning objective AAP-1.B (determine the value of a variable as a result of an assignment) and essential knowledge AAP-1.B.3 (the value stored in a variable is the most recent value assigned). Confirm the numbering against the current Course and Exam Description.

## Supported statements

One assignment per line. Use `←` or `<-` for assignment. Expressions can use numbers, text in quotes, other variables, `+`, `-`, `*`, `/`, `MOD`, and parentheses. Up to 14 statements and 6 variables.

## Notes

This is an independent teaching tool. It is not affiliated with or endorsed by College Board or Code.org. AP is a registered trademark of College Board.

## License

MIT. See `LICENSE`.
