# firewall_config_steps



# 🧱 Task 4: Firewall Configuration (Windows)

## 🎯 Objective
Configure basic firewall rules to block and allow traffic using Windows Defender Firewall.

## 🧰 Tools Used
- Windows Defender Firewall with Advanced Security
- Windows 11 OS

## 🔧 Actions Performed
- Blocked inbound traffic on port 23 (Telnet)
- Allowed traffic on port 22 (SSH)
- Tested rules and removed after verification

## 💡 Outcome
- Learned how firewall filters network traffic
- Practiced rule creation/removal
- Understood port-level access control

- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🔧 Steps Performed

### 🔹 Block Port 23 (Telnet)
- Inbound Rule → New → Port → TCP → 23 → Block → All Profiles → Name: Block Telnet

### 🔹 Allow Port 22 (SSH)
- Inbound Rule → New → Port → TCP → 22 → Allow → All Profiles → Name: Allow SSH

### 🔹 Remove Rule
- Right-click on rule → Delete

### 📸 Screenshots
- block_telnet_rule.jpg
- allow_ssh_rule.jpg

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
