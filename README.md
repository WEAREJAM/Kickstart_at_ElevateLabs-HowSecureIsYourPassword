# Kickstart_at_ElevateLabs-HowSecureIsYourPassword

# How Secure Is Your Password?

Do you know that **any password can be cracked** with brute force and other techniques?  
The real difference lies in **time** – how long it takes to break.  

If your password is just your name or a few numbers, it can be cracked in **seconds** using freely available tools. But by making it more complex (adding uppercase, special characters, and numbers), we can **push the limit** so that it takes **months or even years** to crack.  

This project demonstrates how password strength works, how attackers create targeted wordlists, and what we can do to secure our accounts.

---

## Password Strength Demo

I used [Bitwarden Password Strength Tool](https://bitwarden.com/password-strength/) to test different password combinations.  

- **Trial 1: Just a name** → Weak (cracked in < 1 sec)  
- **Trial 2: Added special characters** → Weak (2 seconds)  
- **Trial 3: Uppercase + longer password** → Better (3 hours)  
- **Trial 4: Mixed special characters + numbers** → Strong (5 months)  

Key takeaway: Adding variety (uppercase, lowercase, numbers, symbols) significantly increases cracking time.  

---

## Brute Force & Wordlist Tools

Two common brute-forcing tools:  

- Hydra  
- John the Ripper  

These tools work best when attackers already have some personal information.  

---

## Creating Custom Wordlists with CUPP  

Attackers can generate wordlists using **CUPP (Common User Passwords Profiler)**.  

This lets attackers build targeted wordlists based on:

First/last name

Date of birth

Pet names

Favorite words

Numbers & special characters

With such custom lists, the chance of your password being guessed increases drastically.

## Final Layer of Security: MFA

Even if your password is cracked, enabling Multi-Factor Authentication (MFA) makes it almost impossible for attackers to access your account.

## Conclusion

Every password can be cracked – but we can make it harder.

Use long, complex, unique passwords.

Always enable MFA for maximum protection.
