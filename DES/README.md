# DES and Triple-DES

## DES_ECB.v and DES_TB.v
DES encryption/decryption circuit and its testbench.
(Update 2007/Sep/25)

## DESSpec2007Sep25.pdf
Specification form for DES_ECB.v
(Update 2007/Sep/25)

## DES_ECB_Akkar.v

DES encryption/decryption circuit with a DPA (Differential Power
Analysis) / SPA (Simple Power Analysis) countermeasure [1] where a
plaintext/ciphertext is masked by a rundom number.  This sample code
uses a constant 0x123456789abcdef as a rundom number after the IP
operation.

[1] M. Akkar, C. Giraud, "An Implementation of DES and AES, Secure against Some Attacks", CHES2001

## TDEA.v and TDEA_tb.v
TDEA (a.k.a. Triple-DES) encryption/decryption circuit
(Update 2007/Sep/25)

## TDEASpec2007Sep25.pdf
Specification form for DES_ECB.v
(Update 2007/Sep/25)
