# Quantum Circuits in Maude

## N-SWAP

- [N-SWAP](./n-swap/n-swap.maude)
  - n-swap swaps qubits values.
    - `n-swap(x, y) -> (y,x)`

## Ctrl-N-Swap

- [Ctrl-N-Swap](./ctrl-n-swap/ctrl-n-swap.maude)
  - n-swap swaps qubits values with control qubit.
    - `ctrl-n-swap(ctrl, x, y) -> (y,x)`

## Ctrl-Add

- [Ctrl-Add](./ctrl-add/ctrl-add.maude)
  - addition of 2 natural numbers in quantum circuits with control qubit.
    - `ctrl-add(ctrl, x, y) -> (x+y)`

## Ctrl-Sub

- [Ctrl-Sub](./ctrl-sub/ctrl-sub.maude)
  - subtraction of 2 natural numbers in quantum circuits with control qubit.
    - `ctrl-sub(ctrl, x, y) -> (x-y)`

## Ctrl-Mod-Add

- [Ctrl-Mod-Add](./ctrl-mod-add/ctrl-mod-add.maude)
  - addition of 2 natural numbers in quantum circuits with control qubit and modulo operation.
    - `ctrl-mod-add(ctrl, x, y, n) -> (x+y) mod n`

## Ctrl-Ctrl-Mod-Add

- [Ctrl-Ctrl-Mod-Add](./ctrl-ctrl-mod-add/ctrl-ctrl-mod-add.maude)
  - addition of 2 natural numbers in quantum circuits with two control qubits and modulo operation.
    - `ctrl-ctrl-mod-add(ctrl0, ctrl1, x, y, n) -> (x+y) mod n`

## Ctrl-Mod-Mult

- [Ctrl-Mod-Mult](./ctrl-mod-mult/ctrl-mod-mult.maude)
  - multiplication of 2 natural numbers in quantum circuits with control qubit and modulo operation.
    - `ctrl-mod-mult(ctrl, x, y, n) -> (x*y) mod n`

## Mod-Exp

- [Mod-Exp](./mod-exp/mod-exp.maude)
  - exponentiation of 2 natural numbers in quantum circuits with modulo operation.
    - `mod-exp(x, y, n) -> (x^y) mod n`
