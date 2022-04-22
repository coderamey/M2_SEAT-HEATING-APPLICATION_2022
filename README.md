# M2_SEAT-HEATING-APPLICATION_2022


## OBJECTIVE:

The Seat Heating control system is basically used to control the temperature of a car seat. When a passanger or a driver of the car seats on a car, the button sensor gets activated (which acts as one switch). After that, the user has to turn on the heater(which acts as another switch). The temperature sensor keeps monitoring and recording the temperature and sends the analog value to the microcontroller ATmega328. The microcontroller takes the analog input of the temperature sensor and gives output a temperature value through UART( through serial communication)

## CI and Code quality:
# SIMULATION RESULTS:
![41](https://user-images.githubusercontent.com/101514346/164737089-ec9ae836-6c6b-4ff0-8a4d-14781631302e.jpeg)

# ACTIVITY 1

## If the user seated onto the seat and then he had turned on the heatbutton , only then the led should turn on.


# Simulation results

![11](https://user-images.githubusercontent.com/101514346/164737713-b0dd2d8b-1fb4-42ff-a02b-a15b942ff5e2.jpeg)

Both switch are open(0 0)


![12](https://user-images.githubusercontent.com/101514346/164737822-827983f4-1e9d-44cf-a7a5-a9df7e936e57.jpeg)

Either of switch is open (0 1 or 1 0)


![13](https://user-images.githubusercontent.com/101514346/164737958-1f10cdc0-c015-4972-8c96-f3650da57135.jpeg)

Both switch are closed(1 1)

# ACTIVITY 2
## To take input from temp sensor and to indicate changes at a particular temparture.
Since temp sensor is not availaible in simul ide made use of potentiometer and calculated the voltages for particuar range.


# Simulation Results:
![21](https://user-images.githubusercontent.com/101514346/164738345-33b5def0-c2de-4de1-a5b8-cbf74638ede5.jpeg)

# ACTIVITY 3
## To generate pwm at different analog values.

# Simulation Results:
![33](https://user-images.githubusercontent.com/101514346/164738674-e2ae49a4-211c-4e5e-aff2-1a249d45ddde.jpeg)
Output PWM-20%

![34](https://user-images.githubusercontent.com/101514346/164738808-ffd097a2-5f43-4a61-b839-fadd36c00ed2.jpeg)
Output PWM-40%

![32](https://user-images.githubusercontent.com/101514346/164738963-b549f601-fde2-4a61-a501-ef6a4f4bab24.jpeg)
Output PWM-71%

![31](https://user-images.githubusercontent.com/101514346/164739079-a9c0c06b-3f74-4c94-9bed-e5019c2478a4.jpeg)
Output PWM-95%

# ACTIVITY 4
## To send the temperature value to a Serail monitor.
![44](https://user-images.githubusercontent.com/101514346/164739265-5c2e022a-c0a8-4960-adb3-3d53276553aa.jpeg)
