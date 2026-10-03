# Data Model

This project follows a Star Schema design.

## Fact Table

### FactVisits

Contains patient visit records.

Columns include:

- VisitID
- PatientID
- DoctorID
- DepartmentID
- DiseaseID
- VisitDate
- TreatmentCost
- LengthOfStay
- Readmitted
- SatisfactionScore

---

## Dimension Tables

### DimPatient

Contains patient demographic information.

### DimDoctor

Contains doctor information.

### DimDepartment

Contains hospital departments.

### DimDisease

Contains disease classifications.

### DimDate

Provides calendar intelligence.