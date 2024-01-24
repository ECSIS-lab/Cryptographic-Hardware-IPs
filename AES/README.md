# AES

## AES.v and AES_TB.v

AES encryption/decryption circuit and its testbench.
The key length is limited to 128 bits.

## AES_Comp.v, AES_TBL.v, AES_PPRM1.v, AES_PPRM3.v, and AES_ENC_TB.v

AES encryption/decryption circuits and their testbench.
S-boxes are implemented based on Composite field, LUT, ANF (Arithmetic Normal Form), and 3-stage PPRM in AES_Comp.v, AES_TBL.v, AES_PPRM1.v, AES_PPRM3.v, respectively. AES_Comp.v supports both encryption and decryption, while others support only encryption.
The key length is limited to 128 bits.
(Update 2007/Oct/04)

## AESSpec2007Sep25.pdf

Specification form for AES2.v
(Update 2007/Sep/25)
