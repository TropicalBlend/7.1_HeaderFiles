# 7.1_HeaderFiles
7.1_HeaderFiles

#include <LIST0701.h>
using namespace std;

Cat::Cat(int inistialAge)	//constructor
{
	itsAge = initialAge;
}

Cat::~Cat()					//destructor, takes no action
{
}

//create a cat, set its age, have it
//meow, tell us its age, then meow again.
int main()
{
	Cat Frisky(5);
	Frisky.Meow();
	cout << "frisky is a cat who is ";
	cout << Frisky.GetAge() << " years old.\n";
	Frisky.Meow();
	Frisky > SetAge(7);
	cout << "Now Frisky is ";
	cout << Frisky.GetAge() << " years old.\n";
	
	system("pause");
	return 0;
}
