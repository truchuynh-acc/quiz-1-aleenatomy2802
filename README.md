[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Aleena Tomy
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>
using namespace std;
class Car {
public:
    
    string model;
    int year;
    string color;

    // Setters
    void set_model(string new_model) {
        model = new_model;
    }

    void set_year(int new_year) {
        year = new_year;
    }

    void set_color(string new_color) {
        color = new_color;
    }

    // Getters
    string get_model() {
        return model;
    }

    int get_year() {
        return year;
    }

    string get_color() {
        return color;
    }



    void display_details() {
        cout << "Model: " << model << ", Year: " << year << ", Color: " << color << endl;
    }
};

int main() {
    Car myCar;
    myCar.model = "Toyota Camry";
    myCar.year = 2011;
    myCar.color = "Blue";


    myCar.display_details();

    return 0;
}

```
