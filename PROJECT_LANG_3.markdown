
***

# Project language file number 3

## For: DeGoogle Your Life: Its time to cut WideVine DRM

The 3rd project language file for this project (WacOS)  is Markdown, as this project uses Markdown significantly in documentation, and I am now including all languages as project language files.

This is an instance in which I am using Markdown as a project language file, as I learned how to make the GitHub linguist recognize Markdown as a language. I found this out when snooping around on [Apple/Swift Evolution](https://github.com/apple/swift-evolution/blob/main/.gitattributes) if you want to do this yourself, simply add this to your `.gitattributes` file (if you haven't created one yet, make it now, do not add anything else to the file name but `.gitattributes`)

```gitattributes
*.md linguist-detectable=true
*.md linguist-documentation=false
```

Extended version:

```gitattributes
# Markdown
*.md linguist-detectable=true
*.md linguist-documentation=false
*.mkd linguist-detectable=true
*.mkd linguist-documentation=false
*.markdown linguist-detectable=true
*.markdown linguist-documentation=false
```

## File info

File type: `Markdown document (*.md .mkd *.mdown *.markdown)`

File version: `1 (Tuesday, 2021 December 28th at 6:24 pm)`

Line count (including blank lines and compiler line): `38`

***
