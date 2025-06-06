# Create-A-Strong-Password-And-Evaluate-Its-Strength
Task 6

# Password Strength Evaluation

## Objective

To understand what makes a password strong and test it against password strength tools

---
##Tools Used

[PasswordMeter](https://www.passwordmeter.com)
---
## Password Testing

| Password            | Components Used                              | Length | PasswordMeter Score (%) | Feedback Summary                          |
|---------------------|-----------------------------------------------|--------|--------------------------|-------------------------------------------|
| `123456`       | Numbers                           | 6     | 18%                      | Very Weak    |
| `Password`          | Uppercase + Lowercase                | 8      | 50%                      | Weak               |
| `Pass@123`     | Upper + Lower + Number + Symbol               | 8     | 88%                      | Strong       |
| `Lr1o7dBfHc9*$`      | Upper + Lower + Number + Multiple Symbols     | 13     | 100%                     | Very strong     |
| `qwerty`            | Lowercase only                                | 6      | 8%                       | Very Weak          |

---

## Best Practices for Strong Passwords

- Use **at least 12 characters**
- Include a mix of **uppercase, lowercase, numbers, and symbols**
- Avoid **common words or predictable substitutions**
- Do **not** use **personal information** (e.g., your name, birthday)
- Use **random phrases** or **passphrases**
- Never reuse passwords across different platforms

---

## Common Password Attacks

| Attack Type         | Description                                                                 | Defense Strategy                           |
|---------------------|-----------------------------------------------------------------------------|--------------------------------------------|
| **Brute Force**     | Tries every possible combination of characters                              | Use long, complex passwords                |
| **Dictionary**      | Tries common words and passwords                                             | Avoid dictionary words and names           |
| **Credential Stuffing** | Uses leaked passwords from other sites                                    | Use unique passwords per account           |
| **Phishing**        | Tricks users into revealing passwords via fake websites/emails              | Enable 2FA, verify site authenticity       |

---

## Password Complexity & Security

| Complexity Level     | Score | Security Level |
|----------------------|--------------------------|----------------|
| Simple (`123456`)     |   4%   | Very Weak     |
| Moderate (`Password`)  | 26% | Moderate      |
| Strong (`Pass@123`) | 77% | Strong        |
| Very Strong (`Lr1o7dBfHc9*$`) | 100% | Very Strong    |

---

## Summary

- The **longer** and **more complex**, the better.
- **Unpredictable** passwords are much harder to crack.
- Use **passphrases** that are long but memorable:
