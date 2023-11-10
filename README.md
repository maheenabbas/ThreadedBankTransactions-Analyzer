# ThreadedBankTransactions-Analyzer

## Description:
The ThreadedBankTransactions Analyzer project is a Java-based initiative that extends the functionality of the attached "Bank Account" project. The primary goal is to introduce multithreading capabilities for deposit and withdrawal transactions, conducting a predetermined number of iterations and carefully examining the resulting balances. The project unfolds in several key steps:

## Multithreaded Processing:

The project sets up threads for both deposit and withdrawal operations, creating a synchronized environment to manage concurrent transactions effectively.
Conducts 100 iterations of deposit and withdrawal transactions, observing the resulting balances at the conclusion of each execution.

## Observation and Analysis:

The program is executed, and attention is directed to the "balances" generated at the end of the 100 transactions.
Initial observations are made, noting any unexpected or inconsistent final balances.

## Refinement and Array Implementation:

The program is modified to process a reduced number of transactions (10 each for deposit and withdrawal), all with identical amounts.
An array is introduced to systematically count the occurrences of each final balance returned by the project after each execution of the loop.

## Data Integrity Evaluation:

Despite the expectation for a final balance of $0 after each iteration, the project recognizes potential discrepancies.
The final output, comprising the count of each unique final balance, is captured in a text file for further analysis.
