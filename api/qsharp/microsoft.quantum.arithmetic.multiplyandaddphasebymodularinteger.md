---
uid: Microsoft.Quantum.Arithmetic.MultiplyAndAddPhaseByModularInteger
title: MultiplyAndAddPhaseByModularInteger operation
ms.date: 11/25/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: MultiplyAndAddPhaseByModularInteger
qsharp.summary: >-
  The same as MultiplyAndAddByModularInteger, but assumes that the summand encodes
  integers in QFT basis.
---

# MultiplyAndAddPhaseByModularInteger operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


The same as MultiplyAndAddByModularInteger, but assumes that the summand encodes

```qsharp
operation MultiplyAndAddPhaseByModularInteger (constMultiplier : Int, modulus : Int, multiplier : Microsoft.Quantum.Arithmetic.LittleEndian, phaseSummand : Microsoft.Quantum.Arithmetic.PhaseLittleEndian) : Unit is Adj + Ctl
```


## Input

### constMultiplier : [Int](xref:microsoft.quantum.lang-ref.int)

An integer $a$ to be added to each basis state label.


### modulus : [Int](xref:microsoft.quantum.lang-ref.int)

The modulus $N$ which addition and multiplication is taken with respect to.


### multiplier : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

A quantum register representing an unsigned integer whose value is to


### phaseSummand : [PhaseLittleEndian](xref:Microsoft.Quantum.Arithmetic.PhaseLittleEndian)

A quantum register representing an unsigned integer to use as the target



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

Assumes that `phaseSummand` has the highest bit set to 0.

## See Also

- [Microsoft.Quantum.Arithmetic.MultiplyAndAddByModularInteger](xref:Microsoft.Quantum.Arithmetic.MultiplyAndAddByModularInteger)