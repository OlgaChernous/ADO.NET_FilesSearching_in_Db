# ADO.NET_FilesSearching_in_Db
User can choose the directory and mask of files. The tabel FileSystem (columns: path, size, date, text) will be filled by information of searched files. Further the user writes from 1 to 4 criterions in corresponding textboxes  for searching the file (by Name, by Size, by Date of last change, by Text). The result of searching will be displayed in dataGridView. If the user clicks on column Text in dataGridView, the text of the file will be displayed in richTextBox. Also the user has opportunity to synchronize the information in table FileSystem with information in directory .