
# Smash Ultimate API

The aim of this project is to build a rest api featuring all characters of Super Smash Bros. Ultimate. 
Characters have attributes mainly based on their frame data and other stats available like their weight for example.

## Endpoints

### Character

Example for a GET request:

OperationID: getCharacterByName

*/api/v1/character/Fox*

returns:

```
{  
  "id" : 7,  
  "name": "Fox",  
  "groundedAttacks": [],  
  "aerialAttacks": [],  
  "specialAttacks": [],  
  "grabsAndThrows": [],
  "dodgesAndRolls": [],  
  "miscInfo": []  
}
```