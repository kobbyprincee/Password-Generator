🔐 Simple Password Generator (Bash Script)

Bash
OpenSSL
License

A lightweight Bash script that generates secure, random passwords using OpenSSL's cryptographically secure random number generator.
✨ Features

    Generates 5 random passwords at a time

    Customizable password length

    Uses openssl rand for strong randomness

    No dependencies beyond standard Unix tools

    Simple and fast command-line operation

📦 Installation
Option 1: Clone the repository
bash
Copy

git clone https://github.com/kobbyprincee/Password-Generator.git
cd Password-Generator
chmod +x password-generator.sh


🚀 Usage

Run the script and follow the prompts:
bash
Copy

./password-generator.sh

Example session:
bash
Copy

$ ./password-generator.sh
This is a simple password generator
Please enter the length of the password: 12
Generated passwords:
1. jK8s2L9jXpQa
2. d8KzP7Fx1dLv
3. 0aKqZ8pLnQsF
4. w8PjRs9KzMvH
5. s9RkWp3NqUtL

🛠 Requirements

    Bash (v4.0+ recommended)

    OpenSSL (for cryptographically secure random generation)

Check your OpenSSL version:
bash
Copy

openssl version

🔧 Customization

You can modify the script to:

    Change the number of passwords generated

    Adjust the character set used

    Add special requirements (symbols, uppercase, etc.)

Example modification to include symbols:
bash
Copy

# Change the character set in the script
CHARSET="A-Za-z0-9!@#$%^&*"

🤝 Contributing

Contributions are welcome! Please open an issue or pull request for any:

    Bug fixes

    Feature enhancements

    Documentation improvements

📄 License

MIT License - see LICENSE file for details.
⚠️ Security Note

While this script uses cryptographically secure random generation, always:

    Store passwords securely

    Use a password manager for important accounts

    Enable 2FA where available

Made with ❤️ by Kobby Prince
New chat
