# Simulation_of_IOT_using_sockets
Simulated IOT (Smart home automation) using Sockets, in C

Sensors and Smart devices connect to the Gateway using sockets. Gateway is multi-threaded such that it can accept requests from multiple sensors. Each item (Sensor, Smart Device or Gateway) is identified by an IP Address and a Port number. When the Gateway process switches on, it listens on the port for “register” requests. Whenever a new item registers with the gateway, it will assign an integer value in sequential order to the item. Gateway takes the inputs from the sensors and decides if it should “switch” the devices “on” or “off” depending on the task. Gateway displays the current state whenever some value from the sensors or the smart device changes.
