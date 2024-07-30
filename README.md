# Coursework Assignment 2 2023–2024

## University of London
Computing and Information Systems/Creative Computing

**Course:** CO3326 Computer Security

**Assignment:** Coursework Assignment 2 2023–2024

### Introduction

This project focuses on Elliptic Curve Cryptography (ECC) and the Elliptic Curve Integrated Encryption Scheme (ECIES). The coursework assignment includes an exercise and a report, each carrying 50 marks.

### Part A – Exercise

The exercise involves decrypting two given ciphertexts and re-encrypting the retrieved plaintext with another key using a simplified version of ECIES. The provided data includes ECC key pairs for Alice and Bob, encrypted messages, and other necessary parameters.

### Part B – Report

The report answers various questions related to ECC and ECIES, demonstrating understanding and practical application of these cryptographic concepts.

### Files in the Repository

- **Assignment/CO3326 Computer security.pdf**: Contains the coursework assignment details.
- **CO3326cw2.docx**: Report answering the provided questions in the coursework.
- **CO3326cw2.json**: JSON file containing the solutions for the exercise.
- **README.md**: This file.

### Structure and Content

#### 1. Explanation and Visualization of the SECP256K1 Elliptic Curve
- Description of the SECP256K1 curve and group law for elliptic curves.
- Visualization and explanation of point addition and scalar multiplication.

#### 2. Finite Prime Fields in Elliptic Curve Cryptography (ECC)
- Description of how elliptic curves operate over finite fields.
- Explanation of modular arithmetic and cyclic subgroups.

#### 3. Subgroup Order and Base Point
- Explanation of subgroup order and its significance in ECC.
- Description of the base point and its selection criteria.

#### 4. Encryption and Decryption Process
- Step-by-step explanation of the encryption and decryption processes using ECC and ECIES.
- Practical example illustrating the process.

#### 5. Vulnerability of ECIES
- Discussion on the susceptibility of ECIES to chosen-plaintext or chosen-ciphertext attacks.
- Explanation of security measures to mitigate these vulnerabilities.

#### 6. Design and Code Implementation
- Overview of the design and pseudocode for ECC encryption and decryption.
- Implementation notes and key functions.

### How to Run

To run the provided code, you need to have Python and the `ecdsa` library installed. The code can be executed in any Python environment. Follow the instructions in the code comments for encryption and decryption processes.

### Submission Requirements

- Report: Submit as a PDF document named `YourName_SRN_CO3326cw2.pdf`.
- Exercise: Submit as a JSON file named `YourName_{srn}_CO3326cw2.json`.

### Acknowledgments

The project is based on traditional ECC practices and built on the ECIES scheme. The provided framework simplifies the complex ECC algorithms for educational purposes.
