**Problem Statement**

>A survey company collected incomplete customer feedback forms. Handle missing data, merge multiple datasets, and clean inconsistent records using Pandas.

For this problem, we will cover three major Pandas tasks:
```
1. Missing Data Handling
    Detect missing values
    Count missing values
    Fill missing values
    Remove missing records
2. Dataset Merging
    Concatenate datasets
    Merge datasets using a common column
    Understand inner, left, right, and outer joins
3. Data Cleaning
    Remove extra spaces
    Standardize uppercase/lowercase values
    Correct inconsistent categorical values
    Remove duplicates
    Convert data types
    Validate cleaned data
```

The Excel file contains three sheets:
| Sheet             | Purpose                            |
| ----------------- | ---------------------------------- |
| `Feedback_Batch1` | First batch of incomplete feedback |
| `Customer_Master` | Customer information               |
| `Feedback_Batch2` | Second batch of feedback           |

**Understand the Four Merge Types**
| Merge   | Meaning                          |
| ------- | -------------------------------- |
| `inner` | Only matching records            |
| `left`  | All records from left DataFrame  |
| `right` | All records from right DataFrame |
| `outer` | All records from both DataFrames |

**merge() vs concat()**
| `merge()`                 | `concat()`                           |
| ------------------------- | ------------------------------------ |
| Combines related datasets | Combines datasets by stacking        |
| Uses common column/key    | Usually doesn't require a common key |
| Similar to SQL JOIN       | Similar to appending rows/columns    |
| Example: Customer ID      | Example: Batch 1 + Batch 2           |


**Complete Practical Flow**

Students can understand the entire practical through this pipeline:
```
Raw Feedback Data
       ↓
Load Dataset
       ↓
Inspect Dataset
       ↓
Detect Missing Values
       ↓
Handle Missing Values
       ↓
Remove Extra Spaces
       ↓
Standardize Text
       ↓
Check Duplicates
       ↓
Remove Duplicates
       ↓
Load Customer Master
       ↓
Merge Datasets
       ↓
Load Feedback Batch 2
       ↓
Concatenate Feedback Batches
       ↓
Validate Final Dataset
       ↓
Save Clean Dataset

```

**Most Important Pandas Functions for This Problem**
| Function               | Purpose                    |
| ---------------------- | -------------------------- |
| `pd.read_csv()`        | Read CSV file              |
| `df.isnull()`          | Detect missing values      |
| `df.isnull().sum()`    | Count missing values       |
| `df.dropna()`          | Remove missing records     |
| `df.fillna()`          | Fill missing values        |
| `df.mean()`            | Calculate mean             |
| `df.median()`          | Calculate median           |
| `df.mode()`            | Find most common value     |
| `df.drop_duplicates()` | Remove duplicate records   |
| `df.duplicated()`      | Detect duplicates          |
| `.str.strip()`         | Remove extra spaces        |
| `.str.lower()`         | Convert text to lowercase  |
| `.str.upper()`         | Convert text to uppercase  |
| `.str.title()`         | Convert text to title case |
| `pd.merge()`           | Merge related datasets     |
| `pd.concat()`          | Combine datasets           |
| `df.to_csv()`          | Save DataFrame as CSV      |
