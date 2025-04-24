# Using-tools-like-John-the-Ripper-for-password-cracking
Nmae:Vimala Rani A

Reg No:212223040240
## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).


### Step 3:
Use John the Ripper to crack the hashes:

## PROGRAM:
Password Cracking with John the Ripper

## OUTPUT:
- Create an txt file 
![Screenshot 2025-04-24 235028](https://github.com/user-attachments/assets/376084e9-7106-40e4-8973-6e4bc0dd8576)


-  Create a Password-Protected ZIP File 
![Screenshot 2025-04-24 235048](https://github.com/user-attachments/assets/eef56d1e-ba40-4ce6-b06f-e7820d086cbe)


### OR

zip -e secret.zip file.txt


- Open John-The-Ripper Tool
- 
![Screenshot 2025-04-24 235105](https://github.com/user-attachments/assets/8611b3ae-5915-4e0c-9052-0ad153733852)


![Screenshot 2025-04-24 235117](https://github.com/user-attachments/assets/30147e33-b472-45b3-be44-abe534c57e70)


- Generate Hash Using zip2john
 
![Screenshot 2025-04-24 235128](https://github.com/user-attachments/assets/2a01f6e0-4b11-4518-82c8-3045fcedf2a4)

- cat hash.txt

![Screenshot 2025-04-24 235139](https://github.com/user-attachments/assets/f3eff3a5-a989-49dd-a615-e5e07b6deb69)


![Screenshot 2025-04-24 235147](https://github.com/user-attachments/assets/5492dbda-7419-4c8d-89b2-086abdcb7ebb)



## RESULT:
The password hashes were successfully cracked using John the Ripper.
