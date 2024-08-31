## [PROBLEM 1 - Alphabet Soup Problem] <br>
<h3>Description and thought process</h3><br>
The Alphabet Soup program is a program that lets the user input any string, and the program will sort the input <br>
in alphabetical order. <br> <br>

To solve this problem, we have to use the function ".isalpha()" because it checks if the character in the string is  <br>
part of the alphabet or not. It will only include all the alphabet characters in the string before proceeding with <br>
the program. This must be done for every character in the string thus, I put it in a for loop. Next is to sort the <br>
alphabet characters in alphabetical order, thus using the "sorted()" function. However, using this function alone <br>
will result in a listed output, hence we use the ".join()" function, which connects all the elements in the list <br>
together in one single string. Finally, we need to display the output using the "print" function <br><br>

### [ADDITIONAL CODES] <br><br>

To ensure that the sorting process and its output go as smoothly and as cleanly as possible, I've added a few lines <br>
of commands in the code. Starting with the ".lower()" command, which turns all the string values to lowercases if <br>
if possible. This is because of the nature of capitalized and lowercase letters having different values hence, <br>
disrupting the flow of the sorting of the string. <br>

![image](https://github.com/user-attachments/assets/f88994b6-d11c-4cd4-8ec7-c20c7e7fddb2) <br>

Next is the ".strip()" command, which removes all the white spaces from the left and the right of the program <br>

![image](https://github.com/user-attachments/assets/c6e018d7-2291-40af-bfba-b260da093c91) <br><br>



## [PROBLEM 2 - Emoticon Problem] <br>
<h3>Description and thought process - to be added </h3><br>
This emoticon program lets the user input any string and converts words into their corresponding emoticons if any <br>
for instance, the word "smile" will be converted to ":)" in the output string. This test program covers four (4) <br>
different emoticons, namely, smile, grin, sad, and mad. <br><br>

To create this program, input from the user is first asked. The program will then split the string into different <br>
elements using the ".split()" function. This function allows the program to split the words and put them in a list <br>
so that each word can be checked individually later on in the program. <br><br>

After splitting, the program must first have <br>
a list of keys and values to refer to when a certain string matches with the condition to convert to an emoticon. <br>
This is where a dictionary function can be used. Enclosed in curly braces are the "key" words and their corresponding <br>
values as shown in the image. <br><br>

![image](https://github.com/user-attachments/assets/ddf82812-48e5-4a94-8869-fd34113dd9cb) <br><br>

Finally, before the output string, the program checks if any of the individual strings match with any of the keys <br>
in the dictionary. To achieve this, the program runs a for loop through all the individual strings before displaying <br>
the output. 

![image](https://github.com/user-attachments/assets/11f0bcc6-fc70-4258-b8a8-c0dcc66b7b47) <br><br>


## [PROBLEM 3 - Unpacking List Problem] <br>
<h3> Description and thought process </h3><br><br>

The unpacking list program is a program that "unpacks" a list of elements into three different groups: first, <br>
middle, and last. In other terms, it separates the first and last elements from all of the elements in between. <br><br>

![image](https://github.com/user-attachments/assets/1c173ae4-c863-42ec-b75c-73fa909f1853) <br><br>

Since we can assign a variable name to each of the element's respective indexes, creating the program is easy. <br>
all we have to do is assign a variable name for the first element, middle element, and last element. However, <br>
We need the middle element variable name to encompass all the elements between the first and last. To achieve <br>
this, we must put an asterisk (*) in front of the variable name. This asterisk essentially tells the variable <br>
name to include all the elements in front of it, starting from its current index until another variable name <br>
stops it, or there are no more elements to include. <br><br>

![image](https://github.com/user-attachments/assets/1083ae89-0777-4f49-9242-b43d41d3c8b9) <br><br>

And that's a wrap! This is the end of my repository on our programming assignment 1. If you have any feedback <br>
tips and tricks, and suggestions to improve my coding efficiency; please do tell me! Thank you once again!




