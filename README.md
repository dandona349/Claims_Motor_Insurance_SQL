# CASE STUDY-SQL
## Claims of Motor Insurance
#### By Emad Asher & Abhishek Dandona

Designed a database for tracking claims in motor insurance to capture customer information, claims pattern and sales performance. The purpose was to generate insights that enable the company to lower loss ratio and improve the sales performance of the employees.

Requirements taken for a Car Insurance company. 
Listed below are the data requirements for customer,vehicle,policy,sales,employee,team,policy type, inspection,claim,addons,employee class and garage.

* The company database has data of customers, vehicles, policies, inspections, claims, garages.
* Customer details are customer ID, first name, last name, age, gender, location.
* Vehicle details are Vehicle Id, make, model, manufacturing year, price
* Policy details are policy number, premium,start date, end date
* Addons details are add on id, name rate
* Policy types details are type and rate
* Sales details are sale id, sale date
* Employee details are employee id, first name, last name, commission, salary
* Team details are team id, name, manager id
* Employee class details are employee class, lower limit , upper limit, rate
* Inspection details are inspection id, start date, end date
* Claim details are claim id, status, approval date
* Garage details are garage id, name, location
* A customer can have several vehicles, but a vehicle can have only one policy.
* Employees receive commission at a fixed rate on their sales. The rate is different for each employee class, where the employee class is determined on basis of number of sales. Better performing employees get more commission.
* Each employee is a team member and each team has a manager.
* A policy has three types, having different coverage. One addon can be added to a policy.
* When a customer applies for claim, the car is inspected first and then claim is either approved or rejected, if approved the car is taken to a garage for repairs.
