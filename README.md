# pass-strength

## Aim

To evaluate the strength of different passwords using a password strength checker and understand how password length, complexity, randomness, and predictability affect security.

## Objective

* To create passwords with different levels of strength.
* To test each password using a password strength checker.
* To compare the strength and feedback provided by the tool.
* To identify best practices for creating strong passwords.
* To understand common password attacks such as **brute-force** and **dictionary attacks**.
* To analyze how password complexity affects resistance to password attacks.
* To understand the importance of unique passwords and Authentication.

## Tools Used

| Tool                                       | Purpose                                         |
| ------------------------------------------ | ----------------------------------------------- |
| **passwordmeter.com Password Strength Checker** | To evaluate the strength of sample passwords    |
| **Web Browser**                            | To access and use the password strength checker |


## Password Strength Testing

Five sample passwords were created with increasing levels of complexity and evaluated using a password strength checker.

| Level | Sample Password        | Strength    | Score / Feedback                                                                        |
| ----- | ---------------------- | ----------- | --------------------------------------------------------------------------------------- |
| 1     | `password123`          | Very Weak   | Common password pattern; easy to guess                                                  |
| 2     | `Lalitha@123`          | Weak        | Contains uppercase, lowercase, numbers and symbols, but uses a predictable name/pattern |
| 3     | `Cyber@2026!`          | Medium      | Good character variety, but contains a predictable word and year                        |
| 4     | `Cyb3r!Shield#92`      | Strong      | Longer and uses uppercase, lowercase, numbers and special characters                    |
| 5     | `vQ7!mZ@2#Lp9$Xr4&Ks8` | Very Strong | Long, random and contains a wide variety of characters                                  |


### Best Practices for Creating Strong Passwords

* Use passwords that are **long** and difficult to predict.
* Prefer **16 or more characters** for important accounts.
* Use a combination of uppercase and lowercase letters, numbers and special characters when appropriate.
* Avoid names, birthdays, phone numbers and other easily available personal information.
* Avoid common passwords such as `password123`, `123456`, or `qwerty`.
* Do not reuse the same password across multiple accounts.
* Use a **unique password for every important account**.
* Consider using a reputable password manager to generate and store unique passwords.
* Enable **multi-factor authentication (MFA)** whenever available.
* Avoid predictable substitutions such as replacing `a` with `@` or `e` with `3` when the underlying word remains obvious.

### Tips Learned from the Evaluation

The password testing demonstrated that:

1. **Length is important** – longer passwords generally provide significantly more possible combinations.
2. **Randomness matters** – predictable words, names and years reduce password strength.
3. **Complexity helps** – using different character types increases the search space.
4. **Common patterns should be avoided** – attackers can automatically test common password patterns.
5. **Uniqueness is essential** – a strong password should not be reused across different services.
6. **Password managers are useful** – they can create long, random and unique passwords without requiring users to memorize them.

### Common Password Attacks

#### Brute-Force Attack

A brute-force attack attempts many possible password combinations until the correct password is found.

**Example:**

An attacker may systematically try:

```text
aaaa
aaab
aaac
...
```

As password length and randomness increase, the number of possible combinations increases, making brute-force attacks more difficult.

#### Dictionary Attack

A dictionary attack uses a list of commonly used words, passwords and combinations instead of trying every possible character combination.

**Example password lists may contain:**

```text
password
password123
welcome
admin
qwerty
```

Passwords based on common words or predictable patterns are therefore more vulnerable to dictionary attacks.

#### Credential Stuffing

Credential stuffing uses username/password combinations obtained from previous data breaches and attempts them on other websites. Password reuse makes this attack particularly effective.

### 8. How Password Complexity Affects Security

Password security depends on factors such as **length, randomness, uniqueness and predictability**.

A short and predictable password has a relatively small search space and can be easier for automated attacks to guess.

For example:

```text
password123
```

is weak because it contains a common word and predictable numbers.

A longer random password such as:

```text
vQ7!mZ@2#Lp9$Xr4&Ks8
```

has a much larger search space and is significantly harder to guess through brute-force or dictionary-based methods.

### Conclusion

The password-strength evaluation showed that increasing password length, randomness and uniqueness can greatly improve resistance to common password attacks. Strong passwords should be long, unpredictable and unique for each account. Combining strong passwords with a password manager and multi-factor authentication provides better overall account security.

