# Code Style

## Indentation

Size 2 tabs. Spaces v Tabs is infamous, but after using both extensively I always come back to tabs for my own projects.

Pros:
- Semantic. Tabs are designed for indentation. It makes sense to let someone change the size they want to view a tab as.
- Searchable. Multiple consecutive spaces are almost always style errors in my code. I want to be able to search for these project-wide instantly.
- Clarity. I style invisible characters as visible when selected in my editor. It's much easier to read the indentation number from tabs than a dot for every space.
- Selecting indentation points. Although many editors offer some support for automatically grouping spaces for selecting/cursor insertion, it almost never does exactly what I expect, and is far from a universal feature. Tabs just work, always.

Cons:
- Standards. Most people in JS-land seem to use spaces. Not much of a reason for personal projects.

## Comments

Comments are essentially warnings in my code, as otherwise I find them to be too distracting when interspersed. I prefer external documentation, although I probably don't do that enough either. One of shortcomings in the code I write.

//TODO Anything that needs fixing/implementing. _Should_ be accompanied by 🚧 when commited.

//SAMPLE Code I want to easily search for and toggle for testing purposes. Related lines should always be commented out when committed.

## Miscellaneous

- Never use semicolons
- Always bracket around `if`/`for`/`while`/etc.
- Never manually break up lines of code. If it's too long to understand on one line it's a code smell that should be refactored.
- Similarly, never put multiple statements on the same line. (Excepting pesky old-style for-loops, which fortunately were removed entirely from Swift.)
- Always use a trailing comma for multi-line array/object declarations. Why? It ensures clean git commits. (I really don't understand how this isn't wider practice. Do people not look at git diffs?) JSON drives me mad because this is invalid syntax according to the spec (I'm looking at you, `package.json`).
- Never use `else` after exiting control flow (`return`/`break`/`continue`) in an initial `if` statement. Redundancy like this makes me think the code isn't doing what it's intended.
- Explicitly reference globals wherever possible (i.e. `window.alert`)

## [VSCode](VSCode/README.md)
