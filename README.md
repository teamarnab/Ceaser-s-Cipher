PROGRAM: CEASER'S CIPHER (Python code)

PROBLEM STATEMENT
Write a python code for encryption or decryption of a given text
1. User would be able to enter the text.
2. For each letter in the user entered text the encrypted text should have the letter that is
   3 letters next to it and reverser for the decryption (the letter 3 letters ahead of the letter
   in the text).
3. Any space in user entered text should be replaced by "@" symbol in the encrypted text and "@" 
   symbol replaced by space in the decrypted text.
4. Print the encrypted or decrypted text


STEPS FOLLOWED
1. Create two lists one of English alphabets having the letters a - z and one of numbers having
   the numbers 0-9.
2. Written a program that will accept a text as an argument.
3. Created an empty variable to store the result (the encrypted/decrypted text).
4. A for loop to iterate through each letter and find if it's in alphabets list or numbers list
   or a space.
5. Added (in case of encryption) or substracted (in case of edecryption) the index number by 3 
   and added the letter in the empty variable which is in the new index.
6. returned the empty string which is now filled.
7. Created an input variable which will accept the text from the user to encrypt or decrypt.
8. Called the encryption / decryption function and passed on the input variable as an argument.
9. Printed the result.
