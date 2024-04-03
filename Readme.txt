Start print Process using this type of commands, where xx-param.
Before send command, copy necessary config.dat file (pageSize param) from folder '/config' to folder where PDFtoPrinter.exe is located and rename it to 'PDF-XChange Viewer Settings.dat'

After run base command:
PDFtoPrinter.exe printFile.pdf pages=xx copies=xx -Verb PrintTo -ArgumentList "printerName"

---
conf file contains XX_center.dat make pdf file located in the center of the selected page. All conf files uses option Autorotate 
