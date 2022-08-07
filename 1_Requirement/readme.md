
REQUIREMENTS
EQUIPMENTS REQUIRED
1. Force Sensing Resistors(FSR)
2. Emergency sirens
3. Blue lights
4. ECU’s (3)
5. Clock Timer
6. GPS Locater
7. Microcontroller
8. Storage
L&T Technology Services CONFIDENTIAL Page 7 of 28
HIGH LEVEL REQUIREMENT
S. 
No.
Id Description Status
1. HLR_1 All the subsystem must work both when 
system is on/off.
2. HLR_2 Switch input will decide at what point process 
should stop, either ignition is on/off.
3. HLR_3 FSR should work either system is ON/OFF.
4. HLR_4 Signal must sent to microprocessor.
5. HLR_5 Message with emergency flag is sent to pre 
saved contacts.
6. HLR_6 Call is sent to ambulance.
7. HLR_7 If user does not gives any input upto this 
point, emergency aid is required.
8 HLR_8 Battery must work in both states either 
ON/OFF.
9. HLR_9 Pre-saved contacts must be in working 
condition.
10. HLR_10 Location must be accurate.
11. HLR_11 Data must be correct.
L&T Technology Services CONFIDENTIAL Page 8 of 28
LOW LEVEL REQUIREMENT
S. 
No.
Id Description Status
1. LLR_1 System must work when ignition is 1/0.
2. LLR_2 Any other values other than 0 and 1 will show 
the error.
3. LLR_3 All the subsystem will turn off when switch 
turn off to 0 for emergency flag,
4. LLR_4 System will send 1if FSR sends and force data.
5. LLR_5 ECU will receive 1 as input when siren rings 
for 15 seconds.
6. LLR_6 ECU will send ‘1’ for sending flag emergency 
signal.
7. LLR_7 0 will be sent to all subsystems when turn off 
button is pressed
8 LLR_8 Battery must work in both states either 
ON/OFF.
9. LLR_9 10 seconds for initial relaxation time.
10. LLR_10 After 10 seconds initialisation process should 
start.
11. LLR_11 1 signal will go for indication light.
L&T Technology Services CONFIDENTIAL Page 9 of 28
ANALYSIS
1.4W1
