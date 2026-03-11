#  Bank Account Simulator

An Object Oriented Programming (OOP) project in Python that 
simulates a real banking system demonstrating all 4 pillars 
of OOP.

##  OOP Concepts Demonstrated
| Concept | How it's used |
|---|---|
| Encapsulation | Balance and account details are private |
| Inheritance | SavingsAccount and CurrentAccount extend Account |
| Polymorphism | Each account type applies different interest rates |
| Abstraction | Abstract base class defines common interface |

##  Project Structure
- `Account` — Abstract base class
- `SavingsAccount` — 4% interest, standard withdrawal
- `CurrentAccount` — 2% interest, overdraft facility
- `Bank` — Manages all accounts

##  Features
- Create Savings and Current accounts
- Deposit and Withdrawal with validation
- Transfer between accounts
- Overdraft facility for Current accounts
- Interest calculation per account type
- Full transaction history with timestamps
- Account statements

##  Tools Used
- Python 3
- Google Colab
- OOP (Encapsulation, Inheritance, Polymorphism, Abstraction)

##  How to Run
1. Open the notebook in Google Colab or Jupyter
2. Run all cells in order
3. Modify the simulation in the last cell to test different scenarios
