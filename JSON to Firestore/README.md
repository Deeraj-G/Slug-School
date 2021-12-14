# Steps:

## Convert the Raw Data
Export the `.xls` or `.xlsx` file to `csv` 

Use a `csv` to `json` converter to convert the `csv` file to `json`

I used https://csvjson.com/csv2json

## Terminal Commands
`npm init` - Just hit `Enter` a few times until you can input in the regular terminal again

`npm install firebase-admin` - This installs the tool necessary to use Firebase Admin SDK

## Things to Note
`index.js` is the JavaScript program to export a JSON file to Cloud Firestore (located inside your project folder)

`index.js` helps us export the grade distribution json to Firestore for easy access

Open a terminal in your IDE

Change directory to one level before the folder that contains everything. For example, if the path to the project is `/User/Programming/FOLDER_NAME` then navigate to `/User/Programming`

Type in the command `node FOLDER_NAME`
