# Cybersecurity
This repository houses the code utilized during my Master's lesson, providing a dedicated focus on cybersecurity implementation using the Python programming language.

## Timing Attack

A timing attack is a type of side-channel attack that exploits variations in the time taken to perform certain operations or processes within a system. The attacker leverages these timing differences to infer sensitive information, such as cryptographic keys or secret data, by analyzing the execution time of the target system's operations.

Timing attacks rely on the principle that the time taken to perform certain operations may vary depending on the data being processed or the internal state of the system. By carefully measuring and comparing the execution times of specific operations, an attacker can deduce patterns or correlations that reveal valuable information about the system's internals.

Timing attacks can be challenging to mitigate as they often require precise measurements and statistical analysis to extract meaningful data. Countermeasures against timing attacks typically involve implementing consistent and constant-time operations, where the execution time is independent of the processed data or sensitive information. This approach helps eliminate timing variations and prevents attackers from extracting information through timing analysis.

It is important to note that timing attacks can be applied in various contexts beyond cryptography, such as password guessing, authentication systems, or even web applications. System designers and developers need to be aware of the potential vulnerabilities associated with timing attacks and employ appropriate security measures to mitigate the risk of such attacks.

In this situtation the purpose of the timing attack was to guess a password.
