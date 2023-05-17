# Data Engineer Challenge

> Level: **Very Easy**


## Code Execution Intructions

All code is in `main.py` file and require 2 arguments: first a path to json file and a path to a csv file. The proposed solution accepts arguments via command line as follows:

`python3.10 data-engineer-1/main.py <path-to-json-file> <path-to-csv-file>`

The arguments can also be manually changed in the main() function inside `main.py` file.


Make sure the following packages are avaliable in your testing environment:
- pandas 1.4.4

## Challenge Instructions

Code the function `load_transform_save` that recieves a path to a JSON file, a function and a path to a CSV file.

The function must load the JSON file, apply the function to the data and save the result in the CSV file.

The transformation function must be able to translate the expected input json data to the expeted CSV data.

## Formats

**JSON**

```json
[
  {
    "firstName": "John",
    "lastName": "Doe",
    "age": 30,
    "city": "New York"
  },
  {
    "firstName": "Jane",
    "lastName": "Doe",
    "age": 25,
    "city": "Chicago"
  },
  {
    "firstName": "Bob",
    "lastName": "Doe",
    "age": 40,
    "city": "Los Angeles"
  }
]
```

**CSV**
```csv
name,age,city
J. Doe,30,New York
J. Doe,25,Chicago
B. Doe,40,Los Angeles
```

## Notions

- [python-json](https://docs.python.org/3/library/json.html)
- [python-csv](https://docs.python.org/3/library/csv.html)

## Code provided

```python
import json
import csv

def load_transform_save(path_to_json_file, function, path_to_csv_file):
    pass

def main():
    pass

if __name__ == "__main__":
    main()
```

If you have any questions please [open and issue](https://github.com/zarvhq/challenges/issues/new) and we'll reach out to help.