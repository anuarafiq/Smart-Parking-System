# Smart Parking System
A command-line based Smart Parking System developed in C++ to manage parking slots efficiently for students and staff.
_ _ _

# Project Description
This is a console-based Smart Parking System developed using C++ as part of the **TEB1013 Structured Programming** course at Universiti Teknologi PETRONAS (UTP). The system is designed to manage parking slots efficiently for students and staff, featuring ID-based access, real-time slot updates and a stylized text UI for showcasing the parking availability.
_ _ _

# Features
- **Slot Availability Check** – Only allows entry if a slot is available
- **Real-Time Grid Display** – Visual layout with slots `P1` to `P16` (4x4)
- **User ID-Based Entry/Exit** – Prevents double entries; tracks usage
- **Stylized CLI Interface** – Clear and user-friendly text-based design
- **Input Validation** – Prevents invalid or duplicate operations
_ _ _

# C++ Concepts Used
- `struct` – to store user and slot details  
- `array` – 2D array to represent parking grid  
- `functions` – modular structure with reusable logic  
- `vector` – dynamic storage of users  
- `text formatting` – for clear UI presentation  
_ _ _

# How it looks

```
+=============================================+
|           SMART PARKING SYSTEM              |
+=============================================+

      +------+------+------+------+------+
      | P 1  | P 2  | P 3  | P 4  | P 5  | 
      |   O  |   O  |   O  |   O  |   O  | 
      +------+------+------+------+------+
      | P 6  | P 7  | P 8  | P 9  | P10  | 
      |   O  |   O  |   O  |   O  |   O  | 
      +------+------+------+------+------+
      | P11  | P12  | P13  | P14  | P15  | 
      |   O  |   O  |   O  |   O  |   O  | 
      +------+------+------+------+------+
      | P16  | P17  | P18  | P19  | P20  | 
      |   O  |   O  |   O  |   O  |   O  | 
      +------+------+------+------+------+
      | P21  | P22  | P23  | P24  | P25  | 
      |   O  |   O  |   O  |   O  |   O  | 
      +------+------+------+------+------+

Legend: O = Available | X = Occupied
===============================================

--- Smart Parking System ---
1 Enter Parking
2 Exit Parking
3 View Parked Users
4 Search User Parking Info
5 View Slot Summary
99 Exit Program

Enter choice: 
```

_ _ _

# Future Development Ideas 
- Admin mode with password
- Parking fee calculation (based on duration)
- RFID or barcode scanner simulation
- Load/save data on program restart
_ _ _

# Developed By
**Kheshwenda Narasimban**  
**Anuar Afiq bin Arfahairy**  
Bachelor of Computer Science  
Universiti Teknologi PETRONAS (UTP)  
_ _ _

# License
This project is created for academic and educational purposes.

