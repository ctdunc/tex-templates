# NREL Beamer Theme (16x9).
This theme provides the following commands.

`\logoleft{...\includegraphics[...logo_options]{logo}` will insert the NREL logo in the top left corner.

`\cols{int}` specifies the number of expected columns.

`\separatorcolumn` will pad between columns.

`\fundingoffices{text}` will insert the funded offices into the disclaimer provided in the footer.

`\conftitle{title}` will add a conference title.

`\conflocation{loc}` adds a conference location

`\confdates{dates}` adds conference dates.

`\pubtracker{num}` inserts the NREL publication tracking number.


All of these fields must be provided (with the exception of logoleft). 
If they are not necessary, call them in your preamble and leave them blank.
