Task: Syncronize changes across the source of the multilincual content.

Example:
- Find changes to the content in spanish with: `git diff -- index.qmd`
- Translate that to english and write it in the corresponding location in index.en.qmd

Similarly, find changes to the english content with `git diff -- index.en.qmd` then translate it so latinamerican spanish (using "voceo") and write it to index.qmd

Do that same for all index* files for all languages. 

README.md is also multilingual but has all languages in that single file, each under a language-specific `<summary>` section. If you detect changes in README.md syncronize them across all sections.

If `git diff` shows nothing it's possible that the user staged or commited the changes. Explore and ask.

IMPORTANT: If you see a conflict across languages (e.g. changes in two languages dissagree) warn the user and help them to resolve the conflicts.

