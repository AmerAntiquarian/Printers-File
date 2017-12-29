# Printers-File
This data details the work of 6,145 printers, publishers, editors, binders, papermakers, and others involved in the printing trade in what is now the United States through 1820. we then partnered with Zepheira to transform the data into BIBFRAME, the library standard for Linked Open Data. The Early Printing Trade vocabulary builds on the BIBFRAME Lite vocabulary to support the description of people involved in all parts of the printing trades in the hand press and early steam press periods. The Printers’ File data now exists in a backend framework on Library.Link Network: http://link.americanantiquarian.org/
Please find the data there, but know that it is not yet easy to search or extract. This is why we have posted it on GitHub. 

The xlsx sheets here reproduce the data as flat files; they are dependent on one another to be understood. The strucure of the data as it exists in these spreadsheets is as follows:
1. Printers.xlsx
     -Column A: Printer ID as assigned during data entry
     *Column B: Last_Name note that the authorized version trumped the version of the name on the card (see 2. Name Variations.xlsx)
     *Column C: First_Name note that the authorized version trumped the version of the name on the card (see 2. Name Variations.xlsx)
     *Column D: Birth_Date 
     *Column E: Death_Date
     *Column F: Birth_Location (see 3. Locations.xlsx)
     *Column G: Death_Location (see 3. Locations.xlsx)
     *Column H: Gender 
     *Column I: Race (see 4. Race.xlsx) 
     *Column J: Notes unstructured data that provides additional information on a person's vital dates or place of birth
     *Column K: Notes unstructured data related to conflicting information that was outside of the purview of data entry to resolve
     *Column L: First_JPEG refers to the scanned index card from which data was entered. These cards can be seen by plugging that 6 digit # into this URL http://www.americanantiquarian.org/pfcards/XXXXX.jpeg Please note that if the number does not have 6 digits, then add "0" before the number provided.
      Column M: Last_JPEG refers to the last of the scanned index cards w information on this printer. Printers can have anywhere from 1 to 10 cards.
      Column N: AUTH_ID refers to an authorization number internal to AAS's OPAC.
      Column O: LC_URI Library of Congress Name Authority File included whenever name verified 
      Column P: VIAF_URI Virtual Internation Authority File included whenever name verified 
      
2. Name Variations.xlsx
      Column A: Name_Var_ID as assigned during data entry
      Column B: Printer_ID taken from 1. Printers.xlsx Column A
      Column C: Last_Name variation as noted on index card or as differs from Library of Congress Name Authority File 
      Column D: First_Name variation as noted on index card or as differs from Library of Congress Name Authority File 
      
3. Locations.xlsx
      Column A: Loc_ID as assigned during data entry 
      Column B: City 
      Column C: State 
      Column D: Country
      Column E: Authority link: location in GeoNames geographical database
      
4. Race.xlsx
      Column A: Race_ID as assigned during data entry
      Column B: Race
      
5. Employment.xlsx
      Column A: Employ_ID as assigned during data entry
      Column B: Printer_ID taken from 1. Printers.xlsx Column A
      Column C: Trade_ID taken from
      Column D: Start_Year
      Column E: End_Year
      Column F: Loc_ID taken from 3. Locations.xlsx Column A
      Column G: Firm_ID
      Column H: Notes unstructed data that provides additional information on employment
      


