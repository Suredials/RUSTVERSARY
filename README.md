# 🦀 RUSTVERSARY 🦀

Welcome to the RustVersary repository! This is a curated collection of tools and scripts that I've developed for malware development using Rust. 🛡️

The repository is structured to reflect the diverse set of skills required for the exam, ranging from enumeration scripts, exploitation tools, to post-exploitation scripts and various utility tools that enhance the penetration testing process. 🕵️‍♂️

Each tool and script is documented to explain its purpose, usage, and any prerequisites needed for its operation. This toolkit is intended to serve not only as my personal arsenal for security assessment challenges but also as a resource for fellow security enthusiasts and professionals who are on the same path towards mastering offensive security techniques. 🔍

Feel free to explore, use, and contribute to this toolkit as we delve into the world of cybersecurity. 🌐

## 📚 TOOLKIT CATALOG
### 💉 PROCESS INJECTION
| Script/Technique                                                                                                                             | Description                                                                                                                                                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Thread Execution Hijacking](https://github.com/Suredials/RUSTVERSARY/blob/main/PROCESS%20INJECTION/thread_execution_hijacking/src/main.rs)	 | Adversaries may inject malicious code into hijacked processes in order to evade process-based defenses as well as possibly elevate privileges. Thread Execution Hijacking is a method of executing arbitrary code in the address space of a separate live process [^1]. |
| [Process Hollowing](https://github.com/Suredials/RUSTVERSARY/blob/main/PROCESS%20INJECTION/process_hollowing/src/main.rs)                    | Adversaries may inject malicious code into suspended and hollowed processes in order to evade process-based defenses. Process hollowing is a method of executing arbitrary code in the address space of a separate live process [^2].                                   |
                                                                                                                                                                                                                                                                | 
## 🤝 HOW TO CONTRIBUTE
Contributions are welcome! If you have any fixes, improvements, or tools to add, please feel free to submit a pull request. 💡

## ⚠️ DISCLAIMER
These tools and scripts are provided for educational purposes only. Unauthorized testing of networks and systems is illegal. Always obtain permission before attempting any penetration testing.

` Happy Hacking! 😄 `

[^1]: [Process Injection: Thread Execution Hijacking](https://attack.mitre.org/techniques/T1055/003/)

[^2]: [Process Injection: Process Hollowing](https://attack.mitre.org/techniques/T1055/012/)
