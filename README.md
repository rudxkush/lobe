# lobe
#include <iostream>
using namespace std;

int main()
{
  char love[20];
  int lob;
  cout << "what is her name...:)\n";
  cin.getline(love,20);
  cout <<"do you love her\n";
  cout <<"if yes put 1 else put 0";
  cin >>lob;
  while(!lob)
  {
  if(lob==1)
  {
  cout<<"alwys meant to be my "<<love;
  }
  else if(lob==0);
  {
  cout<<"bhagwan meri kardo "<<love;
  }
 }
}
