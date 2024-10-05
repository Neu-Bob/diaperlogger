Diaper Logger,  use node-red to write events to a google spread sheet then pull the sum of the events as a number to a property in HomeAssistant or NodeRed

1. Configure Node-Red with the correct spreadsheet 

https://docs.google.com/spreadsheets/d/1PHTnzUlZ7UH0CfWVRG7MpbFkuDRjJ3s58pMT03BjZkU/edit?gid=0#gid=0

Let's configure the Google Sheets node in Node-RED:
Open your Node-RED flow.
Drag in a Google Sheets node and double-click to edit it.
In the "Spreadsheet ID" field, paste: 1PHTnzUlZ7UH0CfWVRG7MpbFkuDRjJ3s58pMT03BjZkU.
In the "Worksheet Name" field, enter: Sheet1.

