# lobe
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
    
    while (lob != 0 && lob != 1)
    {
        cout << "Invalid input. Please enter 0 or 1: ";
        cin >> lob;
    }
    
    if (lob == 1)
    {
        cout << "Always meant to be my " << love;
    }
    else
    {
        cout << "Bhagwan meri kardo " << love;
    }
    
    return 0;
}

