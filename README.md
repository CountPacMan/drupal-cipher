# Drupal Cipher Assessment for Epicodus
## by Daniel Toader
### Date: May 22, 2015
#### Description
Basic Drupal 7 site as a showcase for a custom cipher module. This module encrypts user input using a Shift Ciper. The user inputs a shift value, direction, and phrase. The module returns the encoded phrase based on the given specifications. All input is validated before result is calculated.

#### Setup instructions
1. Clone this git repository
2. Import the database that exists in sites/db-backups/daniel_cipher.sql to your mysql server
3. add db user "cipher_admin" with password "epicodus" and all privileges to the db
3. Ensure Apache server is running with PHP server and pointed to the root folder for this site
4. Start the web app by pointing your browser to the root (http://localhost:8888/)  

#### Drupal login instructions
Users created are:
1. "admin" with password "epicodus"
2. "user" with password "epicodus"

#### Copyright © 2015, Daniel Toader  

#### License: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE)

#### Technologies used
- Drupal 7.36
