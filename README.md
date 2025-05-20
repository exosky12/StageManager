# 🗂️ StageManager

StageManager is a command-line internship management system developed as part of a school project.  
It allows students to apply for internships, supervisors to create them, and juries to assign grades.

> ⚠️ WARNING  
> Due to the use of `scanf`, **do not add a newline at the end of the `data_stage.txt` file**.  
> Otherwise, the program may misinterpret leftover lines and store incorrect values due to buffer issues.

✅ Example of a valid line:  
5008 63 1 638 1061 03 0 0 2548 63 0 1 517 3040 04 1 517

📌 Known limitations:  
- `scanf` should be replaced by `fgets` for more robust input handling  
- No format validation: incorrect lines in `data_stage.txt` may break execution

## 💡 Features

- Students can apply for internships
- Internship supervisors can add internship offers
- Juries can assign grades to students

## 🛠 Compilation

To build and run the program:
```
gcc -o stagemanager main.c  
./stagemanager
```

(Adjust the filename if necessary.)

## 🏫 Context

This project was completed as part of a C programming assignment.  
It focuses on file I/O, memory management, and procedural logic in a command-line interface.

## 📬 Contact


Email: julesmerienne06@gmail.com <br>
Twitter/X: https://x.com/exosky12_
