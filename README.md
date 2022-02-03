# MITRE ATT&CK Notes Template

**Current ATT&CK Version**: [v10.1](https://attack.mitre.org/versions/v10/)

In an effort to organize the notes I take during courses and engagements I have created this template based on the MITRE ATT&CK framework. It was created with the use of [Obsidian](https://obsidian.md) in mind, so it uses it's linking syntax. If you use a different note taking system, it shouldn't be too difficult to change this.

Currently, only the Enterprise domain is covered in this repo. If/when I require the Mobile or ICS domains, I will include those here as well.

## Structure

```
├── ATT&CK.md <- Main page with links to the corresponding tactics
├── Tactics
│   ├── Collection.md <- Every tactic page links to the techniques linked to that tactic
│   ├── Command and Control.md
│   ├── Credential Access.md
│   ├── Defense Evasion.md
│   ├── Discovery.md
│   ├── Execution.md
│   ├── Exfiltration.md
│   ├── Impact.md
│   ├── Initial Access.md
│   ├── Lateral Movement.md
│   ├── Persistence.md
│   ├── Privilege Escalation.md
│   ├── Reconnaissance.md
│   └── Resource Development.md
└── Techniques
    ├── *.md <- Every technique page links to the corresponding sub-techniques
```
