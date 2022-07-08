# API
# Title : REST API for managing the statistics of the soccer players of the national team of Togo

This includes actions related to data collection, processing and retrieval under the node.js environment using express.js.



### . URL


   https://tranquil-ravine-60224.herokuapp.com/


### - Method :

<The request type>

`GET` | `POST` | `DELETE` | `PUT`

### - URL Params :

#### Required:

`id=[integer]`

 ### `Tools used to build the API :`

####  - NodeJS

 ####  - Express.js – Fast, unopinionated, minimalist web framework for [Node js](https://nodejs.org/en/)
 
 ### `Packages installed :`
 
#### - nvm – Node Version Manager
#### - npm – Node Package Manager
#### - Node.js
#### - Express installed with npm (npm install express body-parser morgan).

 ### `How to Use :`
 
 #### - POST https://tranquil-ravine-60224.herokuapp.com/api/v1/stats
 
 - This will create the stats a player

 `- this is the input examples
  {
    "id": 7,
    "wins": 8,
    "losses": 2,
    "points_scored": 34
  }`
 
`- and it will return json file like this
  {
    "id": 7,
    "wins": 8,
    "losses": 2,
    "points_scored": 34
  }`


#### - GET https://tranquil-ravine-60224.herokuapp.com/api/v1/stats/7

 `- This will get the stats for player 7
 {
    "id": 7,
    "wins": 8,
    "losses": 2,
    "points_scored": 34
  }`
 #### - PUT https://tranquil-ravine-60224.herokuapp.com/api/v1/stats/7
 
 . This will update the stats for player 7
 `- this the input 
 {
    "id": 7,
    "wins": 82,
    "losses": 2,
    "points_scored": 34
  }`
  
  
 - and it will return json file like this
`{
    "id": 7,
    "wins": 82,
    "losses": 2,
    "points_scored": 34
  }`
  
  #### - DELETE https://tranquil-ravine-60224.herokuapp.com/api/v1/stats/10
  . This will delete the stats for player 10
  
  ` - this the input 
 {
    "id": 10,
    "wins": 82,
    "losses": 2,
    "points_scored": 34
  }`
  
