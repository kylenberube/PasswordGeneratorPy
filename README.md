# Python-Password-Generator

## Description
Project consists of a simple Python script that allows the user to generate a 12 character password, using a random sequence of letters, digits and special characters.

## Script Walk-through
Run the script:
``` bash
python python_password_generator.py
```  
Enter the desired length when prompted

The generated password will display on the console

## Customization

You can customize the script by modifying the `generate_password` function in `python_password_generator.py`. Adjust the `length` parameter or update the `characters` variable to include/exclude specific character sets.

```python
# Customize password length
password_length = 16
generated_password = generate_password(password_length)

# Customize character sets
characters = string.ascii_letters + string.digits  # Example with letters and digits only
generated_password = generate_password(length=12)
