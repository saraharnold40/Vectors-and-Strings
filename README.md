# Vectors-and-Strings
/*Read first / next character and loop until no more characters in the buffer
if character is a symbol; that is, a space, newline, or one of ., !? -;
if the word length is not zero(that is, if this symbol ends a word)
Increment word count
If word length is greater than the maximum word length
Replace maximum length with word length
Reset word length to zero
else
Increment character count
Increment word length
Output word count
Output average word length(calculate this using word and character counts)
Output maximum word length*/


#include <iostream>

#include <vector>

#include <string>

using namespace std;

int main() 
{
    vector <char> passage;

    char current;


    cout << “Please enter all your sentences below (hit enter when finished) :” << endl;

    while (cin.get(current)) 
