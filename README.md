# Installation and Setup of Node.js Environment


### Step 1: Installing Node.js
- Installation method: official installer
- The stable **Node.js LTS** version was downloaded from the official website [nodejs.org](https://nodejs.org)
- The `.msi` installer was launched, and the installation was completed using default settings

---

### Step 2: Verifying Installation
To confirm successful installation, the following commands were executed in the terminal (PowerShell / CMD):

```bash
node -v
npm -v
```

**Expected result:** display of Node.js and npm version numbers  

<img width="361" height="156" alt="Знімок екрана 2026-06-04 151116" src="https://github.com/user-attachments/assets/8f1b7517-a862-4172-be7e-0603a0f4eeb2" />


---

### Step 3: Working in the REPL Environment
The REPL interactive environment was started using the command:

```bash
node
```

Basic operations were executed in the REPL:

```javascript
5 + 10
20 - 7
```

The REPL successfully performed the Read → Evaluate → Print → Loop cycle.

<img width="417" height="206" alt="Знімок екрана 2026-06-04 151133" src="https://github.com/user-attachments/assets/0c786ec2-9618-4887-9584-12b235dbf32e" />


---

### Step 4: Creating and Running `main.js`

A file named `main.js` was created with the following code:

```javascript
const a = 10;
const b = 5;

console.log(`Sum: ${a + b}`);
console.log(`Difference: ${a - b}`);
console.log(`Product: ${a * b}`);
console.log(`Quotient: ${a / b}`);
```

To run the script, the following command was used:

```bash
node main.js
```

<img width="791" height="207" alt="Знімок екрана 2026-06-04 151407" src="https://github.com/user-attachments/assets/2f1b395e-0e0a-44f5-9bb7-be904a0f183a" />

---
