# Secured Entrance System
Secured Entrance System Project ECE 4894

The secured entrance system for facilities is a consumer grade door lock security system under which the person residing in the facility can authorize a visitor to enter the facility by putting in a request in the database. The resident can use a java based application to enter the credentials of a visitor in a MySQL database. Once a visitor has been entered in the database, that visitor is allowed to enter the building for the following 10 minutes using an RFID tag. For our project, we simulated the infrastructure of Georgia Institute of Technology. The Java application is used to enter the visitor’s name and GT ID. The visitor can then use his/her GT ID on a RFID reader,which is connected to Arduino UNO. Arduino UNO parses the card to a tag, and checks the database to see if any GT ID in the visitor table has a matching tag. If it has a matching tag, the Arduino UNO sends a signal to specify that the user can enter provided time limit is satisfied.