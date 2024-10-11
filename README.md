# Data Annotation Assignment

## Overview
This repository contains Python script, test cases, and explanations for the Data Annotation Assignment. 
The assignment consists each focusing on different aspects of data extraction and template creation using Python.

## File Structure
Part_1/: Understanding Requirements and Data Structure
Part_2/: Template Creation for Data Extraction
Part_3/: Debugging and Improving Extraction Logic
Part_4/: Template Optimization and Efficiency
Part_5/: Dealing with Complex Scenarios


## Instructions for Running Scripts
1. Navigate to each part's folder.
2. Run the main script using `python partX_script.py`.
3. Run the test cases using `python test_partX.py`.

## Thought Process
Each part of the assignment builds upon the previous one, adding complexity and real-world scenarios. Below is a summary of each part:

### Part 1: Understanding Requirements
- Approach: Reviewed sample PDFs and extracted key elements like headers and table data.
- Challenges: Parsing various formats consistently.
- Solution: Identified common patterns for headers and table formats.

### Part 2: Template Creation
- Approach: Developed a JSON-based template with generalized rules.
- Challenges: Accommodating variations in headers and tables.
- Solution: Used a dictionary-based approach for flexibility.

### Part 3: Debugging and Improving Logic
- Approach: Enhanced code to handle multiple amount formats.
- Challenges: Ensuring the function handles edge cases like word-based numbers.
- Solution: Implemented a word-to-number converter for flexibility.

### Part 4: Template Optimization
- Approach: Generalized extraction logic for varied formats.
- Challenges: Improving efficiency while maintaining accuracy.
- Solution: Used regex optimization and consolidated lookups.

### Part 5: Complex Scenarios
- Approach: Managed multi-page documents and multi-line tables.
- Challenges: Combining data across pages and handling missing data.
- Solution: Implemented functions for multi-page processing and error handling.

## Video Explanation
An explanation video walks through each part, demonstrating how the scripts work, discussing code logic, and showing the output.
(Here I have Created Video Using loom.com where we can share screen along with recording video and audio)

## Assumptions
- Documents follow a consistent format for currency and date representation.
- Variations in headers are manageable through defined patterns.



