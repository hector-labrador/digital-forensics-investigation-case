# Digital Forensics Investigation – Windows Server Case

This project documents a structured digital forensic investigation conducted on a Windows Server disk image (E01 format), following proper chain of custody procedures and forensic integrity validation.

---

## Scope of the Investigation

- Evidence acquisition and documentation
- Chain of custody registration
- Hash verification and integrity validation
- Disk cloning using dc3dd
- Transfer to controlled analysis environment
- Artefact examination using OSForensics

---

## Technical Process

### Evidence Handling
- E01 forensic image format
- Integrity verification using `ewfverify`
- Hash validation (MD5 reference value)
- Controlled disk cloning to `.dd` format

### Artefact Analysis

The investigation included:

- System information analysis
- User account activity
- Web browsing history
- Remote Desktop connections
- Shellbags analysis
- Program execution logs

---

## Key Findings

- Activity outside official working hours
- Use of non-standard software
- Remote access attempts
- Command-line execution contrary to internal policy

---

## Methodological Principles Applied

- Chain of custody documentation
- Integrity preservation
- Controlled analysis environment
- Evidence validation through hash comparison

---

## Purpose

This project demonstrates practical experience in digital forensic methodology, evidence handling procedures, and artefact-based incident reconstruction.
