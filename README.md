# FOR-DEBATE---Deletes-all-non-highlighted-and-non-bolded-text-in-a-word-doc
To delete all non-highlighted or non-bold text, you must
Open the .docx as a ZIP
Extract word/document.xml
Parse/modify XML runs (<w:r>)
Keep only runs with <w:b/> (bold)
OR <w:highlight> (highlighted)
Repack the .docx

To make sure that it will not delete the highlights, find the code that says "yellow" on line and change it with the color that you want.
