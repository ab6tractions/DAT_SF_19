#Homework 1 - Instructions

Using chipotle.tsv in the data subdirectory:
Look at the head and the tail, and think for a minute about how the data is structured. What do you think each column means? What do you think each row means? Tell me! (If you're unsure, look at more of the file contents.)

1. How many orders do there appear to be?
	* 1834
2. How many lines are in the file?
	* 4623
3. Which burrito is more popular, steak or chicken?
	* Chicken
		* __553 Chicken Burrito__
		* 368 Steak Burrito
4. Do chicken burritos more often have black beans or pinto beans?
	* Black Beans
		* __148 Black Beans__
		* 99 Pinto Beans

5. Make a list of all of the CSV or TSV files in the DAT7 repo (using a single command). Think about how wildcard characters can help you with this task.
	* `find -path . -name *.?sv 
6. Count the number of occurrences of the word 'dictionary' (regardless of case) across all files in the DAT7 repo.
	* `grep -ir dictionary ./DAT_SF_19-master
7. Optional: Use the the command line to discover something "interesting" about the Chipotle data. The advanced commands below may be helpful to you!
	* started on this, attempting to find the "soda / water orders" ratio for those who ordered veggie main dish vs. meat-based main dish.  Ran into some command line limitations.