# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
    {
        alert("B Grade"); 
    }
    else
    {
        alert("RA Grade");
    }
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```


## OUTPUT
![Screenshot 2023-06-11 011242](https://github.com/Lillyjagan/Ex06_Web-Design/assets/128703180/553d2600-3815-439d-b798-8edd82b8baf6)
![Screenshot 2023-06-11 011431](https://github.com/Lillyjagan/Ex06_Web-Design/assets/128703180/503b5a8a-8cfc-43c4-8af2-f754cf974746)
![Screenshot 2023-06-11 011508](https://github.com/Lillyjagan/Ex06_Web-Design/assets/128703180/f66d3254-3cfd-4752-bf23-24726c97ad7a)
![Screenshot 2023-06-11 011554](https://github.com/Lillyjagan/Ex06_Web-Design/assets/128703180/9fa3f5fe-cb3f-4207-911d-d2bceb1c6b39)
![Screenshot 2023-06-11 011624](https://github.com/Lillyjagan/Ex06_Web-Design/assets/128703180/561eefc7-56a7-4637-bd49-6b44a32194ca)





## RESULT
  Student result using JavaScript is created successfully.
