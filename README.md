# Password Cracking Lab – John the Ripper & Networkwalks Tools

A practical cybersecurity learning project documenting two password-recovery lab modules completed using John the Ripper (JTR), Johnny GUI, and Networkwalks online tools.

> **Scope and ethics:** This repository documents work performed in an authorized training environment using the lab-provided protected PDF. Password recovery and cracking techniques should only be used on files and systems you own or have explicit permission to test.

## Project overview

The project explores how password-protected PDF files can be assessed in a controlled lab. It demonstrates the role of password hashes and dictionary-based password recovery, and highlights why strong, unique passwords matter.

## Module 1 – Password Cracking with John the Ripper (JTR)

**Tools covered**
- John the Ripper
- Johnny graphical user interface (GUI)
- PDF hash extraction utility
- Windows Notepad for saving the extracted hash

**Lab workflow**
1. Install John the Ripper and the Johnny GUI.
2. Configure Johnny to use the `john.exe` executable from the John the Ripper `run` folder.
3. Obtain the hash from the lab-provided password-protected PDF.
4. Save the extracted hash in a text file (the task guide uses `hash1.txt`).
5. Load the hash file in Johnny and start the password-recovery attack.
6. Use the recovered password to open the protected lab PDF.

## Module 2 – Password Cracking with Networkwalks Tools

**Tools covered**
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web browser

**Lab workflow**
1. Open the lab-provided password-protected PDF.
2. Upload it to the Networkwalks Hash Calculator to extract its PDF hash.
3. Copy the complete hash value, beginning with `$pdf$`.
4. Open the Networkwalks Password Cracker and paste the hash.
5. Start the dictionary-based cracking process and wait for the result.
6. Use the recovered password to open the protected lab PDF.

## Evidence

The `evidence/` folder contains the three original screenshots supplied for this portfolio:

| Screenshot | Evidence description |
|---|---|
| `flag-01-cybersecurity-achievement.png` | Cybersecurity achievement flag |
| `flag-02-jtr-persistence-achievement.png` | JTR persistence achievement flag |
| `flag-03-networkwalks-achievement.png` | Networkwalks achievement flag |

These images are the flag-capture evidence provided for this repository. They are not step-by-step screenshots of every action in the two modules.

## Key learning outcomes

- Understanding the difference between encryption and hashing.
- Learning how password hashes can be extracted from protected PDF files.
- Becoming familiar with John the Ripper and its Johnny GUI.
- Understanding the basic workflow of dictionary-based password recovery.
- Recognizing the importance of strong, unique passwords and authorized security testing.

## Repository structure

```text
password-cracking-lab/
├── README.md
└── evidence/
    ├── flag-01-cybersecurity-achievement.png
    ├── flag-02-jtr-persistence-achievement.png
    └── flag-03-networkwalks-achievement.png
```

## Notes

- The training PDFs were used as project instructions and are intentionally not included in this repository.
- No protected PDF files, extracted password hashes, or recovered passwords are included.
- Before making this repository public, review the screenshots to ensure the visible challenge flag tokens are permitted to be shared publicly.
- Add any additional screenshots of your actual tool workflow if you want to document each step in greater detail.

## Acknowledgement

Training task materials: Networkwalks – Cybersecurity & Ethical Hacking Project Tasks.
