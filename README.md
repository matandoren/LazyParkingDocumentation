# LazyParking

### Introduction
This project is a parking lot management system for a theoretical smart parking lot (that uses a card reader, an automated gate and sensors that can sense if a vehicle is occupying a parking spot). <br>
Such parking lot is intended to serve a particular group of people. Some examples are:
- A parking lot of a building that serves only the residents of that building
- A parking lot of a factory that serves only the people employed at that factory
- A parking lot of a college that serves only the students and staff of that college

The client provides drivers a visual representation of the current state of the parking lot which allows them to easily find an empty parking spot <br>


`*` Since this parking lot is theoretical, the operation of the card reader, gate, sensors and drivers using the parking lot is simulated in the server using mockup modules

([LazyParkingServer](https://github.com/matandoren/LazyParkingServer), [LazyParkingWindowsClient](https://github.com/matandoren/LazyParkingWindowsClient) and their respective
[documentation](https://github.com/matandoren/LazyParkingDocumentation) were created by Ohad Hever, Tima Kukushkin, Matan Oren and Gilad Rozin
for their Software Engineering course project <br>
[LazyParkingAndroidClient](https://github.com/matandoren/LazyParkingAndroidClient) and its repspective [documentation](https://github.com/matandoren/LazyParkingDocumentation)
were created by Tima Kukushkin and Matan Oren for their Developing client-side in Android Environment course project)

### How to use?
### `Step 1:`
Launch [LazyParkingServer](https://github.com/matandoren/LazyParkingServer) using the entry point at parkingLotServer.ParkingLotServer (you don't have to log in) <br>
To log in to the Admin UI use:
- Username: admin
- Password: 123456

### `Step 2:`
Launch a client ([LazyParkingWindowsClient](https://github.com/matandoren/LazyParkingWindowsClient), [LazyParkingAndroidClient](https://github.com/matandoren/LazyParkingAndroidClient)) <br>
To log in as a Driver use:
- Username: driver
- Password: 123456

To log in as an Operator use:
- Username: operator
- Password: 123456

Most operations available in the UI are self descriptive. They appear as buttons on the right hand side of the UI in both the Windows client and the Admin UI on the server
and as menu items that pop up after you tap the "more options icon" (the 3 vertical dots icon) on the Android client. <br>
The arrow buttons are used for navigating between floors. <br>
Operators can reserve parking spots by left-clicking (on the Windows client) or tapping (on the Anroid client) on a parking spot that is not already reserved.
To release a reserved parking spot left-click/tap it.
