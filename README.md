# Adding English lexicon for matched Thai words

This repository includes:
* Word document `Sustainable AI article.docx` containing part of an article from Krungsri’s Sustainable AI series (“พัฒนา AI อย่างไรให้เป็นมิตรกับสิ่งแวดล้อม”), publicly announced on 22 November 2024 on the Krungsri website. 
The file is provided solely as an example for learning and self-practice (e.g., text processing, glossary insertion, basic NLP).

* Selected glossary entries were extracted from the Word file and compiled into an Excel spreadsheet `glossary.xlsx` containing Thai–English term pairs.

Run `Insert_TH2ENGlexicon_highlightTH.py` to find Find matching Thai terms, insert the corresponding English in parentheses, and highlight the matched Thai terms. 

The processed file (with lexicon and highlights) will be saved as `Sustainable AI article_highlightedTH_lexiconENG.docx`
 
< NOTE > \
Requirement: `!pip install python-docx`

