## Given-two-Python-sets-update-first-set-with-items-that-exist-only-in-the-first-set-and-not-in-the-second set
## Sample code to check the details 
```sh
set1 = {10, 20, 30}
set2 = {20, 40, 50}

set1.difference_update(set2)
print(set1)
```
## Expected Output
set1 = {10, 30}

