# Steps:

## Convert the Raw Data
  1. Export the `.xls` or `.xlsx` file to `csv` 
  2. Use a `csv` to `json` converter to convert the `csv` file to `json`
    a. I used https://csvjson.com/csv2json

## Terminal Commands
  1. `npm init` - Just hit `Enter` a few times until you can input in the regular terminal again
  4. `npm install firebase-admin` - This installs the tool necessary to use Firebase Admin SDK

## Things to Note
  1. `index.js` is the JavaScript program to export a JSON file to Cloud Firestore (located inside your project folder)
  2. `index.js` helps us export the grade distribution json to Firestore for easy access
  3. Open a terminal in your IDE
  4. Change directory to one level before the folder that contains everything. For example, if the path to the project is `/User/Programming/FOLDER_NAME` then navigate to `/User/Programming`
  5. Type in the command `node FOLDER_NAME`
