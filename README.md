# API-Collection
POKEMON SAMPLE GET REQUEST API TEST SUITE
**Requirement :**
PokeApi provide a free to use RESTful set of resources about Pokémon at https://pokeapi.co/api/v2/
Documentation can be found here: Documentation - PokéAPI (pokeapi.co)

**Task**
Creating a suite of tests to validate that the following endpoint works as expected:
Endpoint POKEMON URL : https://pokeapi.co/api/v2/pokemon/{id or name}/
**Assumption :**
1.Information returned by the API is correct, and that your tests are here to safeguard against future regressions. 
2.User has installed POstman latest version preferable in his machine 
3. For Datadriven test scripts in the collection it has to be run via "Runner" with "DataDrivenPokeman" excel passed to the runner in "Select File" option of runner .This excel named "DataDrivenPokeman" have been placed separately.while running this certain gloabal variables need to be unchecked in global variable section for e.g ID and NAME .

Test Suite :
This contains at present five GET requests (2 are for Data driven from runner , 3 are for simply running from postman )
I have used global Variables(global.json) for parameterizing URL-https://pokeapi.co/api/v2/pokemon/ , this will be called in all the request with {{URL}} in global variable and also gloabal variables like ID , NAME and other important fields to be checked .
For simplicity have:
- Three test suites which contains the simple test around ID , NAME and Detailed test.
- Datadriven two test suites are for runner 
- global.json conating the global data for parameterized fields.
Evolving Evolving 

