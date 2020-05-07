the error was that the condition i%3 and i%5 ==0 was placed last

this means that even if the condition satisfies, i%3 or i%5 will also satisfya and thus will never reach this condition

to fix this error placing the i%3 and i%5 ==0 condition first solves it 