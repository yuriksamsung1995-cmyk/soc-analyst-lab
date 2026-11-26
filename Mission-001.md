soc-analyst-lab/
│
├── README.md
│
├── Windows-Logs/
│   └── Mission-001.md
│
├── Network-Analysis/
│   └── Mission-002.md
│
└── SOC-Investigations/
    └── Mission-003.md
Mission 001 – Windows Security Logs

Objective

Practice analyzing Windows Security Events.

Environment

* Operating System: Windows 11
* Tool: Windows Event Viewer
* Log: Windows Security

Events Observed

Event ID	Description
4624	Successful logon
4672	Special privileges assigned to new logon
5379	Credential Manager credentials were read

Analysis

During this exercise, I examined Windows Security Events and learned how to identify successful logons, privileged logons and access to stored credentials.

Conclusion

Individual events require additional context before determining whether suspicious activity occurred.

Skills Practiced

* Windows Event Viewer
* Security Logs
* Event ID analysis
* Basic SOC investigation

Status: Completed