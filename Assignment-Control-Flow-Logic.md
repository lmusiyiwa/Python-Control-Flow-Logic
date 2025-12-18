Python Fundamentals - Assignment 3
This assignment will test your ability to control the flow of your programs using conditional logic (if/elif/else) and loops (for/while).

Exercise 5: Clinical BMI Calculator 
Scenario: You are creating a program to calculate a patient's Body Mass Index (BMI) and determine their weight status.
Formula: BMI = weight (kg) / height (m)²
Your Task: Write a program that:
Prompts the user to enter their weight in kilograms and their height in meters.
Calculates their BMI using the formula.
Uses if, elif, and else statements to determine the patient's weight status based on these criteria:
BMI less than 18.5: "Underweight"
BMI between 18.5 and 24.9: "Normal weight"
BMI of 25.0 or more: "Overweight"
Prints a formatted message showing their calculated BMI (rounded to one decimal place) and their weight status.

Exercise 6: Lecture Theatre Occupancy Check 
Scenario: A lecture theatre has a maximum safe capacity of 120 occupants. You need to write a program that checks if an event is violating this regulation.
Your Task:
Create a variable max_capacity and set it to 120.
Prompt the user to enter the number of people expected to attend.
If the number is less than or equal to max_capacity:
Calculate how many more people can attend.
Print a message stating the event is legal and the number of available spots.
If the number exceeds max_capacity:
Calculate how many people must be excluded.
Print a message stating the event is illegal and the number of people who must be turned away.

Exercise 7: Pharmacy Inventory Report 
Scenario: The head pharmacist wants a report of all medications with names longer than 10 characters, as they require special labels.
Your Task:
Start with this inventory dictionary:
Python
pharmacy_inventory = {
    'Analgesics': ['Paracetamol', 'Ibuprofen'],
    'Antibiotics': ['Amoxicillin', 'Doxycycline', 'Penicillin V'],
    'Antiseptics': ['Iodine', 'Chlorhexidine', 'Hydrogen Peroxide']
}


Use a for loop to go through the values of the dictionary.
Inside that loop, use another for loop to go through each individual medication name.
Use an if statement to check if the length of the medication name is greater than 10.
If it is, print a message like: Long name alert: Chlorhexidine (13 characters).