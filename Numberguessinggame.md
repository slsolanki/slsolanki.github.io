This is the flowchart for my number guessing game
graph TD
A[Start] --> B[Computer randomly selects a number]
B --> C[User guesses the number]
C --> D{Is guess correct?}
D --Yes--> E[Display "Correct"]
E --> F[End]
D --No--> G{Is guess too high?}
G --Yes--> E[Display "Too High"]
G --No--> E[Display "Too Low"]
H --> C
