🔐 Simple Password Generator (Bash Script)

A lightweight and secure Bash script that generates strong, random passwords using OpenSSL's cryptographically secure random number generator.



✨ Features

🔁 Generates 5 random passwords at a time

🔢 Customizable password length

🔐 Uses openssl rand for cryptographically secure randomness

⚙️ No dependencies beyond standard Unix tools

⚡ Simple and fast CLI operation

📦 Requirements

Unix-based system (Linux, macOS, WSL)

bash shell

openssl installed (available by default on most Unix systems)

🚀 Getting Started

Clone the repository:

git clone https://github.com/kobbyprincee/Password-Generator.git
cd Password-Generator

Make the script executable:

chmod +x generate-passwords.sh

Run the script:

./generate-passwords.sh

By default, it generates 5 passwords, each 16 characters long.

🛠️ Custom Usage

You can pass a custom password length as a command-line argument:

./generate-passwords.sh 20

🔹 This will generate 5 random passwords, each 20 characters long.

🧪 Sample Output

🔐 Generating 5 secure passwords (Length: 16)...
1: X#4w6!kDZ92Tf@Yb
2: kR2%7Hp&c9D$P1Vz
3: g9*HT8@fR#1!yqLQ
4: ^P3$kWz0T#8&uLtR
5: Wz#0!vL9^Tg$6ePq

📝 License

This project is licensed under the OpenSSL License.

🤝 Contributing

Feel free to fork this project and submit pull requests. Bug fixes, new features, and improvements are all welcome!

