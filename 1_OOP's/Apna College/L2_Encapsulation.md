
## Important 4-pillar in OOP's

<hr>

![Screenshot 2024-06-16 135334](https://github.com/Mehul237/Core-Subjects/assets/117193057/b86b19d4-c935-4fd0-b9d4-2eb749620fba)

<hr>
<br>

## 1. Encapsulation

<hr>

![Screenshot 2024-06-16 161449](https://github.com/Mehul237/Core-Subjects/assets/117193057/a0ecba87-1f2e-4dae-8226-21514a3bc5c9)

![Screenshot 2024-06-16 161546](https://github.com/Mehul237/Core-Subjects/assets/117193057/53a3ac3a-d832-4feb-9427-a85f6a1f838b)

![Screenshot 2024-06-16 161624](https://github.com/Mehul237/Core-Subjects/assets/117193057/46cad30e-b86c-4123-bb0c-9ff29fddfa30)

![Screenshot 2024-06-16 161726](https://github.com/Mehul237/Core-Subjects/assets/117193057/daab28ac-a0c2-470b-92af-63250eb9e6aa)

![Screenshot 2024-06-16 161805](https://github.com/Mehul237/Core-Subjects/assets/117193057/e825f9ed-7a4e-4089-9394-512a09c18d93)

<hr>

> ### Important question,
>
> 1. What is encapsulation and give the example?
> 2. What is data hiding and give the example?
> 3. Type of access specifier, Implement with help of class and also show an example of private, public and protected (inheritance)?
>

<hr>
<br>

### 1. Constructor

![Screenshot 2024-06-16 161909](https://github.com/Mehul237/Core-Subjects/assets/117193057/3d5116fc-34dc-4f69-9a97-563118fb7f69)

![Screenshot 2024-06-16 163123](https://github.com/Mehul237/Core-Subjects/assets/117193057/66293ae0-0578-465e-861a-158fa82f0d31)

![Screenshot 2024-06-16 163134](https://github.com/Mehul237/Core-Subjects/assets/117193057/78ebe925-6d8c-4688-93c7-2497b2db1cb5)

![Screenshot 2024-06-16 163155](https://github.com/Mehul237/Core-Subjects/assets/117193057/1c5eb0d7-166a-40af-a1c9-19244282c995)

> So either programmer create the constructor or if the compiler create the constructor

<br>

![Screenshot 2024-06-16 163356](https://github.com/Mehul237/Core-Subjects/assets/117193057/6e5a9cc6-06a5-48f9-8322-995a691b5a93)

![Screenshot 2024-06-16 163606](https://github.com/Mehul237/Core-Subjects/assets/117193057/1a7c3c05-55b2-4851-b4d0-2e6c9e33aef3)

> The individual objects takes up space (occupies space) inside the memory

<br>

## Properties to build constructor

![Screenshot 2024-06-16 164855](https://github.com/Mehul237/Core-Subjects/assets/117193057/900a6136-cbbc-4050-be2d-cda9e0d3e3c0)

<img width="960" alt="Screenshot 2024-06-16 165531" src="https://github.com/Mehul237/Core-Subjects/assets/117193057/068ff9d6-310a-4d08-9952-408f4568a231">

![Screenshot 2024-06-16 165748](https://github.com/Mehul237/Core-Subjects/assets/117193057/52cfa0a7-4d80-44be-92bb-167b29b8957f)

> Constructor called again and again, If it happens then he will repeat this same line many times to be printed

<br>

![Screenshot 2024-06-16 171200](https://github.com/Mehul237/Core-Subjects/assets/117193057/c32512a5-f33e-41b0-995c-ca2b28c52c49)

![Screenshot 2024-06-16 171153](https://github.com/Mehul237/Core-Subjects/assets/117193057/3ad2684d-9626-4d19-883e-a61599122de0)

> ### Above two image,
> What do you mean by initialisation?
> - You can already set/Assign values for data members
> - <i> Image-1 </i>: Department ki value computer science ho jaye har aek teacher ke liye
> - <i> Image-2 </i>: To us value ko bar-bar hame ja kar set nahi krna padega, Vo automatically jesi hi object create hoga department computer science ho jayega
>
> ### Constructor function called only ones when object is created
> - We don't have to do extra work for call constructor because call get automatically
> - Generally, Constructor function inside the public because get call from the main class and have a access to public
>

<br>

![Screenshot 2024-06-16 173104](https://github.com/Mehul237/Core-Subjects/assets/117193057/4fe5b8b5-796b-463f-8565-28a5bfb26a51)

![Screenshot 2024-06-16 173123](https://github.com/Mehul237/Core-Subjects/assets/117193057/f801b362-ad10-438d-8505-be5ca6d90e39)

> <i> Note </i>:
> - Memory allocation happens for only object, not classes
>

<br>

## Types of constructor

![Screenshot 2024-06-16 174115](https://github.com/Mehul237/Core-Subjects/assets/117193057/1aec6cf7-aaf8-42dc-9de6-d6b53c0ee4d5)

> ## Summary:
>  1. Non-parameterized: Not having the parameter
>  2. Parameterized: having the parameter

<br>

<img width="960" alt="Screenshot 2024-06-16 175335" src="https://github.com/Mehul237/Core-Subjects/assets/117193057/c4712632-4f16-4053-9751-fe78c1cf4bab">

<img width="960" alt="Screenshot 2024-06-16 175557" src="https://github.com/Mehul237/Core-Subjects/assets/117193057/8489a7ef-7c4e-44df-81c3-abf146195ff9">


```cpp

#include <bits/stdc++.h>
using namespace std;

class Teacher {
private:
    double salary;  
public:
    
    // 1_Non-parameterized
    // Teacher() {
    //     cout << "Hi, I am constructor\n";
    // }


    // 2_Parameterized, 4-parameter
    Teacher(string n, string d, string s, double sal) {
        name = n;
        dept = d;
        subject = s;
        salary = sal;
    }
 
    string name;
    string dept;
    string subject;

    void changeDept(string newDept) {
        dept = newDept;
    }

    void getInfo() {
        cout << "Name: " << name << "\n";
        cout << "Department: " << dept << "\n";
        cout << "Subject: " << subject << "\n";
        cout << "Salary: " << salary << "\n";
    }
};


int main() {
    Teacher t1("Vinod Valand", "CSE", "OOPs, OS, CN, DBMS", 150000);
    t1.getInfo();
    
    return 0;
}

```

<br>


### Why you comment the teacher constructor which not having the parameter?

<hr>

![Screenshot 2024-06-16 175905](https://github.com/Mehul237/Core-Subjects/assets/117193057/23d1dfee-2cc7-4d72-8feb-3fc24c4b1dad)
> Same constructor name but different parameter

![Screenshot 2024-06-16 175923](https://github.com/Mehul237/Core-Subjects/assets/117193057/f06737fc-b1b4-40ba-81d9-1f780cb9c176)
> When a execution happens then according to parameter give the output

![Screenshot 2024-06-16 180906](https://github.com/Mehul237/Core-Subjects/assets/117193057/f7392ac9-9fc5-4ae5-bd3c-acfa07c6aba0)
> We can have multiple parameters, Their name may be same but their type are different to this phenomenon we call Constructor Overloading (Polymorphism)

<hr>
<br>

## This 

<br>
