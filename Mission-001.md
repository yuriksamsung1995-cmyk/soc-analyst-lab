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

1. Objective

Practice analyzing Windows Security Events.

2. Environment

* Operating System: Windows 11
* Tool: Windows Event Viewer
* Log: Windows Security

3. Events Observed

Event ID	Description
4624	Successful logon
4672	Special privileges assigned to new logon
5379	Credential Manager credentials were read

4. Analysis

During this exercise, I examined Windows Security Events and learned how to identify successful logons, privileged logons and access to stored credentials.

5. Conclusion

Individual events require additional context before determining whether suspicious activity occurred.

6. Skills Practiced

* Windows Event Viewer
* Security Logs
* Event ID analysis
* Basic SOC investigation

Status: Completed