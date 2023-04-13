#include <iostream>
using namespace std;

class Person {
  private:
    string name;
    int age;
  
  public:
    // Constructor
    Person(string n, int a) {
      name = n;
      age = a;
    }
  
    // Public methods
    void introduce() {
      cout << "Hi, my name is " << name << " and I am " << age << " years old." << endl;
    }
};

int main() {
  // Create a Person object
  Person person1("John", 30);
  
  // Call the introduce method
  person1.introduce();
  
  return 0;
}
