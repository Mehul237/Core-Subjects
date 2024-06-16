
## Intro

<hr>

![Screenshot_2024-06-16-00-48-46-68](https://github.com/Mehul237/Core-Subjects/assets/117193057/91d76cc7-2af5-4221-a967-3b46167bc2e7)

![Screenshot_2024-06-16-00-49-06-48](https://github.com/Mehul237/Core-Subjects/assets/117193057/5864dae5-28ea-4630-a595-2241879453ba)

<hr>
<br>

## 1. Object and Class

<hr>

![Screenshot_2024-06-16-00-55-08-15](https://github.com/Mehul237/Core-Subjects/assets/117193057/c8dfbcae-ab71-4187-87b0-f2d9f2b02a10)

![Screenshot_2024-06-16-00-55-27-56](https://github.com/Mehul237/Core-Subjects/assets/117193057/58881a3b-b1e1-43ec-97a2-d1d47476dc21)

![Screenshot_2024-06-16-00-58-31-84](https://github.com/Mehul237/Core-Subjects/assets/117193057/d66730ea-a54f-485e-80f3-1a56ee9a4a34)

![Screenshot_2024-06-16-00-58-50-87](https://github.com/Mehul237/Core-Subjects/assets/117193057/529bbb74-644f-46a0-919e-2971c36d44e9)

![Screenshot_2024-06-16-01-00-17-66](https://github.com/Mehul237/Core-Subjects/assets/117193057/5dc60fef-3217-4ef5-a905-9fcd95d8d828)

![Screenshot_2024-06-16-01-01-58-39](https://github.com/Mehul237/Core-Subjects/assets/117193057/0b14c36e-7739-4726-893f-bb64ce749a24)

![Screenshot_2024-06-16-01-02-54-56](https://github.com/Mehul237/Core-Subjects/assets/117193057/10950e51-34bf-4d81-8e84-a87590b84a6d)

![Screenshot_2024-06-16-01-03-04-39](https://github.com/Mehul237/Core-Subjects/assets/117193057/3d0b083d-d2dd-4b0b-b68d-79a8a3da5095)

### Hands-one Practice:

![Screenshot 2024-06-16 132434](https://github.com/Mehul237/Core-Subjects/assets/117193057/028f52ce-d3c7-4fe8-89cd-e53a329dc4fe)

![Screenshot 2024-06-16 132911](https://github.com/Mehul237/Core-Subjects/assets/117193057/31633936-40aa-451e-a95a-88b673ccaeac)

![Screenshot 2024-06-16 132920](https://github.com/Mehul237/Core-Subjects/assets/117193057/1a859313-dc2f-4369-8ab2-a9cb797ca5d3)

<hr>
<br>


## 2. Access Specifier

<hr>

![Screenshot 2024-06-16 133045](https://github.com/Mehul237/Core-Subjects/assets/117193057/04378e22-d044-457f-82e3-ae1dcf888616)

![Screenshot 2024-06-16 133437](https://github.com/Mehul237/Core-Subjects/assets/117193057/37c57207-dce4-4749-a643-e4217209028c)


### Protected: Inheritance concept used mostly

![Screenshot 2024-06-16 133843](https://github.com/Mehul237/Core-Subjects/assets/117193057/e59ccc8f-4ffa-4e18-9007-aad0f8d22df2)

![Screenshot 2024-06-16 135219](https://github.com/Mehul237/Core-Subjects/assets/117193057/ce13716b-fa5a-4393-be9c-a489bd101049)


### Code: Include 1st and 2nd

```cpp

#include <bits/stdc++.h>
using namespace std;

// 1. Class and Object
// 2. Access specifier


class Teacher {
private:
    double salary;
  
public:

    // Properties or attributes
    string name;
    string dept;
    string subject;

    // Methods (fn) also called member fn
    void changeDept(string newDept) {
        dept = newDept;
    }


    // Salary not accessed directly, but indiretly accessed through public method like setter and getter

    // Setter: Set the private attributes value
    void setSalary(double s) {
        salary = s;
    }

    // getter: get the private attributes value
    double getSalary() {
        return salary;
    }
};


int main() {

    // Object created, t1 (obj1)
    Teacher obj1;

    // Accessed and assigned value
    obj1.name = "Vinod valand";
    obj1.dept = "Computer Science";
    obj1.subject = "DSA, OOPS, OS, CN, DBMS";

// 1_Case: Public

    // obj1.salary = 150000;
    cout << "Name: "    << obj1.name << "\n";
    // cout << "Salary: "  << obj1.salary << "\n";
    cout << "Subject: " << obj1.subject << "\n";


// 2_Case: Privete
    obj1.setSalary(150000);
    cout << "Salary: "  << obj1.getSalary() << "\n";

}

```

<hr>
<br>
