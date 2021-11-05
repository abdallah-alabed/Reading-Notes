## Random Module in Python
The random module provides access to functions that support many operations. Perhaps the most important thing is that it allows you to generate random numbers.

**Randint**:
accepts two parameters: 
- a lowest (beginning of the range)
- a highest number. (end of the range) (low must be lower then high)

**Random**:
random number between 0 and 1 ( multiply by something to enlarge the scale)

**Random.choice**:
choose an element randomly from a list

**Random.shuffle**:
shuffle list items into random order

**Randrange**:
Generate a randomly selected element from range(start, stop, step)


## Risk analysis
risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test,
After that, the process of assigning the level of risk is done.


Why use Risk Analysis?
it helps the developers and managers to mitigate the risks.

possible risks that you could encounter? 
- Use of new hardware
- Use of new technology
- Use of new automation tool
- The sequence of code
- Availability of test resources for the application

how to tackle risks:
- Conduct Risk Assessment review meeting
- Use maximum resources to work on high-risk areas
- Create a Risk Assessment database for future use
- Identify and notice the risk magnitude indicators: high, medium, low.

**Risk Identification**
- Business Risks: (This risk is the most common risk associated with our topic. It is the risk that may come from your company or your customer, not from your project.)
- Testing Risks: (You should be well acquainted with the platform you are working on, along with the software testing tools being used.)
- Premature Release Risk: (a fair amount of knowledge to analyze the risk associated with releasing unsatisfactory or untested software is required)
- Software Risks: (You should be well versed with the risks associated with the software development process.)

**The perspective of Risk Assessment**
- Effect: (To assess risk by Effect. In case you identify a condition, event or action and try to determine its impact.)
- Cause: (To assess risk by Cause is opposite of by Effect. Initialize scanning the problem and reach to the point that could be the most probable reason behind that.)
- Likelihood: (To assess risk by Likelihood is to say that there is a probability that a requirement won’t be satisfied.)

**How to perform Risk Analysis?**
- Searching the risk
- Analyzing the impact of each individual risk
- Measures for the risk identified


## BIG O notation
equation how a run-time scale to an input

**O(1)**: time is constant with respect to the size of the input.

**O(n)**: depends on external restrictions to define the time needed

**4 rules to know**:
- two different steps <we should add them> O(A)+O(B)=O(A+B)
- drop contants
- different inputs = different variables
- drop non-dominate terms


