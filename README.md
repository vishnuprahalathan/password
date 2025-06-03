# 🔐 Task 6 – Password Strength Evaluation

## 🎯 Objective
To understand what makes a password strong by testing various passwords on [passwordmeter.com](https://www.passwordmeter.com) and analyzing their scores, structure, and security weaknesses.

---

## 🧪 Passwords Tested & Results

| Password                     | Score | Strength      | Observations |
|------------------------------|-------|---------------|--------------|
| `12345678910`                | 9%    | Very Weak     | Only numbers, highly predictable and sequential |
| `abc123`                     | 32%   | Weak          | Short, common pattern, lacks uppercase/symbols |
| `P@ssw0rd`                   | 68%   | Strong        | Meets most requirements but predictable word |
| `A1b2C3d4`                   | 86%   | Very Strong   | Good character mix, no repetition or sequences |
| `Tm#92wPq%LkZ`               | 100%  | Very Strong   | High entropy, includes all character types |
| `correcthorsebatterystaple` | 25%   | Weak (Tool)   | Weak by score, but a strong real-world passphrase |

---

## 🔎 Key Insights

### ✅ Best Practices for Strong Passwords
- Use **12+ characters**
- Mix **uppercase**, **lowercase**, **numbers**, and **symbols**
- Avoid dictionary words, patterns, and sequences
- Use **passphrases** for memorable yet secure options
- Never reuse passwords across accounts
- Enable **Multi-Factor Authentication (MFA)**

### 🔓 Common Attacks Researched
| Attack Type       | Description |
|-------------------|-------------|
| **Brute Force**   | Attempts every possible combination |
| **Dictionary**    | Uses common password lists |
| **Credential Stuffing** | Tries breached username-password pairs |
| **Phishing**      | Tricks users into entering passwords |

---

## 🛠 Tools Used
- [https://www.passwordmeter.com](https://www.passwordmeter.com)
- Google (for attack research & best practices)

---

## 📸 Screenshots
Screenshots of each tested password and its detailed score breakdown are included in the repository.

---

## 📝 Conclusion
This task helped reinforce the importance of using strong, complex, and unique passwords. It also demonstrated how password length and diversity drastically impact resistance against attacks like brute force or dictionary attacks. Passphrases like `correcthorsebatterystaple` are underrated by tools but strong in practice due to their length and unpredictability.

