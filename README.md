
# Smash Ultimate API

The aim of this project is to build a rest api featuring all characters of Super Smash Bros. Ultimate.

## Endpoints

### Character

Example for a GET request:

OperationID: getCharacterByName

*context-path/character/Fox*

returns:

```
{  
  "id" : 7,  
  "name": "Fox",  
  "groundedAttacks": [],  
  "aerialAttacks": [],  
  "specialAttacks": [],  
  "dodgesAndRolls": [],  
  "miscInfo": []  
}
```