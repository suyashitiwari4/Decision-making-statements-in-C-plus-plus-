# AIM: To study and implement C++ decision making statements

# SOFTWARE REQUIRED:

Visual Studio

# THEORY:

Decision-making is the process to make a decision about which part of the code should be executed or not based on some condition. Decision-making in C++ involves the usage of conditional statements (also called decision control statements) to execute specific blocks of code primarily based on given situations and their results.

if Statement: In C++, the if statement is the simplest decision-making statement. It allows the execution of a block of code if the given condition is true. The body of the if statement is executed only if the given condition is true.

if-else Statement The if else is a decision-making statement allows us to make a decision based on the evaluation of a given condition. If the given condition evaluates to true then the code inside the 'if' block is executed and in case the condition is false, the code inside the 'else' block is executed.

if else if Ladder The if else if Ladder statements allow us to include additional situations after the preliminary if condition. The 'else if' condition is checked only if the above condition is not true, and the else is the statement that will be executed if none of the above conditions is true. If some condition is true, then not only the associated block is executed.

Nested if else The nested if else statement contains an 'if' statement inside another 'if' statement. This structure lets in more complex selection-making by way of comparing multiple conditions. In this type of statement, multiple conditions are checked, and then the body of the last if statement is executed.

Switch Statement In C++, the switch statement is used when multiple situations need to be evaluated primarily based on the value of a variable or an expression. switch statement acts as an alternative to multiple if statements or if-else ladder and has a cleaner structure and it is easy for handling multiple conditions.

# Implementation:

Based on the above decision making statements in C++ , Simple programs have been used to help understand how decision making statements work in c++. The programs are:

1.Odd-Even check

2.Vowel Check

3.Finding the largest number from three given numbers by the user

4.Making a Calculator using Switch Case

5.Making a Restaurant menu system.

# ALGORITHM:

Program 1:

Objective: To determine whether a user-entered number is even or odd.

STEPS:

1.Start

2.Ask the user to enter an integer (n)

3.Read input into variable n

4.Check divisibility of n by 2:

If n % 2 == 0, then:

5.Display "This is an even number"

6.Else:

7.Display "This is an Odd number"

8.End

Program 2:

Objective: To determine whether the character entered by the user is a vowel or a consonant.

STEPS:

1.Start

2.Declare a character variable str

3.Ask the user to enter a character

4.Read the input into str

5.Check if the character is a vowel:

If str is equal to 'a', 'e', 'i', 'o', 'u' (or their uppercase forms), then:

6.Display "The Character entered is a Vowel"

7.Else:

8.Display "The Character entered is a Consonant"

9.End

Program 3

Objective:

To determine and display the largest number among three user-entered integers.

STEPS:

1.Start

2.Declare three integer variables: a, b, c

3.Ask user to enter three numbers

4.Read input values into a, b, and c

5.Initialize num ← a

6.Compare b and c with num:

If b > num, set num ← b

If c > num, set num ← c

7.Display the largest number (num)

8.End

Program 4:

Objective: To perform one of four basic arithmetic operations—Addition, Subtraction, Multiplication, or Division—based on user input(Simple Calculator).

STEPS:

1.Start

2.Declare float variables a, b, sum, sub, mul, Div and integer num

3.Ask user to enter two numbers

4.Read inputs into a and b

5.Ask user to select an operation:

1 → Addition

2 → Subtraction

3 → Multiplication

4 → Division

6.Read input into num

7.Use a switch-case statement to perform the selected operation:

Case 1: sum ← a + b

Case 2: sub ← a - b

Case 3: mul ← a * b

Case 4: Div ← a / b

Default: Display invalid input message

8.Display the result of the selected operation

9.End

Proagram-5:

Objective:Using switch case to select different dishes from menu.

STEPS:

1.Start

2.Declare variable choice and subchoice.

3.Display the menu 1.VEG THAALI 2.NON-VEG THAALI 3.CHINESE.

4.Enter your main course choice

5. case 1:
            cout << "You selected VEG THAALI." << endl;
   
            cout << "Choose your sabji:" << endl;
   
            cout << "1. Paneer Butter Masala" << endl;
   
            cout << "2. Veg Korma" << endl;
   
            cout << "Enter your sub-choice: ";
   
            cin >> subChoice;
   
            switch(subChoice) {
   
                case 1:
   
                    cout << "You will get:" << endl;
   
                    cout << "Paneer Butter Masala, Garlic Naan, Salad, Vanilla Ice Cream" << endl;
                    break;
   
                case 2:
   
                    cout << "You will get:" << endl;
   
                    cout << "Veg Korma, Butter Roti, Salad, Mango Ice Cream" << endl;
                    break;
   
                default:
                    cout << "Invalid sub-choice in VEG THAALI!" << endl;
            }
            break;

7. case 2:
            cout << "You selected NON-VEG THAALI." << endl;
   
            cout << "Choose your non-veg dish:" << endl;
   
            cout << "1. Butter Chicken" << endl;
   
            cout << "2. Chicken Curry" << endl;
   
            cout << "Enter your sub-choice: ";
   
            cin >> subChoice;
   
            switch(subChoice) {
                case 1:
                    cout << "You will get:" << endl;
   
                    cout << "Butter Chicken, Garlic Naan, Omelette, Chocolate Ice Cream" << endl;
   
                    break;
   
                case 2:
   
                    cout << "You will get:" << endl;
   
                    cout << "Chicken Curry, Butter Roti, Boiled Egg, Strawberry Ice Cream" << endl;
   
                    break;
   
                default:
                    cout << "Invalid sub-choice in NON-VEG THAALI!" << endl;
            }
            break;


   7. case 3:
      
            cout << "You selected CHINESE." << endl;
      
            cout << "Choose your Chinese dish:" << endl;
      
            cout << "1. Manchurian Rice Bowl" << endl;
      
            cout << "2. Hakka Noodles" << endl;
      
            cout << "Enter your sub-choice: ";
      
            cin >> subChoice;
      
            switch(subChoice) {
                case 1:
      
                    cout << "You will get: Manchurian Rice Bowl with Sauce" << endl;
                    break;
      
                case 2:
      
                    cout << "You will get: Hakka Noodles with Spring Roll" << endl;
                    break;
      
                default:
                    cout << "Invalid sub-choice in CHINESE!" << endl;
            }
            break;

  8. otherwise invalid main choice.

  9.End
# Conclusion:

Hence we have learnt and implemented C++ decison making statements


