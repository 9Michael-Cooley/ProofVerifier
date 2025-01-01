# ProofVerifier
A simple, open-source library for verifying mathematical proofs using Python.

## Description
ProofVerifier is designed to automate the process of verifying mathematical proofs, allowing users to focus on the logic and reasoning behind the proof rather than the tedious verification process.

## Features
- Supports multiple proof formats (e.g., propositional, predicate, and modal logic)
- Allows for user-defined rules and axioms
- Includes a built-in theorem prover for automatic proof verification
- Integrates with popular math libraries (e.g., SymPy) for symbolic manipulation

## Install
You can install ProofVerifier using pip:
```bash
pip install proof-verifier
```
## Usage
```python
from proof_verifier import Proof

# Define a simple propositional logic proof
proof = Proof()
proof.add_rule("A -> B")
proof.add_rule("B -> C")
proof.add_rule("A")
proof.verify()
```
See the example directory for more usage examples.