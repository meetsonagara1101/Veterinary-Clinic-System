# Veterinary Clinic Management System

## Overview
The Veterinary Clinic Management System is a command-line-based application designed to manage patient records and appointments for a veterinary clinic. It allows clinic staff to efficiently handle patient information, search records, schedule appointments, and manage data in an organized manner.

## Features
### **Patient Management**
- View all patient records
- Search patients by ID or phone number
- Add new patients (with validation checks)
- Edit patient details (name and contact information)
- Remove patient records (with confirmation prompts)

### **Appointment Management**
- View all scheduled appointments
- View appointments by date
- Add new appointments
- Remove existing appointments

## System Requirements
- Operating System: Windows/Linux/MacOS
- Compiler: GCC (if using C/C++) or Python Interpreter (if using Python)
- Terminal or Command Prompt for execution

## How to Use
1. **Start the application**: Run the executable or script from the terminal.
2. **Main Menu**:
   - Select `1` for Patient Management
   - Select `2` for Appointment Management
   - Select `0` to Exit
3. **Patient Management Menu**:
   - Choose options to view, search, add, edit, or remove patients.
   - Follow prompts to enter required data.
   - Validation checks ensure proper input.
4. **Appointment Management Menu**:
   - Choose to view all appointments or filter by date.
   - Add or remove appointments as needed.

## Error Handling
- The system provides error messages for incorrect inputs.
- Data validation ensures proper entry of phone numbers and patient names.
- Confirmations are required for critical operations like deletion.

## Example Outputs
- **Viewing Patients:**
  ```
  Pat.# Name            Phone#
  ----- --------------- --------------------
  01024 Shaggy Yanson   (304)800-5191 (CELL)
  01032 Pugsley Yanson  (304)800-5191 (CELL)
  ```
- **Searching by Patient Number:**
  ```
  Search by patient number: 1088
  Name  : Potato Yards
  Number: 01088
  Phone : (583)678-8577 (HOME)
  ```
- **Viewing Appointments:**
  ```
  Date       Time  Pat.# Name            Phone#
  ---------- ----- ----- --------------- --------------------
  2024-02-29 10:00 01024 Shaggy Yanson   (304)800-5191 (CELL)
  2024-02-29 10:30 01080 Sandy Beach     (999)333-4444 (WORK)
  ```

## Future Enhancements
- Implement a graphical user interface (GUI)
- Add a database for persistent storage
- Enable automated appointment reminders

## License
This project is open-source and free to use under the MIT License.
