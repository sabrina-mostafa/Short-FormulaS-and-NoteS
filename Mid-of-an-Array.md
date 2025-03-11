![Screenshot 2025-03-11 161726](https://github.com/user-attachments/assets/8ad17699-1993-4368-ad1f-1aa28c1f22b3)


<br/>

## If the range is **O<=M<20** and we have to find mid of **(16, 18)**
    then, 
    for (L+R)/2
       => (16+18)/2
       => (34)/2   here, **34** is a **overflow*** bcz 0<=M<20
<br/>

     But for (L + (R-L)/2)
            => (16 + (18-16)/2)
            => (16 + 2/2)
            => (16 + 1)
            => 17  valid ans without overflow.

# So we should use the formula, M = (L +(R-L)2) to find mid of a range to avoid overflow.
