# Table Markup
A table represents information in grid format.
Basic table structure contains the following elements:
- 'table': Used to create a table. The contents of the table are written out row by row
- 'tr': Used to add rows to the table. 'tr' should be followed by one or more 'td' elements
- 'td': Used to represent a cell in a table
- 'th': Used just like 'td' but ist purpose is to represent the headings for either a column or a row. 
- Even if a cell has no content, you still use a 'td' or 'th' element to represent the presence of an empty cell otherwise the table will not render correctly.
- Using 'th' elements for the headings helps people who use screen readers, improves the ability for search engines to index the pages, and also enables web authors to control the appearance of tables better with CSS.
- The 'scope' attribute on the 'th' element to indicate whether it is a heading for a column or a row. It can take the values: 'row' or 'col'.
- To span cells in table (merging cells), you can use the span attributes
	- 'colspan' attribute can be used on 'th' or 'td' elements and indicates how many columnsthat cell should run across.
	- 'rowspan' attribute can be used on 'th' or 'td' elements to indicate how many rows a cell should span down the table

There are 3 elements that help distinguish between the main content of the table and first and last rows (which can contain different content). These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table:
- 'thead': Used for headings of table
- 'tbody': Used for main contents of the table
- 'tfoot': Used for table footer
