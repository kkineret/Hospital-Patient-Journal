# Hospital-Patient-Journal
This project is designed for managing patients in a hospital. It includes functions for updating patient status, deleting patients, and archiving discharged patients. Archiving happens automatically, and the archive CSV file is saved in the `hospital` folder.

## Functionality Description

1. **Main Menu**:
   Upon launching the program, you'll be presented with the following options:
Welcome to the patients journal! Please choose an option: 
1- Add a New Patient 
2- Delete a Patient 
3- Update the Patient's Status 
4- Search for a Patient 
5- Print all the Patients of the Department 
6 - View Archived Patients 
0 - Exit Enter your choice:

2. **Add a New Patient**:
- Allows adding a new patient to the system.

3. **Delete a Patient**:
- Allows deleting a patient from the system.

4. **Update the Patient's Status**:
- Allows updating the patient's current status (e.g., treatment, discharge, etc.).

5. **Search for a Patient**:
- Allows searching for a specific patient by their details.

6. **Print all the Patients of the Department**:
- Displays a list of all the patients currently in the department.

7. **View Archived Patients**:
- Displays a list of all discharged patients stored in the archive.

8. **Patient Archiving**:
- When a patient is discharged, their information is automatically saved to an archive file in CSV format.
- The archive file is saved in the `hospital` directory with the name `patients_archive.csv`.
- The archive contains information about discharged patients, allowing you to track the history of patients who are no longer in the current list.

## How to Use

1. Clone the repository:
git clone https://github.com/kkineret/Hospital-Patient-Journal.git

2. Navigate to the project directory:
cd Hospital-Patient-Journal

3. To compile and run the project, use:
javac Main.java
java Main

4. The patient archive will be automatically updated each time a patient is discharged, and the file will be saved in the hospital folder.

Project Structure

Hospital-Patient-Journal/
│
├── src/
│   ├── Main.java               # Main class of the program
│   ├── Patient.java            # Patient class
│   ├── ArchiveManager.java     # Class for managing archives
│   └── ...                    # Other project classes
│
├── hospital/                   # Folder for storing archives
│   └── patients_archive.csv    # Archive of discharged patients
│
└── README.md                  # This file

Dependencies

Java 8 or higher
Notes

The archive is created automatically each time a patient's status is updated to "discharged."
The CSV file patients_archive.csv can be opened with any text editor or spreadsheet application.

Developers: Maria Edinburg and Ekaterina Fedorenko




