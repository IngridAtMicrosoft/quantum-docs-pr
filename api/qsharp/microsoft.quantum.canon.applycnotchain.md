---
uid: Microsoft.Quantum.Canon.ApplyCNOTChain
title: ApplyCNOTChain operation
ms.date: 11/25/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApplyCNOTChain
qsharp.summary: Computes the parity of a register of qubits in-place.
---

# ApplyCNOTChain operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Computes the parity of a register of qubits in-place.

```qsharp
operation ApplyCNOTChain (qubits : Qubit[]) : Unit is Adj + Ctl
```


## Description

This operation transforms the state of its input as

## Input

### qubits : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

Array of qubits whose parity is to be computed and stored.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)
