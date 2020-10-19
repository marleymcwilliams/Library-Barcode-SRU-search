# Library-Barcode-SRU-search

Barcode x can plug into getTitle(x) and getMmsId(x). Convinient for Excel especially.

You'll need to know your Ex Libris institution code (sometimes also referred to as "Alma institution code" or "Source ILS institution code"; ex. OSU is "01ALLIANCE_OSU").
Plug that into the function at the URL indicated by the comment (sorry, you'll have to do it once per function).

If you're in excel/sheets, under the "tools" tab, select "Script editor" and paste the code into the window.
If a cell has your barcode, ex. at C5, and you want its respective title at A5, click into A5 and type "=getTitle(C5)" or "=getMmsId(C5)" for MmsId.
