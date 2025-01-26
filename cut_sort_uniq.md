### **`cut` Command Notes**

- **Purpose**: The `cut` command is used to extract sections from each line of input, typically from files or output, based on specified delimiters, characters, or byte positions.

#### **Common Options**:

1. **Cut by Character Position**
   - **Option**: `-c`
   - Extracts specific character positions from each line.
2. **Cut by Field Delimiter**

   - **Option**: `-f`
   - Extracts specific fields (delimited by a separator like a tab or space). Often used with `-d` to specify the delimiter.

3. **Specify Field Separator**

   - **Option**: `-d`
   - Specifies the delimiter to separate fields, such as a comma or space.

4. **Remove Characters from the Beginning**
   - **Option**: `-b`
   - Selects byte positions, useful when dealing with binary data.

---

### **`sort` Command Notes**

- **Purpose**: The `sort` command is used to arrange lines of text in a specified order (alphabetically, numerically, etc.).

#### **Common Options**:

1. **Sort Alphabetically (Default)**

   - **Command**: `sort`
   - Sorts lines in ascending order (alphabetically by default).

2. **Sort Numerically**

   - **Option**: `-n`
   - Sorts lines based on numerical values instead of alphabetic order.

3. **Sort in Reverse Order**

   - **Option**: `-r`
   - Reverses the order of the sorted output.

4. **Sort by Specific Field**

   - **Option**: `-k`
   - Sorts lines based on a specific field or column, useful for sorting structured data.

5. **Remove Duplicates During Sorting**

   - **Option**: `-u`
   - Removes duplicate lines during sorting.

6. **Ignore Case During Sorting**
   - **Option**: `-f`
   - Sorts input in a case-insensitive manner.

---

### **`uniq` Command Notes**

- **Purpose**: The `uniq` command is used to filter out repeated lines in a file or input.

#### **Common Options**:

1. **Remove Consecutive Duplicate Lines**

   - **Command**: `uniq`
   - Removes adjacent duplicate lines. Typically used in combination with `sort` to remove all duplicates.

2. **Show Only Duplicate Lines**

   - **Option**: `-d`
   - Displays only the lines that are repeated in the input.

3. **Count Occurrences of Each Line**

   - **Option**: `-c`
   - Displays the number of times each line occurs in the input.

4. **Print Only Unique Lines**
   - **Option**: `-u`
   - Displays only the lines that appear once.

---

### **Combined Usage**:

- **`cut` + `sort` + `uniq`**:  
  These commands are often used together for text processing. For example, you might use `cut` to extract specific fields, `sort` to organize the data, and `uniq` to remove duplicates or count occurrences.

---
