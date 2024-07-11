
## Set 
- Used to combine multiple select statements
- Contain only unique value (Always gives distinct rows)

<hr>

### Set Operation
- Union
- Intersection
- Minus
- Only apply on ROWS (Join -- Columnwise)
  
![Screenshot 2024-07-12 004332](https://github.com/user-attachments/assets/982e61a8-6fc6-4cb1-b0b8-5d2fc529ee9f)

<hr>
<br>

### 1. Union

![Screenshot 2024-07-12 003202](https://github.com/user-attachments/assets/a272b08b-b7f7-4378-83d2-fb3d7e143e12)

      Full Join V/S Union
      
![Screenshot 2024-07-12 003629](https://github.com/user-attachments/assets/d0712c65-0f33-4586-b038-d8e64b104c25)

- In case of Union: Row increase
- In case of Full Join: Column increase

<hr>
<br>

### 2. Intersect
- Using INNER JOIN implement
- Returns common values of the tables

<img width="960" alt="Screenshot 2024-07-12 005309" src="https://github.com/user-attachments/assets/68236f6a-9869-4f84-ba56-80cb4bb53864">

<hr>
<br>

### 3. Minus
- Using LEFT JOIN implement
- returns the distinct row from the first table that does not occur in the second table

![Screenshot 2024-07-12 010105](https://github.com/user-attachments/assets/7e202365-6b83-4615-afe7-1e64e1062acd)

<hr>
<br>

    RECAP,
![Screenshot 2024-07-12 005935](https://github.com/user-attachments/assets/b242ae1f-f476-4050-874f-48c1a6ab5647)

<hr>
<br>
<br>


## Practice question from above concept

<hr>

![Screenshot 2024-07-12 014757](https://github.com/user-attachments/assets/1bcfae8f-c800-4c89-9f03-d0b8ba25bfa5)

<hr>
<br>

     1_UNION
![Screenshot 2024-07-12 014932](https://github.com/user-attachments/assets/cba5b04e-1869-41a9-b8ff-777140e90a04)

    
![Screenshot 2024-07-12 015021](https://github.com/user-attachments/assets/d411a97c-78ea-402b-bdfd-3122d650817c)

    2_INTERSECT -- 1st: Column increase, 2nd: row same according to table

![Screenshot 2024-07-12 015208](https://github.com/user-attachments/assets/a4fcf0c7-81bf-4d30-b76c-47b19ec048a1)

![Screenshot 2024-07-12 015228](https://github.com/user-attachments/assets/e7e8c12f-da01-4d87-a554-e135a9f25d6a)

    3_Minus

![Screenshot 2024-07-12 015511](https://github.com/user-attachments/assets/3dce634a-29a5-4a41-b179-7a8471d4511a)

<hr>
