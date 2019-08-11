# ADVANCED ENCRYPTION STANDARD ALGORITHM (AES)

This project implements the working Advanced Encryption Standard (AES) algorithm, which is one of the most strongest forms of encryption.It is a symmetric block cipher encryption algorithm which is widely used to encrypt sensitive data. The three variants of AES are based on different key sizes (128, 192, and 256 bits).The encryption phase of AES can be broken into three phases: the initial round, the main rounds, and the final round. All of the phases use the mentioned phases in different combinations as follows:
1. Initial Round:
   - AddRoundKey
2. Main Rounds:
   - SubBytes
   - ShiftRows
   - MixColumns
   - AddRoundKey
3. Final Round:
   - SubBytes
   - ShiftRows
   - AddRoundKey
   </a>
The main rounds of AES are repeated a set number of times for each variant of AES. AES-128 uses 9 iterations of the main round, AES-192 uses 11, and AES-256 uses 13.

The interactive web tool provides ways to encrypt and decrypt different types of data like the numeric, audio, visual, pictorial.Initially, numeric encryption-decryption was validated on the credit/debit card numbers data.Later, the project was extended to validate other data like the images etc using the counter mode of Fiestel Network.\
\
The project used Javascript, JQuery for building the web tool.It successively helps to encrypt and decrypt different kinds of data with several kinds of extensions (doc, docx,ppt, css, jpeg, mp4, gif,png etc.,) and safely helps to protect the data in consideration.\
\
Use atmindex.html for interaction.
