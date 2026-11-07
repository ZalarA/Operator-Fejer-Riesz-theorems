# Supplementary Examples and Mathematica Code

This repository accompanies **“Operator Fejér–Riesz Theorems with Gaps and Degree Bounds”** by **Abhay Jindal and Aljaž Zalar**.

It contains a standalone supplement with the explicit computations referred to in the remark at the end of the manuscript subsection **“Computation of the additive constant”**, together with Mathematica/Wolfram Language code for exact symbolic verification.

The examples concern

$$
K_0=[0,1]\cup[2,3], \qquad K_1=K_0\cup\{4\},
$$

with natural descriptions

$$
S_0=\{x,(x-1)(x-2),3-x\},
$$

$$
S_1=\{x,(x-1)(x-2),(x-3)(x-4),4-x\}.
$$

The supplement derives admissible additive constants $c_{S_0}=12$ and $c_{S_1}=18$ for the degree bounds in Theorem A. These constants are not asserted to be optimal. The minimality results concern specific intermediate certificates: the degree of the scalar multiplier, the certificate for $\Delta$, and the fixed matrix construction used to adjoin the isolated point.

The notebook includes the rank-one matrix pencil, the degree-preserving congruence for the choice $q=1$, scalar sums-of-squares identities, an explicit matrix certificate, and computations supporting the degree bounds and minimality arguments.

## Files

| File | Contents |
| --- | --- |
| [Explicit computations of the additive constants.pdf](https://github.com/ZalarA/Operator-Fejer-Riesz-theorems/blob/main/Explicit%20computations%20of%20the%20additive%20constants.pdf) | Supplementary examples, including all five claims and their proofs. |
| [Operator_Fejer_Riesz_Example_q1.pdf](https://github.com/ZalarA/Operator-Fejer-Riesz-theorems/blob/main/Operator_Fejer_Riesz_Example_q1.pdf) | PDF export of the Mathematica notebook, viewable without Mathematica. |
| [Operator_Fejer_Riesz_Example_q1.nb](https://github.com/ZalarA/Operator-Fejer-Riesz-theorems/blob/main/Operator_Fejer_Riesz_Example_q1.nb) | Mathematica notebook with annotated computations. |

## Usage

### Read the supplementary examples

Open [Explicit computations of the additive constants.pdf](https://github.com/ZalarA/Operator-Fejer-Riesz-theorems/blob/main/Explicit%20computations%20of%20the%20additive%20constants.pdf). Appendix B numbering is retained. Citations to numbered manuscript results refer to the accompanying manuscript; the supplement's claims and equations are numbered locally.

### Run the Mathematica computations

Download [Operator_Fejer_Riesz_Example_q1.nb](https://github.com/ZalarA/Operator-Fejer-Riesz-theorems/blob/main/Operator_Fejer_Riesz_Example_q1.nb), open it in **Wolfram Mathematica**, and evaluate the cells in order.

To view the computations without Mathematica, open the [PDF export of the notebook](https://github.com/ZalarA/Operator-Fejer-Riesz-theorems/blob/main/Operator_Fejer_Riesz_Example_q1.pdf).

The code uses exact arithmetic and displays the computed polynomial and matrix expressions. The proofs are given in the supplementary document and use the general results established in the manuscript.

## Reference

A. Jindal and A. Zalar, *Operator Fejér–Riesz Theorems with Gaps and Degree Bounds*, manuscript, 2026.

When using these computations, please cite the manuscript and this repository.
