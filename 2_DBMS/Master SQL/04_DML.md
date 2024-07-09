## Data Manipulation Language

### 1. Insert

<hr>
<br>

### 2. Update
    Syntax: 
    1. UPDATE table-name SET col1 = 1, col2 = ‘abc’ WHERE id = 1;
    2. UPDATE student SET standard = standard + 1;                 // All row will be updated
<hr>

    1_Only for single updation with WHERE
![Screenshot 2024-07-09 184915](https://github.com/Mehul237/Core-Subjects/assets/117193057/d8eb28e1-6b80-4269-8b7d-4461bc2f5722)

    2_Update multiple ROWS
![Screenshot 2024-07-09 185829](https://github.com/Mehul237/Core-Subjects/assets/117193057/a3950265-f91f-49e6-9756-28cf3e4c5f23)

<hr>
<br>

### 3. Delete
    Syntax:
    1. DELETE FROM table-name WHERE id = 1;
    2. DELETE FROM table-name;              // All rows will be deleted

<hr>

    1_Only for single Delete
![Screenshot 2024-07-09 190456](https://github.com/Mehul237/Core-Subjects/assets/117193057/01749b58-a746-4bdd-b767-f32248ab9d79)

    2_Delete table (All row will be deleted)

![Screenshot 2024-07-09 190549](https://github.com/Mehul237/Core-Subjects/assets/117193057/322a2f9c-bd3d-4706-9a9e-45aebba82316)

<hr>
<br>

### 4. Replace

<hr>

![Screenshot 2024-07-09 235842](https://github.com/Mehul237/Core-Subjects/assets/117193057/7b678bb2-1d0d-46cc-8c6e-49cb9ffb5a44)

     CASE-01: Data already present then behave like REPLACEMENT, Only given data change and other set NULL col

![Screenshot 2024-07-09 235941](https://github.com/Mehul237/Core-Subjects/assets/117193057/759bbc1e-d013-4145-af4a-3fcd6194a5c9)

![Screenshot 2024-07-09 235952](https://github.com/Mehul237/Core-Subjects/assets/117193057/07a4eb97-406f-4df9-91f3-361cb0e93803)

     CASE-02: Data NOT present then behave like INSERT, Also having different(3) way to implement

![Screenshot 2024-07-10 000423](https://github.com/Mehul237/Core-Subjects/assets/117193057/ac0fd338-2ce7-42f8-8823-93177f0bd2ae)

![Screenshot 2024-07-10 000747](https://github.com/Mehul237/Core-Subjects/assets/117193057/a8369f8b-e3b4-43b5-8eb0-e5651578b629)

![Screenshot 2024-07-10 000912](https://github.com/Mehul237/Core-Subjects/assets/117193057/271ffd98-394d-465f-a439-71c97c4fd0cd)

![Screenshot 2024-07-10 001101](https://github.com/Mehul237/Core-Subjects/assets/117193057/9d9d0669-cb83-4407-86aa-c803b7d40fa4)

- In case of replace, If data already present then replace. If data is not present then insert
- In case of Update, If data already present then update work and if data is not present then update don't do anything

![Screenshot 2024-07-10 001721](https://github.com/Mehul237/Core-Subjects/assets/117193057/fe42b0f7-44f0-4264-bb47-e6e1b8b789f5)
    
<hr>
