---
uid: Microsoft.Quantum.Characterization.QuantumPhaseEstimation
title: QuantumPhaseEstimation operation
ms.date: 11/25/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Characterization
qsharp.name: QuantumPhaseEstimation
qsharp.summary: >-
  Performs the quantum phase estimation algorithm for a given oracle `U` and `targetState`,
  reading the phase into a big-endian quantum register.
---

# QuantumPhaseEstimation operation

Namespace: [Microsoft.Quantum.Characterization](xref:Microsoft.Quantum.Characterization)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Performs the quantum phase estimation algorithm for a given oracle `U` and `targetState`,

```qsharp
operation QuantumPhaseEstimation (oracle : Microsoft.Quantum.Oracles.DiscreteOracle, targetState : Qubit[], controlRegister : Microsoft.Quantum.Arithmetic.BigEndian) : Unit is Adj + Ctl
```


## Input

### oracle : [DiscreteOracle](xref:Microsoft.Quantum.Oracles.DiscreteOracle)

An operation implementing $U^m$ for given integer powers m.


### targetState : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

A quantum register representing the state $\ket{\phi}$ acted on by $U$. If $\ket{\phi}$ is an


### controlRegister : [BigEndian](xref:Microsoft.Quantum.Arithmetic.BigEndian)

A big-endian representation integer register that can be used



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)
