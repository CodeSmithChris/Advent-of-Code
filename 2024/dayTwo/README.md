- Each new line is a report
- Each report has levels
- A report is only valid (safe) if the levels are either increasing or decreasing in value by [1-3] 
- Tally the safe reports
- Submit tally

### Possible solution
Create a list of Structs with an int array and bool for safe
Create a node for each new line and assign that line to the array
If true compare indices if the value is continously increasing or decreasing by a value of [1-3]
If true switch the bool to true
Count number of structs with safe == true
