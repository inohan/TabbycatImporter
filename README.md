# TabbycatImporter
Tabbycat Importer is a web application created using Node.js to upload debater / team / adjudicator data to [TabbycatDebate/tabbycat](https://github.com/TabbycatDebate/tabbycat).
## How to use
1. Install [Node.js](https://nodejs.org/en).
2. Install this repository from **Code >> Download ZIP**.
![Instructions](TabbycatImporter01.PNG)
3. Expand the ZIP file. Copy the file path.
![Instructions](TabbycatImporter02.PNG)
4. Open command prompt (cmd).
5. Enter
   ```
   cd (file path)
   npm install
   node server.js
   ```
   to start the local server.
6. Access [localhost:3000](http://localhost:3000/). Start from settings.
7. Fill in the template for [Teams](Teams.xlsx) and [Adjudicators](Adjudicators.xlsx) and upload them.
8. Press `ctrl+C` on command prompt when you want to quit.
