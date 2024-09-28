# File Handling in Python - Practice Activity

👋 **Welcome to your Python file handling practice session!**

In this activity, you'll learn how to:

- Open files using different modes (read, write, append)
- Write and read data from files
- Manage errors when working with files

## Instructions

1. **Open the `main.py` file** from this repository.
2. **Type the code** as given in the task or experiment with your own.
3. **Click the "Run" button** to test your code and see the output.

### Key Concepts

- **Opening files**: Learn how to open files in different modes (e.g., `"r"` for read, `"w"` for write).
- **Writing to a file**: Understand how to write text/data into a file.
- **Reading from a file**: Practice reading the contents of a file.
- **Closing files**: Don’t forget to close the file when you're done.
- **Error Handling**: Use `try` and `except` to handle errors gracefully when working with files.

### Example

Here’s a simple example of writing to a file:

```python
# Open a file in write mode
with open("example.txt", "w") as file:
    file.write("Hello, Python learners!")

# Now let's read the file
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```
