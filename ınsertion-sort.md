# Insertion Sort Project

[![image](https://www.linkpicture.com/q/insertion.png)](![[image](https://www.linkpicture.com/q/insertion.png)])

###  1. çözüm
array
[22, 27, 16, 2, 18, 6] --> n

**22** | 27 16 12 18 6 --> n-1

**22** **27** | 16 12 18 6 --> n-2

**16** **22** **27** | 12 18 6 --> n-3

**12** **16** **22** **27** | 18 6 --> n-4

**12** **16** **18** **22** **27** | 6 --> 1

**6**  **12** **16** **18** **22** **27**  --> sorted array

###  2.çözüm

T(n) = n + (n-1) + (n-2)+....+ 1 = n*(n+1)/2
Time Complexity --> O(n^2)

###  3.Çözüm

Worst Case: O(n^2)
Avarage Case: O(n^2)
Best Case: O(n)

###  4.çözüm

18 sayısı Avarage Case kapsamına girer.

### 5.çözüm
[7,3,5,8,2,9,4,15,6]

İlk 4 adımı

**7** | 3 5 8 2 9 4 15 6 
**3** **7** | 5 8 2 9 4 15 6
**3** **5** **7** | 8 2 9 4 15 6
**3** **5** **7** **8** | 2 9 4 15 6

