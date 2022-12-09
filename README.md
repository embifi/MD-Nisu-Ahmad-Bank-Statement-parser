 # BANK_DATA_PARSER 
- this app takes pdf of bank and convert into text and rendered to front End 
## Features
- Easy to use 
- Upload file and See Your data in table 
## Project Setup
- ejs 
- express
- pdf-parser
## our inedx file
- Use Router and Controler To handle this app
- We use pdf-parsed data to frontEnd wisely Witout using any database
- Just use from and send file to server and all the data manuplate by searver 
- And our Controller converts our pdf to into list of array this array passed to front end Throught Context
- like 
 {
            title: "Bank DataParser",
            name: name,
            // data: JSON.stringify(pdfdata.text)
            DetailArray:DetailArray,
            statement:statement,
            bankDataArray:bankDataArray
        })

