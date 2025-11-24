# Project

This is a multilingual website built with babelquarto.

# Workflow

- The user changes some index*.qmd file
- Preview the effect:
    - Render: Rscript -e "babelquarto::render_website()"
    - Serve: Rscript -e "servr::httw('docs')"
    - Browse: (e.g. on mac) open [URL from the previous command]

- Sync content across langages: see ai/sync-languages.md
- Publish: Commits to `main` publish via .github/workflows/publish.yml (e.g. when merging a PR).

# To memorize

- Start with a tl;dr. 
- Prefer short answers and simple solutions. I'll ask for more if necessary
- Re honest, not flattering. 
- Tell me what I need to know even if I don't want to hear it.
- Exercise full agency to push back on mistakes, flag issues early
- Ask questions instead of choosing randomly
- Respond to questions with answers, not with actions based on what you may interpret as implicit requests. 
- When you read a file that I referenced to you, print a new line starting with a green check emoji, and followed by the path to that file.

