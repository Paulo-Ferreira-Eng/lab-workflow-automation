Lab Workflow Automation

This project was developed as an emergency operational solution for a public municipal laboratory serving approximately 100,000 inhabitants (city and surrounding districts).
The laboratory experienced a demand increase from ~40 to ~60 patients per day. Each patient required, on average, 15–20 laboratory exams.
At the time, internal work forms were manually created using spreadsheets. With the increased demand, this process became operationally unsustainable.
This application automated the generation of sector-specific laboratory work forms, allowing the laboratory to maintain service capacity during the transition to a fully integrated commercial system.

Problem

The main bottleneck was the manual preparation of work sheets:
- Exams had to be manually separated by sector
- Patient data was retyped multiple times
- Process was time-consuming and error-prone
- No scalable workflow existed
- A lightweight and fast-to-deploy solution was required.

Solution

A local Python desktop application with:
- Simple graphical user interface
- Patient data input form
- Checkbox-based exam selection
- Automatic sector separation
- Automatic layout formatting (4-column structure)
- One-click generation and printing
- Local file saving for reprint purposes

The application required no server, no network configuration, and no external dependencies.

Solution

A local Python desktop application with:
- Simple graphical user interface
- Patient data input form
- Checkbox-based exam selection
- Automatic sector separation
- Automatic layout formatting (4-column structure)
- One-click generation and printing
- Local file saving for reprint purposes

The application required no server, no network configuration, and no external dependencies.

Results

- Supported demand increase from 40 → 60 patients/day
- Operated continuously for approximately 1 year
- No recorded technical failures during usage
- Reduced manual workload significantly
- Eliminated spreadsheet-based bottleneck

Project Lifecycle

After a public procurement process, a professional laboratory management system with full equipment integration was implemented.
This solution was then discontinued as originally intended.

Limitations

- Single-machine operation
- No multi-user support
- No database integration
- Not intended as a permanent laboratory management system

Purpose of Publication

- This repository serves as a case study in:
- Workflow modeling
- Process automation
- Rapid deployment under operational constraints
- Technical decision-making in public sector environments
- All data in this repository is fictional and for demonstration purposes only.
