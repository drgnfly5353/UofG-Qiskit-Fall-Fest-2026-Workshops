# UofG IBM Qiskit Fall Fest 2026 – Workshop Materials

Welcome to the official materials repository for the **University of Glasgow IBM Qiskit Fall Fest 2026**, co-hosted with IBM Quantum.

This repository contains everything you need for the hands-on workshop and the slides from our speaker sessions. It will be updated as new material becomes available.

- **Date:** Saturday 24 October 2026
- **Venue:** Sir Alwyn Williams Building, School of Computing Science, University of Glasgow, 18 Lilybank Gardens, Glasgow G12 8RZ
- **Event website (schedule, speakers, online joining link):** https://neonel21.github.io/UofG-IBM-Qiskit-Fall-Fest/

## Contents

```
├── workshops/
│   └── Qiskit 101 Hands-on.ipynb
└── presentations/
    ├── QiskitFallFest_IntroToQuantum.pptx
    └── Kiran Kaur Raina - Quantum Reality Security and Education.pdf
```

### Workshop

| File | Description |
|---|---|
| [Qiskit 101 Hands-on.ipynb](workshops/Qiskit%20101%20Hands-on.ipynb) | **IBM Qiskit Hands-on Workshop** (11:00–13:00). Install Qiskit, build and visualise your first quantum circuits, run them on a simulator, and then on a real IBM quantum computer. |

### Presentations

| File | Description |
|---|---|
| [QiskitFallFest_IntroToQuantum.pptx](presentations/QiskitFallFest_IntroToQuantum.pptx) | Introduction to quantum computing |
| [Kiran Kaur Raina - Quantum Reality Security and Education.pdf](presentations/Kiran%20Kaur%20Raina%20-%20Quantum%20Reality%20Security%20and%20Education.pdf) | *Quantum Reality: Why Security and Education Decide Everything*, by Kiran Kaur Raina, founder of NucleQi |

## Before the workshop

Please do these steps before you arrive so we can spend the session on quantum computing rather than installation.

1. **Bring a laptop** with Python 3.10 or newer installed.
2. **Install the required packages:**
   ```bash
   pip install "qiskit[visualization]" qiskit-ibm-runtime qiskit-aer jupyter
   ```
3. **Create a free IBM Quantum account** at https://quantum.cloud.ibm.com. You will need it to run circuits on real quantum hardware. The notebook walks you through finding your API key and CRN.

## Getting the materials

**Option 1: Download ZIP (no Git needed).** Click the green **Code** button at the top of this page, then choose **Download ZIP**.

**Option 2: Clone with Git**
```bash
git clone https://github.com/drgnfly5353/UofG-Qiskit-Fall-Fest-2026-Workshops.git
cd UofG-Qiskit-Fall-Fest-2026-Workshops
```

Then open the notebook:
```bash
jupyter notebook "workshops/Qiskit 101 Hands-on.ipynb"
```

No setup? You can also preview the notebook directly on GitHub by clicking on it, or upload it to [Google Colab](https://colab.research.google.com).

You may also wish to directly access it through the [Colab Integration](https://colab.research.google.com/github/drgnfly5353/UofG-Qiskit-Fall-Fest-2026-Workshops/blob/main/<notebook>.ipynb).

## Keep your API key safe

Your IBM Quantum API key works like a password.

- Paste it **only** into your own copy of the notebook.
- **Never** commit it to GitHub or share it in chat.
- After running `QiskitRuntimeService.save_account(...)` once, your key is saved on your computer, so you can delete it from the notebook cell.

## Useful links

- [IBM Quantum Platform](https://quantum.cloud.ibm.com)
- [Qiskit documentation](https://quantum.cloud.ibm.com/docs)
- [IBM Quantum Learning](https://quantum.cloud.ibm.com/learning)
- [Qiskit Fall Fest 2026 global materials](https://github.com/Qiskit-Fall-Fest-2026)

## Credits

Organised by the University of Glasgow Quantum Computing Society with support from IBM Quantum.

Slides are the work of their respective speakers and are shared with their permission for educational use. Please credit the original authors if you reuse them.
