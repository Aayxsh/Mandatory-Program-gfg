# Password-Generator-Program
a code to make a randomized password with symbols, letters, numbers.
1. Declare numbers,symbol, and letters as lists. 
2. Take numerical input from user for the required output. 
3. Create an empty list which will later be used. 
4. Using for loop, we can pick "n" number of characters for number,symbol and letters. We use the random.choice function to pick these characters at random and add to the empty list.
5. NOTE: Since the first element of the list is considered to be at position 0, we need the higher range to be x+1, x being the higher range in the for loop.
6. Once we get the empty list filled with the numbers,symbols and letters we use the shuffle function to shuffle these elements of the list. 
7. Make a new empty string and then add in the list with the help of for loop.
