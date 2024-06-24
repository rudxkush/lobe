#include <iostream>
using namespace std;

int main()
{
    char love[20];
    int lob;
    
    cout << "What is her name? :)\n";
    cin.getline(love, 20);
    
    cout << "Do you love her?\n";
    cout << "If yes, enter 1. Otherwise, enter 0: ";
    cin >> lob;
    
    while (lob == 0 && lob != 1)
    {
         cout << "Always meant to be my " << love;
    }

    if (lob == 1)
    {
    cout << "Bhagwan meri kardo " << love;   
    }
    else
    {
        cout << "Bhagwan barbhaad kardo " << love;
    }
    
    return 0;
}


