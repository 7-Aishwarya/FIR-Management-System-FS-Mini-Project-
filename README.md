# FIR Management System using File Structures(Hashing Collison Resolution Using Bucketing)

Tech Stack - Python

A FIR Portal based on File Strutures Concepts:
- Collision Resolutions Using Bucketing.
- Variable Length Records
- Hash Key = Case Place

Key Functionalities:
- Login and Signup
- Registering FIR
- Searching for FIR
- Deleting FIR
- Displaying Contents Of Buckets


Insertion Of A Record:
- In this project ,hash address is generated for case place based on the addrees generated case place along with its fir no(firno|caseplace) occupy its home address in bucket file.
Bucket file is made up of 0 to 9 address spaces i.e 10 buckets. Each buckets can hold upto 5 records that is they are made up of 5 slots.When all slots get filled in corresponding bucket it leads in Bucket Overflow  due to collission and corresponding recording will not be inserted into that slot.


Deletion Of A Record:(Tombstones for handling deletion(####)):
- Whenever record is deleted its entry in bucketfile will also get deleted and it is replaced with #### indicating record is deleted a new record can be inserted into that slot.

Note: The format of FIR ID while registering should be 'F' followed by 3 digits. Ex: F123

<br><br>

How to RUN the project:
1. Install necessary library - Tkinter
2. RUN ```python InitMain.py```

<br><br>
Screenshots
<br>

<img src="https://github.com/7-Aishwarya/FIR-Management-System/assets/98330491/2b722a6e-3b61-4f34-bf12-887c7b53e576" >              
<img src = "https://github.com/7-Aishwarya/CNS-Lab-Programs-VTU-5th-Sem-/assets/98330491/cdbc29ef-7286-4d14-bd88-6487d3f78a3c"  >
<img src = "https://github.com/7-Aishwarya/FIR-Management-System/assets/98330491/226fed04-fe12-41fd-be6b-0b7705bbd022" >
<img src = "https://github.com/7-Aishwarya/FIR-Management-System/assets/98330491/5874345d-65f8-4fcb-8da0-48e7a2e5512f " >
<img src = "https://github.com/7-Aishwarya/FIR-Management-System/assets/98330491/2967c176-def8-401d-8975-a13d635d7241">
