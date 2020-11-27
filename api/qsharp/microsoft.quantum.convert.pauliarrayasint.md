---
uid: Microsoft.Quantum.Convert.PauliArrayAsInt
title: PauliArrayAsInt function
ms.date: 11/25/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Convert
qsharp.name: PauliArrayAsInt
qsharp.summary: >-
  Encodes a multi-qubit Pauli operator represented as an array of
  single-qubit Pauli operators into an integer.
---

# PauliArrayAsInt function

Namespace: [Microsoft.Quantum.Convert](xref:Microsoft.Quantum.Convert)

Package: [Microsoft.Quantum.QSharp.Core](https://nuget.org/packages/Microsoft.Quantum.QSharp.Core)


Encodes a multi-qubit Pauli operator represented as an array of

```qsharp
function PauliArrayAsInt (paulis : Pauli[]) : Int
```


## Input

### paulis : [Pauli](xref:microsoft.quantum.lang-ref.pauli)[]

An array of at most 31 single-qubit Pauli operators.



## Output : [Int](xref:microsoft.quantum.lang-ref.int)

An integer uniquely identifying `paulis`, as described below.

## Remarks

Each Pauli operator can be encoded using two bits: