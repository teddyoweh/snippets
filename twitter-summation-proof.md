#### [Twitter Post](https://twitter.com/pickover/status/1543376324110213121)
![image](https://pbs.twimg.com/media/FEwkB1iWYAg0E6b?format=jpg&name=small)

#### [My Reply](https://twitter.com/tedddyoweh/status/1543521339855835136)

Quick python code to prove statement

```py
def verify(m:int):
  # Validation Step.
  return solve1(m)==solve2(m)
       
def solve1(m:int):
  # Sums up all the cubes of the values in the range (m) (summation) 
  return sum([k**3 for k in range(m)]) 
        

def solve2(m:int):
  # Sums up all the values in the range (m)  (summation), the squares up the results 
  return sum([k for k in range(m)])**2 
     
# Testing 
print(verify(4)) # The output determines if the equation above is valid
```
