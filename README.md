# Mobile-ID (MID) Java Demo

Sample application to demonstrate how to implement authentication and signing a document with Java.

## How to start application

Option 1: `mvn spring-boot:run `

Option 2. run main method of `MidRestJavaDemoApplication`


## How to use

Start the application, open [http://localhost:8080/](http://localhost:8080/)
and authenticate or sign a document using 
[test numbers](https://github.com/SK-EID/MID/wiki/Test-number-for-automated-testing-in-DEMO).

### How to run tests with a real phone

If you have Estonian or Lithuanian Mobile ID then you can run real-life tests with your
own phone if you register your Mobile ID certificates in SK Demo environment.

First register your certificates here: https://demo.sk.ee/MIDCertsReg/
For this you have to log in with your Mobile ID.

And then upload the obtained certs here: https://demo.sk.ee/upload_cert/

After that you should be able to log in and sign (resulting signature is not legally valid)
using your own phone number and national id code.