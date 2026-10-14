# School Attendance System

**Programming Logic Assignment** — Sulaiman Kondeh

## Project overview

This project designs a simple school attendance process for teachers. The accompanying report explains the problem, proposed system, requirements, computational-thinking approach, stakeholders, benefits, limitations, and relevant education goals. The flowchart and pseudocode describe the attendance-entry logic. An editable Flowgorithm prototype demonstrates input validation and attendance totals.

## Repository contents

- `School_Attendance_System_Written_Report[101].docx` — written project report.
- `School_Attendance_Flowchart.png` — flowchart image showing the main attendance workflow.
- `School_Attendance_System_Pseudocode.docx` — structured pseudocode and explanation of sequence, selection, and repetition.
- `School_Attendance_System.fprg` — editable Flowgorithm prototype.

## Prototype behavior

The Flowgorithm file asks for a class, date, and positive number of students. For each student, it accepts a name and a status (`P` for present, `A` for absent, or `L` for late), rejects invalid status codes, and prints totals by status.

This is a classroom logic prototype, not a deployed school information system. It does not authenticate users or save student records to a database. Use fictional data when testing.

## Run the Flowgorithm project

1. Install and open Flowgorithm.
2. Choose **File → Open** and select `School_Attendance_System.fprg`.
3. Choose **Run**. Enter a class (for example, `Form 2A`), a date (for example, `2026-10-14`), and a positive student count.
4. Enter a student name and one of `P`, `A`, or `L` for each student. If a status is invalid, enter one of the valid codes when prompted.
5. Check that the final present, absent, and late totals add up to the number of students entered.

## Example test

For three students, enter `Ama` / `P`, `Binta` / `A`, and `Joseph` / `L`. The expected summary is 3 total, 1 present, 1 absent, and 1 late. Also test an invalid status such as `X` and confirm the program asks again.
