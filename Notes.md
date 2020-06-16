Went back to week 2 work with wget
  Was having trouble finding a suitable data set using the methods we used that week
  tried several from Amalia Skarlatou Levi's twitter thread
  Was interested in the old bailey but felt stonewalled by the site format
    Individual pictures saved as .gif files, and directly beside was an already OCR and cleaned version of the text
 Decided to move on and try to grab a data set from Chronicling America as we did in week 2 with APIs
  Tried a few search tems, came up with some good results for 'hockey'
  Retraced steps of week 2 API discussion, changed search term in the script
  Ran into similar problems as I was having previously with nothing shoing up when I ran the script in command prompt
  Switching to powershell gave desired data, though I was limited to 20 results
    Probably something to do with the 'results per page' limit from the website
    not sure how to get rid of this and access the full 62000 results
    I'm worried that would be overwhelming to parse with my current skillset so I'll stick to 20 for now
  Converted to csv file with online converter
  Once in Excel I removed unnecessary columns
    Would later realise I only deleted the data in the columns, not the column itself
    Fixed that in OpenRefine
  Opened csv in OpenRefine
    Cleaned up file buy trimming whitespace, getting rid of empty columns
    Clusters were minimally useful
      In order to get it to pick up any similarities, I had to open up the parameters
      Rather than clustering based on the word [volume], which appeared for every entry
      I selected a cell, edited as needed and used the 'apply to all identical cells' function
   Exported back into a more manageable csv
   Opened in Excel
    Worked to get sum totals of the chosen keyword for each publication
    Shown adjacent to first instance of each publication appearing on list
    Also threw in total instances of chosen keyword
    Added simple visualisation based on instances vs publication
    Saved as excel workbook
   Upload to voyant
    Played with different visualisation tools
    Realised I do not have the chosen keyword 'Hockey' anywhere in my completed visualisation
      Needed to zoom out a bit more throughought the process to catch this
   Skipped final part based on week 5 due to time constraints
