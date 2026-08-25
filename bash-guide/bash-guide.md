# :octopus: Bash Scripting & Shell Snippets

Personal reference for shell operations, batch management, and environment rules.

---

## Batch Archive Extraction
### Uncompress all .zip archives in the current directory without overwriting existing files:
'''bash
$ for f in *.zip; do unzip -n "$f" done 
'''
