# Spiral-search

The aim of this project is to practice on matrices (two dimensional arrays/vectors). You are asked to find the list of chars (i.e. strings) having a simple property and their locations in a 2D matrix via basic search mechanisms, extract information out of it and process that information.
In this project, you are going to implement a program that searches a given input matrix of characters and displays the words which satisfies a condition. 

Starting from any coordinate in the matrix, a word can go spirally. Hence, you are expected to search the input file checking all directions from clockwise and counter clockwise. For example: If you go up in the first step, you need to go right in the second step, then go down. If you go right in the first step, you will go down in the second and go left in the third step. You can see possible search locations below. You can assume the search words will contain at least 3 letters.

<img width="586" alt="Screenshot 2023-10-17 at 21 04 18" src="https://github.com/suleymanbrbr/Spiral-search/assets/111366311/71c75aba-dfe9-4ae5-8910-3799382b607b">
<img width="360" alt="Screenshot 2023-10-17 at 21 01 15" src="https://github.com/suleymanbrbr/Spiral-search/assets/111366311/c52e7836-50da-4c37-803a-d78b3dd1a91c">

Your program should perform input check and ask for new file name until an input file is found (ma- trix 4 2.board)
Your program should perform input check on input file. Input files should comply with those rules; – Matrix should be nxn and all rows must be equal size (matrix 4 2.board)
– Matrix cannot include any of these characters: [a-z], +, -, *, /, %, [0-9] (matrix 7 5.board) Number of words to search and number of found words could be different. (matrix 8 3.board)
Found words in the output don’t have to be sorted. But they should comply with the format: N Words are Found:(2 empty space) WORD1 WORD2 WORD3 WORD4
N is 4 in this case.

<img width="408" alt="Screenshot 2023-10-17 at 21 01 42" src="https://github.com/suleymanbrbr/Spiral-search/assets/111366311/823c6940-63cb-47fe-b65e-c9c4ac683d41">
