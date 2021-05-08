# menu
Create, insert, append, erase, reverse, and print.


include <iostream>
using namespace std;
int main() {
cout << " cout << " cout << " cout << " cout << " cout << " cout << "
1 - Create\n";
2 - Insert\n";
3 - Append\n";
4 - Erase\n";
5 - Reverse\n";
6 - Print\n";
Enter your choice and press return: ";
while (1)
{
int choice;
cin >> choice;
string string1 = "Object Oriented Programming"; if (choice == 1) // to print already ready text {
string string1 = " "; }
else if (choice == 2) {
string string2;
int stcla;
cout << "\n String: ";
cin >> string2;
cout << "\n Index: ";
cin >> stcla;
string1.insert(6, string2);
cout << "Final version : " << string1<<"\n" ;
}
else if (choice == 3) {
string string2;
cout << "\n String : ";
cin >> string2;
string1.append(string2);
cout << "\n After append : " << string1<<"\n"; }
else if (choice == 4)
{
int stcla;
cout << "\n After how many letters should be deleted:"; cin >> stcla;
string1.erase(stcla);
cout << "\n String after erase : " << string1<<"\n"; }
else if (choice == 5)
{
std::string::reverse_iterator reiterator;
cout << "\n Reverse : ";
for (reiterator = string1.rbegin(); reiterator != string1.rend(); reiterator++)
cout << *reiterator;
cout << endl;
}
else if (choice == 6)
{
std::string::iterator normiterator;
cout << "\n Normally: ";
for (normiterator = string1.begin(); normiterator != string1.end(); normiterator++)
cout << *normiterator;
cout << endl;
}
continue; }
cout << "\n Please enter the valid choice \n"; cout << "Choose again\n";
return 0; }
