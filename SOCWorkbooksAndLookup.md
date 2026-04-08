# SOC Workbooks and Lookups — Writeup

## Assets and Identities

- **Looking at the identity inventory, what is the role of R.Lund at the company?**  
  Financial Advisor

- **Looking at the asset inventory, what data does HQ-FINFS-02 store?**  
  Financial Records

- **R.Lund accessed HQ-FINFS-02. Would you consider this normal behavior based on the inventory data (Yea/Nay)?**  
  Yea

---

## Network Diagrams

- **Looking at the network diagram, what service is running on port 10443?**  
  VPN

- **The attacker was assigned IP 10.10.0.53 after a successful VPN brute force. Which subnet does this IP belong to, and what subnet did they attempt to reach next?**  
  VPN Subnet → Database Subnet

- **After a successful VPN brute force, did the attacker successfully access the Database Subnet (TP/FP)?**  
  True Positive (TP) — firewall rules blocked access to the Database Subnet

---

## Workbooks Theory

- **Workbooks are designed to help which SOC role triage alerts correctly?**  
  SOC L1 Analyst

- **What is the step in a workbook where you gather additional context about users, assets, or IPs?**  
  Enrichment

- **Which HR system is commonly used in the room as a lookup source for identity information?**  
  BambooHR

---

## Workbooks Practice

- **What flag did you receive after completing the first workbook?**  
  `THM{the_most_common_soc_workbook}`

- **What flag did you receive after completing the second workbook?**  
  `THM{be_vigilant_with_powershell}`

- **What flag did you receive after completing the third workbook?**  
  `THM{asset_inventory_is_essential}`
