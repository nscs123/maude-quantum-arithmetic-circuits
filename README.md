# Formal Verification of Quantum Arithmetic Circuits

## Basic Definitions of Quantum Computing Rules

- [CPX](./cpx.maude)
  - complex numbers
- [QC](./qc.maude)
  - quantum computing specifications
    - DIRAC: basic definition of qubits in vector.
    - MAT: Matrix operations in qunatum mechanics.
    - QC: Quantum Computing basic behaviors.

## Quantum Circuit List

[Quantum Circuit List](./circuits/README.md)

## Structure of Quantum Circuits and Common Functions Directory

- Quantum circuits and common functions are located at the repository root.

```bash

|
|-- circuits/   --- Quantum circuits are located here.
|-- common/   --- Common functions are located here.
|-- cpx.maude
|-- qc.maude
|-- verifications/   --- Verification code are located here.
|-- README.md   --- This file.
```

## Quantum Circuits Deatails

[Quantum Circuit List](./circuits/README.md)

## Verifications of Quantum Circuits

- code for verify(N) is located at `verifications/verify.maude`.
  - `verify(N)`: verifies 1 to N bits input qubit circuits each verifies the every compbinations of input vectors.

```bash

verifications
|
|-- circuits
|   |-- add
|   |-- sub
|   |-- ctrl-multi-swap
|   |-- ...
|-- verify.maude(common file for verifications)
```

```bash

cd verifications/ctrl-add/


maude verify-ctrl-add.maude
```

- This executes the verification for the ctrl-add circuit.

- In Maude console.

```bash

# verify verif n = 1 to 4
red verify(4) . => true

# verify for n = 2
red verify-one(2) . => true
```
