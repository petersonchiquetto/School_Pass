## 🏫 School_Pass  

**School_Pass** is a simple Python application to calculate a student's final grade and determine whether they passed, are in recovery, or failed based on the entered grades.  

---

### 📌 Features  
✅ Calculates the average of three grades entered by the user.  
✅ Classifies the student as **Passed**, **Recovery**, or **Failed**.  
✅ Simple, fast, and efficient.  

---

### 🚀 How to Run  

1. Make sure you have **Python** installed on your machine.  
2. Clone or download this repository:  

   ```sh
   git clone https://github.com/your-username/School_Pass.git
   cd School_Pass
   ```

3. Run the script:  

   ```sh
   python school_pass.py
   ```

4. Enter the three grades when prompted.  
5. The result will be displayed on the screen.  

---

### 📜 Example Usage  

```sh
Enter the first grade: 8.0  
Enter the second grade: 6.5  
Enter the third grade: 7.2  
Passed  
```

---

### 📄 Code  

```python
nota1 = float(input("Enter the first grade: "))
nota2 = float(input("Enter the second grade: "))
nota3 = float(input("Enter the third grade: "))

average = (nota1 + nota2 + nota3) / 3

if average >= 7:
    print("Passed")
elif 5 <= average < 7:
    print("Recovery")
else:
    print("Failed")
```

---

### 📌 Future Improvements  

🔹 Add support for more than three grades.  
🔹 Allow for weighted grades.  
🔹 Create a graphical user interface (GUI).  

---
