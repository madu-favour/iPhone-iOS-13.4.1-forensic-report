# iPhone iOS 13.4.1 Forensic Analysis

## Overview
This project documents a digital forensic analysis of an iPhone image running iOS 13.4.1.
The investigation was conducted in a Kali Linux environment running on VMware. The objective was to examine the extracted iOS file system, verify evidence integrity, and identify artefacts relevant to a digital forensic investigation.

## Objectives
- Verify the integrity of the forensic image using cryptographic hashes.
- Examine the extracted iOS file-system structure.
- Identify relevant application bundles and user-data containers.
- Examine plist configuration and metadata files.
- Analyse SQLite databases and their associated records.
- Identify digital artefacts that may support forensic investigations.

## Environment
- Kali Linux
- VMware
- iOS 13.4.1 forensic image

## Forensic Methodology
The investigation involved:
1. Verifying the integrity of the forensic image using hash values.
2. Examining the iOS file-system structure.
3. Identifying application directories and user-data containers.
4. Reviewing relevant `.plist` files.
5. Examining SQLite databases and associated artefacts.
6. Documenting findings and observations for forensic reporting.

## Key Areas Examined
- iOS file-system structure
- Application bundles
- User-data containers
- Property List (`.plist`) files
- SQLite databases
- Metadata and configuration artefacts
- File-system evidence

## Tools and Technologies
- Kali Linux
- VMware
- Hash verification tools
- File-system analysis tools
- SQLite database analysis

## Skills Demonstrated
- Digital Forensics
- Mobile Device Forensics
- Digital Evidence Handling
- Evidence Integrity Verification
- iOS File-System Analysis
- SQLite Database Analysis
- Plist Analysis
- Artefact Identification
- Forensic Documentation
- Analytical Problem-Solving
- Linux

## Key Findings
The forensic examination identified and documented relevant artefacts within the extracted iOS file system, including application data, configuration files, metadata and SQLite database records.

The analysis demonstrated how mobile-device artefacts can be examined and correlated to support digital forensic investigations.

Detailed findings, supporting analysis and evidence are contained in the forensic report included in this repository.

## Evidence
The repository contains the forensic report and supporting project materials.

> **Note:** Sensitive personal information and identifying data should be removed or redacted before sharing forensic evidence publicly.

## Disclaimer
This project was completed for educational and cybersecurity training purposes. The analysis was performed in a controlled forensic environment.
