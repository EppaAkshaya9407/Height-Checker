# Height-Checker
heights=list(map(int,input("Enter heights:").split()))
expected=sorted(heights)
count=0
n=len(heights)
for i in range(n):
    if heights[i]!=expected[i]:
        count+=1
print("Output:",count)
