Writing

# DG Interns HUB - Week 1 README

## 1\. Week 1 Objective

Build a safe home lab environment and develop foundational skills in Linux, networking, and cybersecurity concepts. Gain practical experience through virtual machine configuration, Linux command-line exercises, network testing, and beginner-friendly cybersecurity labs.

## 2\. Folder Structure

The following directory structure will be used to organize all Week 1 notes, practical findings, lab writeups, and final deliverables.

```
DG Interns HUB/
└── Week 1/
    ├── Notes/
    │   ├── Cybersecurity and CIA Triad
    │   ├── SOC vs VAPT vs Incident Response
    │   ├── OSI vs TCP-IP and Layer Attacks
    │   ├── IP, MAC, DNS, DHCP and Ports
    │   ├── Linux Filesystem, Permissions and SUID
    │   ├── Threat, Vulnerability, Risk and Exploit
    │   ├── VM Networking Modes
    │   ├── Legal and Ethical Basics
    │   └── Lab Safety Checklist
    │
    ├── Writeups/
    │   ├── TryHackMe Room Writeups/
    │   │   └── One file per completed room
    │   └── OverTheWire Bandit/
    │       └── One file per level (0-10)
    │
    ├── Findings/
    │   ├── Lab Setup/
    │   │   └── VM list, IPs, pings, adapter settings and snapshots
    │   ├── Linux Practice/
    │   │   └── Users, groups, shared folder permissions, 30 command outputs, and cron job
    │   ├── Network Map/
    │   │   └── Network inventory and draw.io diagram exports
    │   └── Over the Wire Bandit/
    │       └── Completion evidence (no passwords)
    │
    ├── Cheat Sheet/
    │   └── Linux Command - What It Does - When to Use It
    │
    ├── Week 1 Weekly Work Report.pdf
    ├── Week 1 Presentation Report.pptx
    └── Week 1 README.docx
```

## 3\. Weekly Workflow

Complete the following activities in sequence and maintain evidence of the work performed.

### Step 1: Prepare Theory Notes

- Read all assigned cybersecurity and networking topics.
- Write the notes in your own words to demonstrate understanding.
- Include relevant definitions, examples, and key takeaways.
- Cover the CIA Triad, SOC, VAPT, incident response, network models, common protocols, Linux permissions, risk concepts, and ethical responsibilities.

### Step 2: Set Up and Isolate Virtual Machines

- Create and configure the required virtual machines.
- Use **Host-only networking** or a carefully configured **NAT Network**, depending on lab requirements.
- Keep vulnerable practice machines isolated from the public internet and unrelated personal devices.
- Take snapshots before making significant configuration changes.

### Step 3: Record Lab Network Details

For each virtual machine, document:

- VM name and operating system.
- IP address and subnet mask or prefix.
- Default gateway, where applicable.
- DNS server configuration.
- Network adapter mode.
- Relevant adapter settings and snapshot details.

Save the information in `Findings/Lab Setup/`.

### Step 4: Test and Document Connectivity

- Check network configuration using appropriate Linux commands.
- Test connectivity between the intended lab machines.
- Perform ping tests where ICMP traffic is permitted.
- Save genuine screenshots and command outputs.
- Record the results, including failed tests and their possible causes.

Store the evidence in `Findings/Lab Setup/`.

### Step 5: Practice Linux Administration

On Ubuntu, complete the assigned exercises involving:

- User and group creation and management.
- File and directory permissions.
- Shared-folder configuration and access control.
- Common Linux commands, with at least 30 documented command outputs.
- Creating and verifying a cron job.

Save commands, outputs, explanations, and screenshots in `Findings/Linux Practice/`.

### Step 6: Complete Cybersecurity Learning Labs

- Complete each assigned TryHackMe room.
- Write a separate report for every completed room.
- Complete OverTheWire Bandit levels 0–10.
- Document the approach, commands used, challenges encountered, and lessons learned.
- Include genuine completion evidence where appropriate.

**Security requirement:** Never include passwords, tokens, private keys, or other secrets in writeups, screenshots, reports, or shared files.

### Step 7: Create the Network Map and Linux Cheat Sheet

- Prepare a network inventory of the lab machines.
- Draw the network topology using draw.io.
- Export and save the diagram in `Findings/Network Map/`.
- Create a Linux command cheat sheet containing:
  - Command
  - What it does
  - When to use it
  - Example usage, where useful

Save the cheat sheet in `Cheat Sheet/`.

### Step 8: Prepare the Final Deliverables

Complete the following documents:

1. **Week 1 Weekly Work Report.pdf** - Summary of objectives, activities, practical work, findings, challenges, and outcomes.
2. **Week 1 Presentation Report.pptx** — Presentation of the lab setup, key concepts, practical exercises, evidence, and learning outcomes.
3. **Week 1 README.docx** — Documentation of the folder structure, weekly objectives, workflow, and completion status.

Ensure that each deliverable accurately reflects the work completed.

### Step 9: Final Review

Before submitting or sharing the project:

- Verify that all expected folders and files are present.
- Check that reports contain no unfinished placeholders.
- Confirm the accuracy of technical explanations and command outputs.
- Ensure screenshots are genuine, readable, and relevant.
- Check that the network diagram matches the actual lab setup.
- Remove passwords, tokens, private keys, and other sensitive information.
- Review the formatting, spelling, and readability of all deliverables.

## 4\. Lab Safety and Ethical Guidelines

- Perform exercises only on systems you own or have explicit permission to test.
- Use isolated virtual machines for vulnerable systems and security experiments.
- Do not scan, attack, or access unauthorized systems or networks.
- Avoid exposing vulnerable machines directly to the public internet.
- Use snapshots and backups to recover from configuration mistakes.
- Never publish credentials or sensitive system information.
- Document activities honestly and use only your own work as evidence.

## 5\. Expected Week 1 Outcomes

By the end of Week 1, the following outcomes should be achieved:

- Foundational cybersecurity theory notes completed.
- Virtual machines configured with appropriate network isolation.
- VM network details recorded and connectivity tests documented.
- Linux users, groups, permissions, and shared-folder exercises completed.
- At least 30 Linux command outputs documented.
- A cron job created and verified.
- Assigned TryHackMe rooms completed and documented.
- OverTheWire Bandit levels 0–10 completed and documented.
- Network inventory and diagram completed.
- Linux command cheat sheet completed.
- Weekly work report and presentation completed.
- README reviewed and all evidence checked for accuracy and secrets.

## 6\. Conclusion

Week 1 establishes the foundation for practical cybersecurity learning by combining theoretical knowledge with hands-on Linux administration, networking, and beginner-level security exercises. Maintaining an organized folder structure, collecting genuine evidence, following safe lab practices, and documenting each activity will make the work easier to review and build upon in subsequent weeks.
