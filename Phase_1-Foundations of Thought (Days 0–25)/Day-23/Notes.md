# Day 23 Notes — Advanced File Handling



## Why Read Line by Line?



* Saves memory for large files
* Allows processing as data streams
* Cleaner logic for text processing



---

## Reading Line by Line



Use a for loop on the file object.



Example:
with open("file.txt", "r") as file:
	for line in file:
		print(line.strip())



---

## Common Patterns



* strip() → remove newline \& spaces
* split() → break into words
* lower() → normalize text
* count / dictionary → frequency analysis



---

## Writing Processed Output



Open a new file in "w" or "a" mode and write results.



---

## Mental Rule



Read → Clean → Process → Write

