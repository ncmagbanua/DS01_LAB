#include <iostream>
#include <stack>
#include <vector>
#include <string>
using namespace std;

int main()
{
    string mystring;
    int openbracescounter = 0;
    int closebracescounter = 0;
    stack<int, vector<int>> iStack;

    cout << "Enter a string of braces: ";
    cin >> mystring;

    for (int x = 0; x < mystring.size(); x++)
    {
        cout << "Pushing " << mystring[x] << endl;
        char currentChar = mystring[x];
        
        if (currentChar == '{'){
            cout<<" open brace:" <<endl;
            openbracescounter++;
        }
        else if (currentChar == '}')
        {
            cout<<" close brace:" <<endl;
            closebracescounter++;
        }
        iStack.push(mystring[x]);
    }
    int nx = openbracescounter - closebracescounter;
    cout<<"Open Braces:"<< openbracescounter << endl;
    cout<<"Close braces:" << closebracescounter <<endl;
    cout << "Minimum number of replacements: " << nx << endl;
}
