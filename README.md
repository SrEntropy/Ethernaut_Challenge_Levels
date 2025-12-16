# Ethernaut Challenge Levels

This repository contains solutions, notes, and walkthroughs for the **Ethernaut** smart contract security challenges.  
Ethernaut is an educational game by OpenZeppelin where each level is a vulnerable smart contract that must be exploited to advance.  
The repo documents how to approach, analyze, and solve each challenge.

---

## Project Overview
Smart contract security is critical in blockchain development.  
Ethernaut provides hands‑on puzzles that simulate real vulnerabilities.  
By solving them, developers learn how exploits work and how to defend against them.  
This repo captures solutions and explanations for each level, serving as a reference and study guide.

---

## Dataset / Levels
Each file corresponds to a challenge:
- **Delegation.md** → Function delegation and `delegatecall` misuse
- **Elevator.md** → Logic manipulation with interfaces
- **Force.md** → Forcing Ether into contracts
- **GatekeeperOne.md** → Access control and tricky modifiers
- **King.md** → Denial of service via contract ownership
- **Privacy.md** → Storage layout and data exposure
- **Reentrance.md** → Classic reentrancy vulnerability
- **Telephone.md** → Ownership transfer flaws
- **Token.md** → Arithmetic overflow/underflow
- **Vault.md** → Reading private storage variables

---

## Pipeline Summary
1. **Read the challenge contract**  
2. **Identify the vulnerability** (e.g., reentrancy, delegatecall misuse)  
3. **Craft exploit code or transaction sequence**  
4. **Document the solution** in Markdown for clarity  
5. **Reflect on mitigation strategies** for secure development  

---

## How to Run
Clone the repo and open the Markdown files for each level:
```bash
git clone https://github.com/yourusername/Ethernaut_Challenge_Levels.git
cd Ethernaut_Challenge_Levels
