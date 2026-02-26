# ⌨️ Standard Keylogger

**By Rashid Iqbal | AI Red Teamer 🛡️**  
**Cyber Internship Project at ARCH Technologies**

A Python-based **Keylogger** to capture and log keystrokes in real time on your system using the `pynput` library. This project was completed as a practical lab and documented by me to demonstrate event-driven programming, input monitoring, and safe handling of sensitive data.

---

## 🎯 Objective

The main goals of this project were to:

1. Capture keyboard inputs in real time using Python 🐍  
2. Store captured keystrokes in persistent log files 📄  
3. Understand how keyboard input can be monitored programmatically ⌨️  
4. Learn proper handling of special keys and exceptions ⚠️  

---

## 🧠 Key Concepts Learned

### Pynput Library

- Allows Python to **monitor and control input devices** like keyboard and mouse 🖱️  
- `pynput.keyboard.Listener` detects key press events in real time  
- Helped me understand **Python interaction with hardware events**  

### Event-Driven Programming

- Program executes functions **in response to events** ⏱️  
- Defined a `keyPressed(key)` function triggered on every key press  
- Taught me how programs can **dynamically respond to user actions**  

### File Handling

- Captured keystrokes are saved in `keyfile.txt` 💾  
- Using `with open("keyfile.txt", 'a') as logKey:` ensures safe **automatic file handling**  
- Improved knowledge of **persistent storage and data logging**  

### Exception Handling

- Special keys like Shift, Ctrl, and Enter do not have direct character representation  
- Implemented `try-except` blocks to handle these gracefully  
- Showed importance of **robust error handling in real applications**  

---

## 🐍 Python Implementation

- Imported the **keyboard module** from `pynput`  
- Defined `keyPressed(key)` to capture keystrokes  
- Within this function:  
  - Attempted to write the character to the log file  
  - Non-character keys are caught to **avoid program interruption**  
- Created a **keyboard listener object**: `keyboard.Listener(on_press=keyPressed)`  
- Started the listener with `.start()` and kept the program running with `input()`  

This structure allows **continuous monitoring and logging of keyboard inputs**.

---

## 💡 Practical Use

This keylogger helps me:

- Understand **how input devices can be monitored programmatically** ⌨️  
- Capture and log sensitive events safely in a **controlled environment** 🛡️  
- Strengthen knowledge in **event-driven programming, file I/O, and exception handling**  
- Gain insight into **methods attackers might use to capture user input** and how **defensive programming** can prevent misuse  

---

## ✅ Conclusion

Exploring the hidden world of keyboard inputs taught me valuable skills and insights:

- Built a Keylogger to monitor and record keystrokes in real time ⌨️  
- Gained hands-on experience with **event-driven programming & input device monitoring**  
- Learned to **capture, log, and handle keystrokes safely** using Python  
- Developed a deeper understanding of **file handling and exception handling**  
- Strengthened knowledge in **Python programming, Cybersecurity, and Ethical Hacking** 🛡️  
- Prepared for **real-world tasks in input monitoring, automation, and security testing**  

---

## 👨‍💻 Author

**Name:** Rashid Iqbal  
**GitHub:** (https://github.com/NoxVesper)  
**📧 Email:** echoinject@gmail.com  

Suggestions for **improvements or bug reports** are highly appreciated! 📝  

---

⚠️ **Disclaimer:** This project is for **educational and ethical purposes only**. I only operate in environments where testing is permitted.
