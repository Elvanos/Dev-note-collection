# Convert all SASS to SCSS recursively

1. **Do:** sass-convert -R *[SOURCE]* --from sass --to scss
2. **DO:** Get-ChildItem *.sass | foreach { Remove-Item -Path $_.FullName }
