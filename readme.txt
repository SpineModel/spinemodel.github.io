==== Convert markdown to html using Pandoc:
for file in $(find . -type f -name "*.md"); do pandoc -f markdown -t html "${file}" -o "${file%md}html"; done
