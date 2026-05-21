# yakindu-statecharts-realtime-modelling
yakindu-statecharts-realtime-modelling
YAKINDU Statechart models of four real-time systems built using YAKINDU Statechart Tools (YST), covering state-based behaviour, timed transitions, guards, and event-driven logic.

Files
FolderFileDescriptionOpenChoice/OpenChoice.yscSystem controller of own design with 4+ states and a counterIntruderAlarm/IntruderAlarm.yscIntruder alarm with full and partial arming modesCoffeeMachine/CoffeeMachine.yscCoffee machine dispenser for Americano, Latte, and CappuccinoAirFryer/AirFryer.yscAir fryer with meal-specific temperature and timing logic

Exercises
Exercise 1 – Open Choice Model

Custom system controller with at least 4 states and a counter
Simulated and tested within YST
Code generated from the statechart

Exercise 2 – Intruder Alarm

Supports full arming and partial arming modes
Timed password entry windows (20s fully armed / 40s partially armed)
Escalating response: keyboard light → beeps → loud alarm → live video transmission
Monitoring station remote shutoff

Exercise 3 – Coffee Machine Dispenser

Accepts a 2 euro coin before operation
Heats water/milk to 60°C (10 seconds)
Three coffee types with timed dispensing steps:

Americano: coffee + hot water (8s)
Latte: coffee + steamed milk (10s)
Cappuccino: coffee + steamed milk (5s) + frothed milk (5s)


Cancel and refund option available after payment

Exercise 4 – Air Fryer

Prepares different meals (chicken, fish, potatoes, etc.)
Meal-specific temperatures and cook times (e.g. chicken: 200°C for 20 minutes)
Returns to initial state when food is ready


Tools Required

YAKINDU Statechart Tools (Eclipse-based IDE)
Open each .ysc file in its respective project folder within YST


Notes

Each exercise is in a separate folder as required by the submission spec
A PDF with state/stimuli tables and statechart screenshots accompanies this submission
