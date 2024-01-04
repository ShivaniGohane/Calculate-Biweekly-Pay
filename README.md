# Prepare test case covering "all" scenarios in one example. This one example should cover all scenarios.		
More complicated example covering all possible scnearios will be given higher points.	
Mutliple test cases covering different scenarios are also acceptable but priority will be to complex test case covering multiple scenarios.


Comprehensive Test Case

Input:
* Employee Type: Hospital Nurse
* Employee Salary: $100/Hour (Supervision of patients considered for salary)
* Working Hours/Day: 9
* Working Days/Week: 5
* Pay Period: Biweekly
* Overtime Rates:
    * 20% additional hourly rate for overtime hours (Up to 50 hours a week)
    * 15% additional hourly rate for overtime hours (Above 50 hours a week)
    * 25% additional hourly rate for overtime hours (Between 2 am to 5 am)
    * 30% additional hourly rate for overtime hours (On National Holiday)
    * Breaktime: 30 minutes after every 3.5 hours (not counted for salary calculation)

 Schedule:
 
1. Date-> 1-Jan-24  Time->2:00 AM to 11:00 PM		
2. Date-> 2-Jan-24	Time->2:00 AM	to 11:00 PM	
3. Date-> 3-Jan-24	Time->2:00 AM	to 11:00 PM	National Holiday
4. Date-> 4-Jan-24	Time->2:00 AM	to 11:00 PM	
5. Date-> 5-Jan-24	Time->2:00 AM	to 11:00 PM	
6. Date-> 6-Jan-24	Time->2:00 AM	to 11:00 PM		
7. Date-> 7-Jan-24	Time->2:00 AM	to 11:00 PM		
8. Date-> 8-Jan-24	Time->2:00 AM	to 11:00 PM		
9. Date-> 9-Jan-24	Time->2:00 AM	to 11:00 PM		
10. Date-> 10-Jan-24	Time->2:00 AM	to 11:00 PM	National Holiday
11. Date-> 11-Jan-24	Time->2:00 AM	to 11:00 PM		
12. Date-> 12-Jan-24	Time->2:00 AM	to 11:00 PM		
13. Date-> 13-Jan-24	Time->2:00 AM	to 11:00 PM		
14. Date-> 14-Jan-24	Time->2:00 AM	to 11:00 PM


Expected Earnings Calculation:

1. Regular Hours:
* Total Regular Hours: 14 days * 9 hours/day = 126 hours
* Breaktime deduction: 12 breaks * 0.5 hours/break = 6 hours
* Regular hours without break: 126 hours - 6 hours = 120 hours
* Regular Earnings: $100/hour * 120 hours = $12,000

2 Overtime Hours (Up to 50 hours a week):
* Total Overtime Hours: 14 hours (No overtime exceeds 50 hours a week)
* Overtime Earnings: $100/hour * 14 hours * 20% = $280

3. Overtime Hours (Above 50 hours a week):
* No overtime hours exceed 50 hours, so no additional calculation.

4. Overtime Hours (Between 2 am to 5 am):
* Total Overtime Hours: 14 hours (All work hours fall between 2 am to 5 am)
* Overtime Earnings: $100/hour * 14 hours * 25% = $350
	
5. Overtime Hours (On National Holiday):
* Total Overtime Hours: 14 hours (All work hours fall on a National Holiday)
* Overtime Earnings: $100/hour * 14 hours * 30% = $420

6. Total Earnings for the Biweekly Period:
* Regular Earnings + Overtime Earnings = $12,000 + $280 + $350 + $420 = $13,050


# Calculate earnings/total pay check for the nurse for above example/examples

1. Date-> 1-Jan-24	Time->2:00 AM	to 11:00 PM		
2. Date-> 2-Jan-24	Time->2:00 AM to	11:00 PM	
3. Date-> 3-Jan-24	Time->2:00 AM	to 11:00 PM National Holiday
4. Date-> 4-Jan-24	Time->2:00 AM	to 11:00 PM	
5. Date-> 5-Jan-24	Time->2:00 AM	to 11:00 PM	

Earnings Calculation:

1. Regular Hours:
* Total Regular Hours: 5 days * 9 hours/day = 45 hours
* Breaktime deduction: 5 breaks * 0.5 hours/break = 2.5 hours
* Regular hours without break: 45 hours - 2.5 hours = 42.5 hours
* Regular Earnings: $100/hour * 42.5 hours = $4,250

2. Overtime Hours (Up to 50 hours a week):
* Total Overtime Hours: 0 hours (within the 50 hours limit)
* Overtime Earnings: $0

3. Overtime Hours (Above 50 hours a week):
* No overtime hours above 50 hours, so no additional calculation.

4. Overtime Hours (Between 2 am to 5 am):
* Total Overtime Hours: 45 hours (all work hours fall between 2 am to 5 am)
* Overtime Earnings: $100/hour * 45 hours * 25% = $1,125

5. Overtime Hours (On National Holiday):
* Total Overtime Hours: 8 hours (all work hours fall on a National Holiday)
* Overtime Earnings: $100/hour * 8 hours * 30% = $240

7. Total Earnings for the Biweekly Period:
* Regular Earnings + Overtime Earnings = $4,250 + $1,125 + $240 = $5,615

The total paycheck for the nurse for the specified schedule and conditions would be $5,615.
