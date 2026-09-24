# HP_Python_Bioinformatics

Learning introduction to python bioinformatics at Humber Polytechnic, all my coding including labs and assignments to the final project of the course.

## Lab_1_MolarityCalculator

Write a script to calculate how much of a compound is needed to make a solution of a given
molarity. You will need to create variables to store:

The molecular mass of the compound (in g/mol)

The volume of solution you want to create (in ml)

The desired concentration (molar M)

The different values you need for the calculation are requested interactively using input
statements

The formula will be: Mass (g) = Concentration (mol/L) * Volume (L) * Formula Weight (g/mol)

Make the script print a summary of the input variables and the calculated value by
passing all these as separate arguments to your print function.

## Lab_1_ComplementaryDNA

Here's a short DNA sequence:
ACTGATCGATTACGTATAGTATTTGCTATCATACATATATATCGATGCGTTCAT
Write a program that will print the complement of this sequence.
HINT: we need to take our sequence and replace
A with T, T with A, C with G, and G with C. We'll have to make four separate calls to
replace, and use the return value for each on as the input for the next one

## Lab_2_Patient_Data_Management

Create a list to store the names of four patients: Jane Doe, John Smith, Emily White, and
Michael Brown. Then:

1. Print the name of the second patient in the list

2. A new patient arrives to the hospital: Sarah Miller. Add her at the end of the list.

3. The third patient’s name was misspelled; it should be Williams instead of White.
Update the patients name to reflect the correct one.

4. The clinic decides to merge with another healthcare provider, which means the
patient records from both institutions must consolidate into a single list:

    a. Create a new list containing the names Alejandro Ramirez, Chloe Mitchell, Sofia Vargas and Liam Sullivan
 
    b. Combine both patient lists into one and print the new list.

6. Modify your script to ask the user for a name, and check if it exists in the list of
patients. Output the verification as a Boolean value (True or False).

7. Modify your script to ask the user for multiple patient names (separated by commas)
and an index, and then insert the new names into the list, starting at the
index/position given by the user.
