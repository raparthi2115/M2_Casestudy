# SEAT HEAT MONITOR AND CONTROL SYSTEM

* In the places where snow falls or temperature is less,that is around zero degree centigrade, people feel comfort if the car seats are warm while travelling.
* In this project Microcontroller ATMega 328 is used to control seat temperature.
* Program is designed like Heater starts operation only if person is sitting on seat and heater switch is closed.
* When both above conditions are true Temperature sensor starts sensing tempraure of seat.
* If seat temperature is more than 25 deg centigrade,there will be no supply to heater because seat is warm enough.
* If temperature is less than 25 deg PWM output drives the heater driver circuit.
* PWM output and temperature values are inversely proportional i,e lesser the temperature more value of PWM signal will drive the heater.
* For different range of temperature values different PWM value signal is generated.
* When temperature rises above 25 deg,PWM signal will be 0(low).
* All this opeartion is automatic and also temperature range is transmitted to serial output.


# Code quality ![Code Quality Score](https://api.codiga.io/project/32895/score/svg)
# Code grade ![Code Grade](https://api.codiga.io/project/32895/status/svg)
# Codacy [![Codacy Badge](https://app.codacy.com/project/badge/Grade/31209cbebccc4d6db984a2b44ee05392)](https://www.codacy.com/gh/raparthi2115/M2_Casestudy/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=raparthi2115/M2_Casestudy&amp;utm_campaign=Badge_Grade)
# C-cpp [![C/C++ CI](https://github.com/raparthi2115/M2_Casestudy/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/raparthi2115/M2_Casestudy/actions/workflows/c-cpp.yml)
# Cpp Check [![Cppcheck Analyse](https://github.com/raparthi2115/M2_Casestudy/actions/workflows/Cppcheck_Analyse.yml/badge.svg)](https://github.com/raparthi2115/M2_Casestudy/actions/workflows/Cppcheck_Analyse.yml)

 
![image](https://user-images.githubusercontent.com/89759853/133575039-3e8920ef-936b-44ad-91cf-148a67c476a2.png)



