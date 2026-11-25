Project Requirements Document
1. What the Project Aims to Achieve
The goal of this system is to manage the massive logistical headache of hosting a global sporting event, like the FIFA World Cup. It aims to organize how hundreds of thousands of fans move between metro stations, shuttle buses, and stadium gates, while also managing match ticketing and stadium vendors.
Ultimately, the system is designed to prevent chaos, ensure crowd safety, and make sure that transport and stadium facilities are used efficiently without being overloaded.
2. What Problems it Will Solve
If you have ever been to a massive tournament, you know the problems:
•	Fans getting stuck at stadium gates because a seating area is already full.
•	Shuttle buses getting overloaded or assigned to the wrong routes.
•	Fans missing the start of a match because they waited hours for transport.
•	Organizers losing out on money because ticket prices weren't adjusted when demand was incredibly high.
•	Food stalls running out of supplies while other stalls have too much.
This system solves these issues by tracking real-time limits, managing schedules, and automatically enforcing crowd-control rules.
3. What the System Will Do and How it Will Behave
The system will act as a central control hub. Here is how it will behave:
•	Transport Management: It will keep track of metro schedules, shuttle bus routes, and driver shifts. It will actively stop a driver from being assigned to two different buses at the exact same time, and it will prevent a bus from being assigned a route if it is already out on another trip.
•	Crowd & Gate Control: It will monitor stadium seating blocks. If a specific seating block reaches 100% capacity, the system will immediately flag the gates leading to that block as "Closed" so fans are redirected.
•	Ticketing & Dynamic Pricing: It will manage match schedules and seat availability. If a highly anticipated match reaches 85% ticket sales, the system will automatically increase the price for the remaining tickets.
•	Vendor Management: It will assign specific locations to team merchandise stalls and food vendors. It will ensure that vendors are not blocking emergency exits or primary walking paths.
4. What Scenarios and Situations it Will Handle
•	The "Rush Hour" Scenario: A metro train arrives carrying 2,000 fans at once. The system checks the available shuttle buses and automatically dispatches three additional buses to that specific station to clear the crowd.
•	The "Sell-Out" Scenario: Tickets for the Final match are selling rapidly. Once the 85% threshold is hit, the system updates the price for the remaining 15% of seats for any new buyers.
•	The "Overcrowded Gate" Scenario: A block of seats in the North Stand fills up. A fan tries to enter through Gate 4 (which leads only to that block). The system blocks the entry and alerts security to redirect the fan to a different area.
•	The "Double Booking" Scenario: A driver calls in sick. The manager tries to assign a replacement driver to a bus route, but the system blocks it because that replacement driver is already scheduled to drive a different route at that time.
5. What is Included in the Project Scope
•	Tracking and managing shuttle bus routes and metro schedules.
•	Tracking stadium capacity by seating block and entrance gate.
•	Managing staff assignments (drivers, gate security, vendor managers).
•	Managing ticket sales thresholds and automatic price increases.
•	Assigning physical locations to food and merchandise stalls.
•	A dashboard view that shows which gates are open/closed and which buses are currently running.
6. What the System Will NOT Do (Excluded Scope)
•	No Real Payment Processing: The system will track how much a ticket costs and log a sale, but it will not connect to actual banks or credit card companies to process real money.
•	No Live GPS Tracking: The system will track schedules and whether a bus is "Active" or "Delayed," but it will not provide a live, moving map of where the buses are on the road.
•	No Employee Payroll: The system tracks driver schedules and shifts, but it will not calculate their salaries, taxes, or pay slips.
•	No Mobile App Interface: We are not building a downloadable app for fans to use on their phones; this project focuses entirely on the backend system used by event organizers and stadium managers

