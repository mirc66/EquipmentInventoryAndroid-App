# EquipmentInventoryAndroid-App

This is a bare bones equipment inventory collection app.  It was made using MIT App Inventor which makes Android Based apps.  We receive a 25 page paper equipment inventory  with barcode , purchase date, price and item description in separate columns. I scanned and scraped using python(not included here) to create a list of barcode numbers as the  existing list was ordered by date of purchase not barcode number  this is called the paperscrapefile.csv.

The opening screen is a floor plan of the floor our unit is with green dots that you select to select a particular room this opens the input screen where  the room number is auto loaded and you scan all the equipment in that room that has a barcode. You can then select another room either entering it manually on screen or by going back to the floor plan screen.  This program outputs a csv file with a column of data that puts the room number and barcode( a long number) below the room on a single column.  Using R this csv is then scraped  for 3 digit room numbers and  the barcodes below  that number are put on separate column.   The barcodes can then easily be compared.  I wrote a quick python program not included here that compares barcode numbers just scanned to the paperscrpefile and outputs the number and description from the scanned paper document inventory  so disposal or loss documentation can be done.
