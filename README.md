
Glossary:

- ***Laegna Logecs*** - my logical system, such as symbolic logic and math.

- ***Laegna Logecs*** - my computational logic system, where engineering considerations cost more than an explicit proof, altough what Djikstra said.

  **“Program testing can be used to show the presence of bugs, but never to show their absence!”**  
  — Edsger W. Dijkstra, *“Notes on Structured Programming”*, April 1970 

Emulators:

https://ten-emulator-develop-aaou.bolt.host/ - emulation of single states of Ten, where both channels can be set by current value, and the state's combination will be analyzed.

https://ten-ether-weave.lovable.app/ - whole Ten with all internal states can be programmed, and result becomes visible (as described in the text).

# LaeLogecs Logex — Repository Guide  
### Main Documents, Links, and Summaries

This repository contains the core texts of **Laegna Logecs**, the symbolic and computational logic system underlying Laegna mathematics, Ten Machines, and AlphaLayer semantics.  
Below are the primary documents, their roles, and how they connect.

---

## 1. Ten Emulator  
**Document:**  
https://github.com/tambetvali/LaeLogecsLogex/blob/main/Ten%20Emulator.md

**Summary:**  
Ten Emulator is the **first operational machine** of Laegna Logecs.  
It implements the three‑band Ten structure:

- **User band** (T/F)  
- **Short‑term band** (A/O)  
- **Long‑term band** (E/I)

The document explains:

- diagonal vs. horizontal‑vertical formats  
- mixed‑band reduction (IO→I, IA→O, EO→A, EA→E)  
- goal semantics (True / False / Unset)  
- color logic (local/global success/failure)  
- unknown and partial states  
- interpreter model  
- mathematical formalization  
- full UI layout and emulator behavior

It is the **execution layer** of Laegna Logecs: the first place where the logic becomes a working machine.

**Related emulators:**

- Single‑state emulator:  
  https://ten-emulator-develop-aaou.bolt.host/  
  Lets you set both channels manually and observe the state combination.

- Full Ten machine emulator:  
  https://ten-ether-weave.lovable.app/  
  Allows programming all internal states and seeing the complete result.

---

## 2. AlphaLayer  
**Directory:**  
https://github.com/tambetvali/LaeLogecsLogex/tree/main/AlphaLayer

**Summary:**  
AlphaLayer is the **semantic physics** of Laegna Logecs.  
It defines:

- the four Laegna digits **I, O, A, E**  
- hologram half‑bits (Den)  
- octave logic (Z–X–Y bands)  
- zero as between‑digit acceleration point  
- dimensional reduction (base‑4 → base‑2)  
- cause‑entropy vs. goal‑entropy  
- local vs. global consistency  
- diagonal format and universal symmetry  
- the semantic substrate Ten Emulator must obey

AlphaLayer is not a machine — it is the **meaning layer**.  
Ten Emulator is built directly on top of it.

---

## 3. Glossary  
A short glossary for orientation:

- **Laegna Logecs (symbolic logic)**  
  The conceptual logic system: digits, bands, symmetries, hologram math.

- **Laegna Logecs (computational logic)**  
  The engineering logic system: machines, interpreters, emulators, execution.  
  Engineering constraints matter more than formal proofs — with Dijkstra’s reminder:

  > “Program testing can be used to show the presence of bugs,  
  > but never to show their absence.”  
  > — Edsger W. Dijkstra, *Notes on Structured Programming*, 1970

---

## 4. How the Documents Fit Together

**AlphaLayer → Ten Emulator → Emulators**

- **AlphaLayer** defines the semantics, digits, and symmetry rules.  
- **Ten Emulator** implements those rules as a working three‑band machine.  
- **Online emulators** let you experiment with Ten logic interactively.

Together they form the **first complete logic stack** of Laegna:

1. **Semantic layer** (AlphaLayer)  
2. **Execution layer** (Ten Emulator)  
3. **Interactive layer** (Emulators)

---

## 5. Additional Texts in the Project

The repository also contains:

- **Graphics** — visualizations of Ten, horizon logic, and machine layouts.  
- **Formal commentary** — interpreter specification and mathematical model.  
- **Horizon image** — conceptual future of Ten logic.  
- **Unmade Machine** — the meta‑layer describing what comes after Ten.

These texts expand Laegna Logecs beyond the Ten Emulator into a broader logic universe.

---

## 6. Purpose of This Repository

This project is the **canonical reference** for:

- Laegna digits  
- Laegna bands  
- Ten machines  
- AlphaLayer semantics  
- Laegna computational logic  
- Laegna symbolic logic  
- Future logic layers (post‑Ten)

It is the foundation of the Laegna Logecs ecosystem.

---
