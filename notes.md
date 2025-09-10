# notes.md — Methodology & commands

- Lab setup:
  - Attacker: Kali Linux (offline)
  - Target: Windows 7 (snapshot enabled)

- Recon:
  - Example scan: `nmap -sS -p 445,139 --script smb-* <target>`
  - Check SMB version using tools like `smbclient` or `rpcclient`

- Verification (non-destructive):
  - Use safe detection scripts or banner checks

- Documentation:
  - Save screenshots of scan output, detection, and shell prompt

- Lessons learned:
  - Always snapshot the VM before testing
  - Use patching and network segmentation to mitigate
