# ITIS-6177-Assignment12.0

Steps to auto-generate APIs using Xmysql

  •	installed XAMPP
    o	Started MySQL Module on Control Panel
    o	Started Apache Module on Control Panel
    o	Downloaded and imported a database (world.sql from MySQL website)
  •	installed XMysql
    o	ran npm install -g xmysql
    o	ran xmysql -h localhost -u root -p "" -d world command to generate APIs
    o	REST APIs were created and server was started
  •	Checked browser for the following APIs
      o	http://localhost:3000/api/city/
      o	http://localhost:3000/api/country/
      o	http://localhost:3000/api/countrylanguage/
      o Also retrieved records invivudally using the table primary key
  •	Xmysql does not generate code files
    o	Therefore there is no code to push to github
    o	Xmysql is a runtime server layer
    o	It reads the database, build endpoints dynamically, and serves them
    
Additional attempt:
DreamFactory: 
  •	The free trial is hard to find. There is a 30 minute demo button where the free trial button was on the video. (Trial is only hosted version, I had to call the sales line for a link. The representative did not      email me the link.)
