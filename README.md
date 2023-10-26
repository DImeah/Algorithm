# An Algorithm that reads a sentence, which ends with a point, character by character, and determines:
1. The length of the sentence (the number of characters).
2. The number of words in the sentence (assuming that the words are separated by a single space).
3. The number of vowels in the sentence

# Conditions and Assumptions
1. Each character was treated separately.
2. The last character is a point.
3. Three variables was used as counters.

# Implementation
1. Lines 1 - 2 declares the name of the algorithm and the input "sentence" a string that it recieves.
2. Lines 3 - 6 declares variables for the counters and the sentence.
3. Lines 7 "begins" the logic.
4. Lines 8 reads the sentence parsed into the function and stores it into the empty string variable sentence.
5. Lines 10 checks if the last index of the string has a point and breaks if it does not at lines 41.
6. Lines 12 uses a while do loop to loop through the lenth of sentence (each character).
7. Lines 14 checks if the character the loop is currently is a space.
8. Lines 15 increments space_counter if the character checked in lines 14 has a space
9. Lines 16 breaks out of lines 14 if the condition is not met.
10. Lines 17 increments char_counter if the condition in lines 14 is not met.
11. Lines 18 ends the if statement from lines 14.
12. Lines 21 - 26 checks the current character if it is a vowel ("a", "A", "e", "E", "i", "I", "o", "O", "u", "U".
13. Lines 27 increaments the vowel_couunter if the switch case statement picks up a vowel.
14. Lines 28 end the switch statement.
15. Lines 30 increaments i (sentence length) being parsed as index for the while do loop.
16. Lines 31 ends the while do loop.
17. Lines 33 word_counter(number of words) is created by adding 1 to the spcae_counter (spaces counted).
18. Lines 34 total number of charcters is determined by adding the char_counter to the spcae_counter
19. Lines 37 - 39 writes out the total character, words and vowel counted.
