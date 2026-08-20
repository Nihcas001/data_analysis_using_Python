This program demonstrates the use of NumPy for numerical computation on customer transaction data. It covers array creation, indexing, slicing, and arithmetic operations for efficient manipulation and analysis of numerical records.

A Complete Practical Question Set. For your students, I would give the following questions.

Part A — Array Creation & Properties
    Import NumPy.
    Create the banking transaction array.
    Display the complete array.
    Find the number of dimensions.
    Find the shape.
    Find the number of elements.
    Display the data type.
    
Part B — Indexing
    Display the first customer's record.
    Display the first customer's balance.
    Display the 10th customer's ID.
    Display the last customer's record.
    Display the last customer's balance.
    
Part C — Slicing
    Display the first five customers.
    Display customers 6–10.
    Display the last five customers.
    Extract all customer IDs.
    Extract all balances.
    Extract all deposits.
    Extract all withdrawals.
    Extract Balance, Deposit and Withdrawal columns.
    
Part D — Arithmetic
    Calculate new balance after deposits and withdrawals.
    Calculate balance after EMI deduction.
    Calculate 5% interest.
    Calculate balance including 5% interest.
    Calculate net transaction amount.
    Calculate total deposits.
    Calculate total withdrawals.
    
Part E — Statistical Operations
    Find total balance.
    Find average balance.
    Find maximum balance.
    Find minimum balance.
    Find median balance.
    Find variance.
    Find standard deviation.
    
Part F — Filtering
    Find customers with balance > ₹70,000.
    Find customers with deposit > ₹15,000.
    Find customers with balance > ₹70,000 AND deposit > ₹15,000.
    Find customers with withdrawal > ₹8,000 OR EMI > ₹5,000.
    Count customers with balance > ₹70,000.
    Categorize customers as Premium/Regular using np.where().

Part G — Advanced NumPy

    Find customer with highest balance using argmax().
    Find customer with lowest balance using argmin().
    Calculate column-wise totals using axis=0.
    Calculate row-wise totals using axis=1.
    Reshape an array.
    Flatten an array.
    Sort balances.
    Perform broadcasting using transaction fees.
    Generate customer IDs using np.arange().
    Generate random transaction data using np.random.randint().

Recommended Teaching Flow

Use this sequence:

    Step 1  → Import NumPy
           ↓
    Step 2  → Create banking array
           ↓
    Step 3  → Understand rows & columns
           ↓
    Step 4  → ndim, shape, size, dtype
           ↓
    Step 5  → Indexing
           ↓
    Step 6  → Slicing
           ↓
    Step 7  → Column extraction
           ↓
    Step 8  → Arithmetic operations
           ↓
    Step 9  → sum, mean, min, max
           ↓
    Step 10 → Boolean filtering
           ↓
    Step 11 → Multiple conditions
           ↓
    Step 12 → np.where()
           ↓
    Step 13 → axis
           ↓
    Step 14 → reshape & flatten
           ↓
    Step 15 → sorting
           ↓
    Step 16 → broadcasting
           ↓
    Step 17 → random array generation



Dataset
    
| Customer ID | Balance | Deposit | Withdrawal |  EMI | Transactions |
| ----------- | ------: | ------: | ---------: | ---: | -----------: |
| 1001        |   50000 |   12000 |       5000 | 3000 |            8 |
| 1002        |   72000 |   15000 |       7000 | 4500 |           12 |
| 1003        |   35000 |    8000 |       3000 | 2500 |            6 |
| 1004        |   91000 |   20000 |       9000 | 6000 |           15 |
| 1005        |   45000 |   10000 |       4000 | 3000 |            9 |
| 1006        |   68000 |   14000 |       6500 | 4000 |           11 |
| 1007        |   29000 |    7000 |       2500 | 2000 |            5 |
| 1008        |   83000 |   18000 |       8500 | 5000 |           14 |
| 1009        |   57000 |   11000 |       5500 | 3500 |           10 |
| 1010        |  102000 |   25000 |      12000 | 7000 |           18 |
| 1011        |   39000 |    9000 |       3500 | 2500 |            7 |
| 1012        |   76000 |   16000 |       7500 | 4500 |           13 |
| 1013        |   48000 |   10500 |       4500 | 3000 |            8 |
| 1014        |   95000 |   22000 |      10000 | 6500 |           16 |
| 1015        |   62000 |   13000 |       6000 | 4000 |           11 |

