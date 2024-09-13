**Work in Progress**

# Riskyl Handwired ZMK Keyboard

This project documents my journey of building a handwired wireless keyboard using the nRF Pro Micro a cheaper alternative to the nice!nano and the ZMK firmware.



## ZMK firmware
Getting a workable firmware wat quite a ride for me. It took me several evenings so I am trying to give here a summary of steps what i did to get all the features that i wanted. a good starting point is the offical documentation of ZMK : https://zmk.dev/docs/development/contributing/documentation

### Setting up zmk local
to create a zmk firmware with your desired keymap you basically have to options a) using github actions provided by zmk b) using provided docker environment by zmk.

- I used the docker option because it enables the fast modification of settings and getting feedback if your configurations are viable and lead to a working firmeware or not. (the later one happend guite often which was the reason for me to choose option be)  
- link to set up the environment : https://zmk.dev/docs/development/contributing/documentation

### adding ability to scroll
- https://github.com/zmkfirmware/zmk/pull/2027 