# Cybersecurity
This repository houses the code utilized during my Master's lesson, providing a dedicated focus on cybersecurity implementation using the Python programming language.

## Timing Attack

A timing attack is a type of side-channel attack that exploits variations in the time taken to perform certain operations or processes within a system. The attacker leverages these timing differences to infer sensitive information, such as cryptographic keys or secret data, by analyzing the execution time of the target system's operations.

Timing attacks rely on the principle that the time taken to perform certain operations may vary depending on the data being processed or the internal state of the system. By carefully measuring and comparing the execution times of specific operations, an attacker can deduce patterns or correlations that reveal valuable information about the system's internals.

Timing attacks can be challenging to mitigate as they often require precise measurements and statistical analysis to extract meaningful data. Countermeasures against timing attacks typically involve implementing consistent and constant-time operations, where the execution time is independent of the processed data or sensitive information. This approach helps eliminate timing variations and prevents attackers from extracting information through timing analysis.

It is important to note that timing attacks can be applied in various contexts beyond cryptography, such as password guessing, authentication systems, or even web applications. System designers and developers need to be aware of the potential vulnerabilities associated with timing attacks and employ appropriate security measures to mitigate the risk of such attacks.

In this situtation the purpose of the timing attack was to guess a password.

## Brute force

For privacy reason all the hash in the code have been remove. 

A brute force attack is a systematic and exhaustive method employed by an attacker to gain unauthorized access to a system or decrypt encrypted data. It involves trying all possible combinations of passwords, encryption keys, or other credentials until the correct one is discovered. This method relies on the assumption that the correct solution exists within the limited set of possibilities and that it can be determined through an exhaustive search.

Brute force attacks are typically used when other, more efficient attack methods, such as exploiting vulnerabilities or weaknesses in the system, are not available or feasible. These attacks can be resource-intensive and time-consuming, as they involve iterating through a large number of potential solutions.

In the context of password attacks, a brute force attack typically involves systematically trying every possible combination of characters, starting from the shortest to the longest passwords. The attacker uses automated tools or scripts that generate and test these combinations against the target system until the correct password is found.

