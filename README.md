
  # Literate Fiesta

  ![badge](https://img.shields.io/badge/license-uHaveCRUD-blueviolet)
  
  
  ## Description
  This is an  ORM based application designed to allow a user to manipulate table data using expressJs with sequalize through the Insomnia App. User is able to conduct CRUD actions on Categories, Products and Tags

  ## Table of Contents

  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
  
  ## Installation
  1. In mysql: source ./db/schema.sql
  2. npm install express mysql2 sequalize
  3. npm run seed
  

  ## Usage
  1. npm run start
  2. Verify log shows: Listening to port
  3. Open Insomnia or Postman
  4. Base Call: 'http://localhost:PORT/api/OBJECTS'
    - PORT Example: 3001
    - OBJECTS Options:
      * categories
      * products
      * tags
    - POST: 
      * Category
      * Product
      * Tag
    - GET:
      * Category
      * Product
      * Tag
    * PUT:
      * Category
      * Product
      * Tag
    - DELETE:
      * Category
      * Product
      * Tag
  

  ## License
  1. uHaveCRUD
  

  ## Contributing
  1. Maria Meyer
  2. Lucas Zimmerman
  
  ## Questions
  1. Maria Bean: [GITHUB](github.com/mmeyer715)	[EMAIL](mailto:mbean1216@icloud.com)
  2. Lucas Zimmerman: [GITHUB](github.com/dolomiteson)	[EMAIL](mailto:zimmerman.lucas@hotmail.com)
  
  
