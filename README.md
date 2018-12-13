# Stolen Bike Cases - JOIN Coding Challenge - Backend (Node.js)

## The context
Stolen bikes are a typical problem in Berlin. The Police want to be more efficient in resolving stolen bike cases. They decided to build a software that can automate their processes — the software that you're going to develop. 
## Requirements
1. Bike owners can report a stolen bike.
1. A bike can have multiple characteristics: license number, color, type, full name of the owner, date, and description of the theft.
1. Police have multiple departments that are responsible for stolen bikes. 
1. A department can have some amount of police officers who can work on stolen bike cases.
1. The Police can scale their number of departments, and can increase the number of police officers per department.
1. Each police officer should be able to search bikes by different characteristics in a database and see which department is responsible for a stolen bike case.
1. New stolen bike cases should be automatically assigned to any free police officer in any department.  
1. A police officer can only handle one stolen bike case at a time. 
1. When the Police find a bike, the case is marked as resolved and the responsible police officer becomes available to take a new stolen bike case. 
1. The system should be able to assign unassigned stolen bike cases automatically when a police officer becomes available.

## Task
Your task is to provide APIs for a frontend application that satisfies all requirements above.
## Tech Requirements
- Node.js
- You are free to use any framework, but it’s recommended that you use one that you’re good at
- Use only SQL Database
- Typescript is a plus

## What we expect
- Build a performant, clean and well-structured solution
- Tests, quality and coverage. 
- Commit early and often. We want to be able to check your progress

## Instructions
- Fork this repo
- The challenge is on!
- Make your API public. Deploy it using the service of your choice (e.g. AWS, Heroku, Digital Ocean...)
- Create a pull request
- Please return your working solution within 7 days of receiving this challenge
