###  Excel Practice: Text Cleaning and Formatting Using Functions


 **Project Overview**:

  This project is a hands-on Excel exercise focused on cleaning and reformatting text data  specifically improperly entered full names. Often in real-world data, especially during manual entry, names and text entries are inconsistent in format, case, and spacing. This exercise demonstrates how to correct such issues using text functions in Microsoft Excel.

---

- Key Excel Functions Used:

 1. **LEFT()**:

     - Syntax: =LEFT(text, num_chars)
     - Purpose: Extracts a specified number of characters from the BEGINNING (left side) of a text string.
     - Use Case in File: Extracted first name initials or short codes from full names.

 2. **RIGHT()**:

     - Syntax: =RIGHT(text, num_chars)
     - Purpose: Extracts characters from the END (right side) of a text string.
     - Use Case in File: Pulled suffixes or final characters from names or IDs.

 3. **MID()**:

     - Syntax: =MID(text, start_num, num_chars)
     - Purpose: Extracts characters from the MIDDLE of a string.
     - Use Case in File: Retrieved portions like middle names or sections of a full name.

 4. **PROPER()**:

     - Syntax: =PROPER(text)
     - Purpose: Converts text to proper case (first letter uppercase, rest lowercase).
     - Use Case in File: Standardized names like "john DOE" to "John Doe'.

 5. **UPPER()**:

     - Syntax: =UPPER(text)
     - Purpose: Converts all text to UPPERCASE.
     - Use Case in File: Made all names consistent in uppercase for uniformity.

 6. **LOWER()**:

     - Syntax: =LOWER(text)
     - Purpose: Converts all text to LOWERCASE.
     - Use Case in File: Ensured all lowercase transformation for comparisons.

 7. **TRIM()**:

     - Syntax: =TRIM(text)
     - Purpose: Removes extra spaces from text, leaving only single spaces between words.
     - Use Case in File: Cleaned up names with irregular spacing like "  John   Doe " → "John Doe".

 8. **FIND()**:

     - Syntax: =FIND(find_text, within_text, [start_num])
     - Purpose: Returns the position of a character or substring within another text string.
     - Use Case in File: Helped locate spaces or delimiters to split FIRST and LAST names.

---

- Objective and Outcome

   The goal was to transform untidy name records into a clean, professional format. This was achieved by:

   - Removing unwanted spaces
   - Standardizing capitalization
   - Splitting names using position-based text functions
   - Applying proper case formatting

Through this, I developed skills in data cleaning, which is a vital first step in any data analysis workflow.

---

- Skills Demonstrated

   - Text manipulation and formatting
   - Real-world data cleaning logic
   - Combining multiple functions in a single formula
   - Understanding character positions within strings





