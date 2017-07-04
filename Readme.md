# Table2Json
Simple JQuery library to convert HTML table to JSON object.
A minimalist jQuery based Table To JSON converter that allows you to 
serialize tabular data into JSON objects.

# How to use it:
- Load jQuery library and the minified version of the jQuery Table2Json plugin at the end of the html page.
     ```JS 
     <script src="//code.jquery.com/jquery.min.js"></script>
     <script src='js/TableToJson.min.js'></script>
     ```
- Convert your tabular data into JavaScript values:
       
     ```JS 
       makeJsonFromTable('tableIDToConvert')
     ```
- Convert JavaScript values to JSON objects:

     ```JS 
       JSON.stringify(makeJsonFromTable('tableToConvert'))
     ```
# Thanks for your support