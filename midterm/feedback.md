# Midterm Feedback
The midterm feedback will be very similar to what you receive on a weekly basis for the homework, but more specific for each problem in this case.

## Final Score: 41.5/50


### Step 1: Priest Score Calculation
* **5pts** - Your code computed the correct probability and returned it
  * **(-0.5pts) You have a mistake in how the scores between 17 and 25 are handled.  That should have just said `percentage = 0.59` but you didn't have any test cases to exercise that condition. Otherwise, you would have seen the failure**
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring

### Step 2: Find a Hospital
* **5pts** - Your code correctly fetched the correct hospital given the inputs using requests
  * **(-3 pts) Your code has the URL parameters hard coded.  Didn't you notice that all your test cases returned the same answer.  Was that by design?**
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring

### Step 3: Get the Hospital Address
* **5pts** - Your code correctly fetched the JSON file, parsed it, and looked up the hospital
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring

### Step 4: Process List of Patients
* **10pts** - Your code correctly fetched the psv file, looped through it, and ran your other functions
* **2pts** - You had a docstring that described what the function was for

### Step 5: Compare Results
* **5pts** - Your code looped through all the results and compared them to the provided key
  * **(-4 pts) - Bad variable names `x` and `y`, and your code didn't do the work of comparing the output with the expected results**

### Extra Credit
* Up to 15 pts based on correctness and quality of the extra credit step

### Coding Best Practices:
**3 pts** - Was your code readable, efficient, and in line with what we learned in class?
* Good variable names?
* Code written into functions where appropriate?
* Appropriate comments with your code?
* Generally easy to follow and undersand?
  * **(-1 pts) Your code tends to be squished together in tight blocks, making it very hard to read where one idea ends and the next starts.  Remember that you want your code to be readable by other people**
