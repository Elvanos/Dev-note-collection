# Convert all SASS to SCSS recursively

1. Open terminal inside project
2. **Do:** sass-convert -R *[SOURCE PATH]* --from sass --to scss
3. **DO:** Get-ChildItem *.sass | foreach { Remove-Item -Path $_.FullName }
