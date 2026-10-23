# UofG IBM Qiskit Fall Fest 2026 – Workshop Materials

Workshop notebooks and presentation slides from the University of Glasgow IBM Qiskit Fall Fest 2026.

Event website: https://neonel21.github.io/UofG-IBM-Qiskit-Fall-Fest/

## Contents

### Workshops

| File | Description |
|---|---|
| [`workshops/Qiskit 101 Hands-on.ipynb`](workshops/Qiskit%20101%20Hands-on.ipynb) | Introductory hands-on: installing Qiskit, building circuits, and running on real IBM quantum hardware |

### Presentations

| File | Description |
|---|---|
| [`presentations/QiskitFallFest_IntroToQuantum.pptx`](presentations/QiskitFallFest_IntroToQuantum.pptx) | Introduction to quantum computing |
| [`presentations/Kiran Kaur Raina - Quantum Reality Security and Education.pdf`](presentations/Kiran%20Kaur%20Raina%20-%20Quantum%20Reality%20Security%20and%20Education.pdf) | *Quantum Reality: Why Security and Education Decide Everything* – Kiran Kaur Raina (NucleQi) |

## Running the workshop

```bash
pip install "qiskit[visualization]" qiskit-ibm-runtime qiskit-aer jupyter
jupyter notebook "workshops/Qiskit 101 Hands-on.ipynb"
```

To run on real quantum hardware you need a free IBM Quantum account. Follow the setup steps in the notebook to add your own API key and CRN.

> **Never commit your API key.** If you fork this repo, keep the placeholder values in the notebook and use `QiskitRuntimeService.save_account()` to store your credentials locally.

## Credits

Slides are the work of their respective speakers and are shared with permission for educational use.
