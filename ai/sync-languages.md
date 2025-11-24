 Task: Syncronize changes across the source of the multilincual content.

Example:
- Find changes to the content in spanish with: `git diff -- index.qmd`
- Translate that to english and write it in the corresponding location in index.en.qmd

Similarly, find changes to the english content with `git diff -- index.en.qmd` then translate it so latinamerican spanish (using "voceo") and write it to index.qmd

Do that same for all index* files for all languages. 
