# JavaScript Challenge: Dean's List Eligibility Checker

This repository contains a mandatory lab challenge designed to reinforce your understanding of core JavaScript concepts, including **Data Structures (Arrays)**, **Functions**, **Conditional Logic**, and **Looping**.

## The Challenge: Semester Eligibility Assessment

Your task is to create a single HTML file with embedded JavaScript to process student academic data, perform calculations, and dynamically display the results to determine eligibility for the Dean's List award.

---

### I. Program Requirements

#### A. Data Structure Setup

1.  **Multi-Dimensional Array:** Define a JavaScript array named `studentData` to store the student records provided below.
2.  **Data Format:** Each sub-array must contain three elements: `[Student Name (String), Total Credit Hours (Number), Current GPA (Number)]`.

**Student Data Table (Input for your Array):**


| Student Name | Credit Hours (Number) | Current GPA (Number) |
| :--- | :--- | :--- |
| Ali Bin Ahmad | 15 | 3.75 |
| Bala A/L Muthu | 12 | 3.40 |
| Siti Nurhaliza | 18 | 4.00 |
| Wong Mei Ling | 10 | 3.50 |
| David Lee | 15 | 2.95 |

#### B. Function Definition (`checkDeanList`)

1.  Create a function named `checkDeanList(gpa)` that accepts one parameter.
2.  The function must use a **Conditional Statement (`if/else`)** to check if the GPA is **3.50 or higher**.
3.  The function must return the appropriate string: `"Dean's List Eligible"` or `"Not Dean's List Eligible"`.

#### C. Processing and Dynamic Output

1.  Use a **`for` loop** to iterate through all student records in the `studentData` array.
2.  Inside the loop, call the `checkDeanList()` function for each student.
3.  Display the results (Name, GPA, and Status) directly onto the web page using the **`document.write()`** method, ensuring each student's result is clearly separated.

### II. Expected Final Output

When your HTML file is opened, the page must dynamically render a clear list of all student outcomes.

**Expected Browser Output:**
![Expected Program Output](assets/output.png)

*(Note: The exact styling and formatting (like colors/divs) can vary, but the information displayed must be accurate.)*

---

## Important Guidance on AI Tool Usage

**I acknowledge that you may use AI tools (e.g., Gemini, ChatGPT) for assistance during the learning and practice phase.** However, please adhere to the following mandatory guidelines:

1.  **MANDATORY CITATION:** If you use an AI tool to generate, correct, or debug any part of the JavaScript code (such as array initialization, function logic, or the loop structure), you **MUST** include a comment in your script indicating its use.

    ```javascript
    // -- AI ASSISTED CODE START --
    // [State which part was assisted, e.g., Logic for the checkDeanList function 
    // or Debugging the for loop structure]
    // ... [Your code here]
    // -- AI ASSISTED CODE END --
    ```

2.  **FUTURE RESTRICTIONS:** Be aware that **during the official Lab Test and Final Examination, the use of any AI tool or external assistance will be strictly prohibited.**

3.  **FOCUS ON MASTERY:** Use AI assistance as a teaching aid, not just an answer generator. The goal is to prepare you for examinations where you are unaided. Even with AI help, you must strive to fully **understand the underlying JavaScript logic, syntax, and principles** to write similar code independently.

Good luck with your challenge!
