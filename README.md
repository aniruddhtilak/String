The program counts the number of characters in a user-entered string while ignoring spaces. 
It uses two different ways to declare character arrays (strings) and demonstrates string input and manipulation.                                                                                                        
                                                                                                                                                                                                                        
Algorithm :

1. Create two character arrays 'str1' and 'str2' to store strings, initialized with values.
2. Display 'str1' and 'str2' using cout.
3. Create a character array 'str3' of size 100 to store user input.
4. Display "Enter a string - ".
5. Read and store user input in 'str3' using cin.get().

6. Create a character pointer 'sptr' and initialize it to point to the first character of 'str3'.
7. Create integer variables 'counter' and 'a' and initialize 'a' to 0.

8. Use a 'while' loop with the condition 'a == 0':
   a. Inside the loop:
      i. Check if the character pointed to by 'sptr' is the null terminator ('\0'):
         - If yes, set 'a' to 1 to exit the loop.
         - If no, continue to the next step.
      ii. Check if the character pointed to by 'sptr' is not a space:
         - If yes, increment 'counter'.
      iii. Move 'sptr' to the next character in the string.

9. Display "Number of characters = " followed by the value of 'counter'.

10. End of the program.
