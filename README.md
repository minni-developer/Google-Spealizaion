# Google Cybersecurity Specialization – Portfolio Activities

A collection of hands-on activities, templates, and reference materials from the **Google Cybersecurity Professional Certificate / Specialization** on Coursera. The work covers security audits, risk assessment, network hardening, incident analysis with the NIST CSF, and practical Linux and SQL tasks.

Most deliverables are Word documents (`.docx`) designed to be used as cybersecurity portfolio pieces.

---

## Repository Structure

```
.
├── task 1/                  # Security audit – Botium Toys (Part 1)
├── task 2/                  # Security audit – Botium Toys (Part 2)
├── Google Network/
│   ├── task 1/              # Network hardening
│   └── task 2/              # Incident analysis with NIST CSF
└── Google Linux/
    ├── task 1/              # Linux file permissions
    └── task 2/              # SQL filtering
```

---

## Contents

### 1. Internal Security Audit – Botium Toys

A fictional small U.S. toy company with a growing worldwide online presence. The IT manager asks for an internal audit covering assets, controls, and regulatory compliance.

**`task 1/` – Conduct the audit**

| File | Description |
|---|---|
| `New Microsoft Word Document.docx` | Activity overview, scenario, and step-by-step instructions |
| `steps for botium.txt` | Plain-text summary of goals, risks, and the self-assessment criteria |
| `Botium-Toys_-Audit-scope-and-goals.docx` | Audit scope (permissions, controls, procedures, compliance) and goals |
| `Botium-Toys_-Risk-assessment.docx` | Asset inventory, risk description, and risk score (8/10, high) |
| `Controls-assessment.docx` | Administrative, technical, and physical controls, marked by priority |
| `Controls-assessment-exemplar.docx` | Reference example of a completed controls assessment |
| `Compliance-checklist-exemplar.docx` | Reference example covering GDPR, PCI DSS, SOC, and related standards |

**`task 2/` – Communicate the results**

| File | Description |
|---|---|
| `New Microsoft Word Document.docx` | Activity overview and instructions for writing the stakeholder memo |
| `Botium-Toys_-Audit-scope-and-goals.docx` | Audit scope and goals (same as above, for reference) |
| `Stakeholder-memorandum-exemplar.docx` | Example memo summarizing scope, goals, critical findings, and recommendations |

**Key themes:** NIST CSF alignment, principle of least privilege, separation of duties, disaster recovery, compliance with GDPR and PCI DSS.

---

### 2. Network Security – `Google Network/`

**`task 1/` – Network hardening**

| File | Description |
|---|---|
| `task.docx` | Scenario: a social media company suffers a data breach caused by undetected vulnerabilities |
| `Network-hardening-tools.xlsx` | Reference table of hardening methods: baseline configurations, configuration checks, disabling unused ports, encryption, firewall maintenance, hardware/software disposal, MFA |
| `Security-risk-assessment-report.docx` | Template: select up to three hardening tools and explain the recommendations |

**`task 2/` – Incident report analysis (NIST CSF)**

| File | Description |
|---|---|
| `task.docx` | Activity instructions for analyzing a network incident |
| `Applying-the-NIST-CSF-.docx` | Reading on the five core functions: Identify, Protect, Detect, Respond, Recover |
| `Incident-report-analysis.docx` | Blank incident report template |
| `Completed-Example-of-an-Incident-report-analysis.docx` | Worked example (a phishing email leading to unauthorized database access) |

---

### 3. Linux and SQL – `Google Linux/`

**`task 1/` – File permissions in Linux**

| File | Description |
|---|---|
| `...Current-file-permissions.docx` | Permissions of the files and subdirectory in `/home/researcher2/projects` |
| `...File-permissions-in-Linux.docx` | Project template: inspect permissions, read permission strings, and change permissions on files, hidden files, and directories |
| `...Instructions-for-including-Linux-commands.docx` | Guidelines for documenting commands and screenshots |

Commands practiced: `ls -la`, `chmod`, and working with hidden files and directories.

**`task 2/` – Filtering with SQL**

| File | Description |
|---|---|
| `...Table-formats.docx` | Schema of the `log_in_attempts` and `employees` tables |
| `...Apply-filters-to-SQL-queries.docx` | Project template with six query tasks (see below) |
| `...Instructions-for-including-SQL-queries.docx` | Guidelines for documenting queries |

Query tasks: after-hours failed logins, logins on specific dates, logins outside Mexico, employees in Marketing, employees in Finance or Sales, and employees not in IT. These use `WHERE` with `AND`, `OR`, `NOT`, and `LIKE`.

---

## Skills Demonstrated

- **Security auditing and risk assessment**: scoping an audit, inventorying assets, and scoring risk
- **Compliance awareness**: GDPR, PCI DSS, SOC, and FERC-NERC applicability
- **Security controls**: administrative, technical, and physical controls, classified as preventative, detective, corrective, or deterrent
- **Network hardening**: ports, firewalls, encryption, MFA, and baseline configurations
- **Incident response**: applying the NIST CSF to a real-world style incident
- **Linux**: reading and modifying file and directory permissions via the command line
- **SQL**: filtering security log data to investigate suspicious activity
- **Technical communication**: writing stakeholder-ready memos and reports

---

## How to Use This Repo

1. Browse the folder for the topic you are interested in.
2. Open the `.docx` and `.xlsx` files in Microsoft Word, Excel, Google Docs, or LibreOffice.
3. Use the `*-exemplar` and `Completed-Example` files as references when preparing your own work.
4. Use the blank templates (for example `Incident-report-analysis.docx`) for your own activities and portfolio.

> **Note:** Some files are original course templates or exemplars, and some are blank. Check each document to see whether it has been completed.

---

## Disclaimer

This repository is for **educational purposes**. The course materials, scenarios, and exemplars belong to Google / Coursera. Botium Toys is a fictional company used for training. No real organizational data is included.

---

## Acknowledgments

- [Google Cybersecurity Professional Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity) on Coursera
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)