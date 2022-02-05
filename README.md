# Project_Nomnio

Project idea is, that we have two ESP32's, one is acting as central other is peripheral. Peripheral has also simple web server. From web server we send command, which is executed on central device, without internet connection. 

![image001](https://user-images.githubusercontent.com/54038162/152644845-c5bd2066-1e82-4d0b-8832-c3112b5be018.png)

![image002](https://user-images.githubusercontent.com/54038162/152644904-87c83146-347f-422b-98c9-cc0425529d23.png)

In published example is GET request:

IP_ADDRESS/GET/L -> sets LED low.
IP_ADDRESS/GET/H -> sets LED high.


