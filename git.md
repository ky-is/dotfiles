# Git

I tend to make larger than average commits for my personal projects. Since I'm not worried aboout conficts, I prefer to keep the commit history reasonably terse and allow each commit to encapsulate all required functionality, without spending time rebasing later.

## Commits

I've tinkered quite a bit with commit styles. After hundreds and hundreds of the same imperative verbs "Fix ...", "Add ...", this started feeling like boilerplate. Instead I now use ~1-3 emoji at the start of each commit that describe nature of changes.

The emoji set I use is adapted from [carloscuesta/gitmoji](https://github.com/carloscuesta/gitmoji/) so at least it's familiar to other projects using emoji commit messages.

### Emoji list

Actions
- 🌱 Starting new files
- ✨ Adding a new feature
- 🐛 Fixing a bug
- 💄 Styling (CSS, IB, etc.)
- 🎨 Cleaning up code (usually no external impact)
- 🏗 Changing internal configuration
- ♻️ Refactoring (moving, splitting, renaming, etc.)
- 🗃 Changing DB/models
- 🖼 Updating static assets
- ➕/➖ Adding/removing dependencies
- ⬆️/⬇️ Up/down-grading dependencies

Rarer
- 👽 Updating code for external library changes
- 🎆 Rendering (canvas/WebGL)
- ⚖️ Balancing (tweaking parameters that change user experience)
- 📝 Writing readme/documentation
- 🔬 Improving test coverage

Modifiers
- 🚧 WIP, followup commits are required to work
- 🔰 Improving tutorial content
- ⚡️ Improving performance
- ♿️ Improving accessibility
- ✏️ Fixing typos/updating copy
- 🔒 Securing code

Special
- 🔖 Tagging a version
- 🚀 Deploying a release
- 🥚 Adding an easter egg

Description-only
- 🍵 Caffeinating on tea
- 🍻 Ballmer-peaking
