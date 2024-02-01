# Password Generator

This Python script generates a random password that meets specified constraints such as length, the number of digits, special characters, uppercase and lowercase letters.

## Usage

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/password-generator.git
    ```

2. **Run the Script:**
    ```bash
    cd password-generator
    python password_generator.py
    ```

3. **Generated Password:**
    After running the script, a randomly generated password that meets the specified constraints will be printed to the console.

## Parameters

- `length`: Length of the password (default: 16)
- `nums`: Minimum number of digits in the password (default: 1)
- `special_chars`: Minimum number of special characters in the password (default: 1)
- `uppercase`: Minimum number of uppercase letters in the password (default: 1)
- `lowercase`: Minimum number of lowercase letters in the password (default: 1)

## Example

Generate a password with default constraints:
```python
new_password = generate_password()
print('Generated password:', new_password)
```

## Dependencies

- `secrets`: Python module for generating cryptographically strong random numbers suitable for managing data such as passwords, account authentication, etc.
- `string`: Python module containing common string operations.

---

You can customize the constraints by passing arguments to the `generate_password()` function. Have fun generating secure passwords! 🛡️💻
