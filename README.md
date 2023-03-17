# BI-RnM
Repo for orgmode version of book "Building Information - Representation and Management"

Epub file of the book was downloaded from https://textbooks.open.tudelft.nl/textbooks/catalog/book/47.

I have only converted the the epub file to orgmode and related files in media folder with pandoc command:
``` 
pandoc --from epub --to org -o buildingInformation.org --extract-media=media ~/Downloads/47-Book\ Manuscript-341-1-10-20220215.epub

```
Copyright for the book:

Copyright (c) 2022 Alexander Koutamanis

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
