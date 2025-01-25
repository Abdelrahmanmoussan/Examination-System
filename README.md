# Examination System

## Project Overview
The Examination System is a simple application designed to facilitate the process of creating and taking exams. The system offers two modes:

1. **Teacher Mode**: Allows teachers to add questions.
2. **Student Mode**: Enables students to answer questions within a set time limit.

### Key Features
- Teachers can add different types of questions:
  - Multiple Choice
  - True/False
  - Fill in the Blank
- Students answer the questions within 30 minutes.
- The system calculates the student's score and assigns a grade.

## Project Breakdown

### Teacher Mode
#### Tasks:
1. Input the number of questions.
2. For each question:
   - Select the type (Multiple Choice, True/False, or Fill in the Blank).
   - Input the question text and correct answers.
3. Store questions and correct answers in a list or data structure.

### Student Mode
#### Tasks:
1. Check if questions are available.
2. Start the exam timer (30 minutes).
3. Display questions to the student:
   - Include options for multiple-choice questions.
   - Allow input for answers.
4. Store student answers in a data structure.
5. End the exam after 30 minutes and proceed to grading.

### Grading
#### Tasks:
1. Compare student answers with the correct answers.
2. Calculate the number of correct answers and the percentage score.
3. Determine the grade based on the score (e.g., Excellent, Very Good, etc.).

### User Interface Enhancements
#### Tasks:
1. Provide clear messages, such as:
   - "The exam will start now."
   - "Time’s up!"
2. Ensure a smooth user experience with intuitive prompts and error handling.

## Analyze the Requirements
- **Inputs**:
  - Number of questions, question types, and student answers.
- **Outputs**:
  - Display questions, results, grades, and system messages.
- **User Interaction**:
  - Ensure ease of use for both teachers and students.

## Data Structures and Organization
- **Question List**:
  - Use objects to represent questions (e.g., `MultipleChoiceQuestion`, `TrueFalseQuestion`).
- **Student Answers**:
  - Store answers in a dictionary with question indexes as keys.
- **Timer**:
  - Implement a timer object to manage the 30-minute exam period.

## Logic Implementation
- **Answer Validation**:
  - Compare student answers with the correct ones stored by the teacher.
- **Grade Calculation**:
  - Calculate the score and assign a grade based on the number of correct answers.

## Testing and Evaluation
1. Test each component independently:
   - Input functionality for Teacher Mode.
   - Timer and answer collection in Student Mode.
   - Grading calculations.
2. Verify that the timer stops after 30 minutes.
3. Validate inputs and ensure error handling is robust.
4. Confirm the grading system is accurate and displays the correct grade.

## Optional Enhancements
1. **Data Persistence**:
   - Store questions in a file or database for reuse.
2. **Randomize Questions**:
   - Display questions in random order for each student.
3. **Review Questions**:
   - Allow students to review their questions and answers after the exam.

---

By implementing these features and following the outlined tasks, this Examination System will provide a functional and user-friendly platform for both teachers and students.

