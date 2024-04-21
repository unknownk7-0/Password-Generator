Password-Generator
This project serves as a Java Console Application designed to generate random passwords and assess their strength.

Introduction
In today's digital era, where security breaches and data leaks are all too common, the significance of robust, distinctive passwords cannot be overstated. Engaged in a variety of online activities, ranging from social media platforms to online banking, I frequently encounter the challenging task of creating new, secure passwords for each account.

Recognizing the need for a streamlined solution, I embarked on developing a Java-based password generator program. Its primary objective is to ease the burden of manually devising passwords by automatically generating strong, randomized passwords that adhere to modern security standards.

Functionalities
1. Generating a Password:
    Users respond with "Yes" or "No" to prompts regarding the use of uppercase letters, lowercase letters, numbers, or symbols.
    Users then input the desired length of the password.
    A password alphabet is crafted based on user responses, forming a string containing the selected characters.
    Random characters from the password alphabet are chosen and amalgamated to create a completely random string according to user preferences.
    The generated password is subsequently showcased on the console.
2. Checking a Password's Strength:
    Password strength is evaluated based on the following criteria:
    Usage of uppercase letters
    Usage of lowercase letters
    Usage of numbers
    Usage of symbols
    Password length being 8 or more (8 often serves as the minimum required length for a decent password).
    Password length being 16 or more (16 is deemed the minimum length for a good password).
    These criteria contribute to determining a score for the password, thereby indicating its strength level to the user (weak/medium/good/great).

3. Displaying Useful Information:
    A supplementary feature offers informative insights to users on password security via console messages. It covers aspects such as the avoidance of password reuse, character repetition, keyboard patterns, dictionary words, letter or number sequences, and more.