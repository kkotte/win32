---
Description: The following table lists the algorithms supported by the Microsoft Advanced Encryption Standard (AES) Cryptographic Provider.
ms.assetid: 34d0479f-9d1e-41cd-87b0-6bc18c7a062b
title: AES Provider Algorithms
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# AES Provider Algorithms

The following table lists the algorithms supported by the Microsoft [*Advanced Encryption Standard*](https://msdn.microsoft.com/en-us/library/ms721532(v=VS.85).aspx) (AES) Cryptographic Provider.



| Algorithm ID       | Description                                                                                                                                                     | Comments                                                                                                                                                   |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| CALG\_3DES         | Triple DES.                                                                                                                                                     | Key length: 168 bits. Default mode: Cipher block chaining.<br/> Block size: 64 bits.<br/> No salt allowed.<br/>                          |
| CALG\_3DES\_112    | Two-key [*triple DES*](https://msdn.microsoft.com/en-us/library/ms721627(v=VS.85).aspx) encryption.                                                            | Key length: 112 bits. Default mode: Cipher block chaining.<br/> Block size: 64 bits.<br/> No salt allowed.<br/>                          |
| CALG\_AES\_128     | AES block encryption algorithm.                                                                                                                                 | Key length: 128 bits.                                                                                                                                      |
| CALG\_AES\_192     | AES block encryption algorithm.                                                                                                                                 | Key length: 192 bits.                                                                                                                                      |
| CALG\_AES\_256     | AES block encryption algorithm.                                                                                                                                 | Key length: 256 bits.                                                                                                                                      |
| CALG\_DES          | DES encryption.                                                                                                                                                 | Key length: 56 bits. Default mode: Cipher block chaining.<br/> Block size: 64 bits.<br/> No salt allowed.<br/>                           |
| CALG\_HMAC         | MAC keyed-hash algorithm.                                                                                                                                       | HMAC computation.                                                                                                                                          |
| CALG\_MAC          | [*Message Authentication Code*](https://msdn.microsoft.com/en-us/library/ms721594(v=VS.85).aspx) (MAC) keyed hash algorithm. | Block cipher MAC.                                                                                                                                          |
| CALG\_MD2          | MD2 hashing algorithm.                                                                                                                                          | For more information, see [*MD2 algorithm*](https://msdn.microsoft.com/en-us/library/ms721594(v=VS.85).aspx).                                       |
| CALG\_MD5          | MD5 hashing algorithm.                                                                                                                                          | For more information, see [*MD5 algorithm*](https://msdn.microsoft.com/en-us/library/ms721594(v=VS.85).aspx).                                       |
| CALG\_RC2          | RC2 block encryption algorithm.                                                                                                                                 | Key length: 128 bits. Default mode: Cipher block chaining.<br/> Block size: 64 bits.<br/> Salt length: Can be set.<br/>                  |
| CALG\_RC4          | RC4 stream encryption algorithm.                                                                                                                                | Key length: 128 bits. Salt length: Can be set.<br/>                                                                                                  |
| CALG\_RSA\_KEYX    | RSA public key exchange algorithm.                                                                                                                              | Key length: Can be set, 384 bits to 16,384 bits in 8-bit increments. Default key length: 1,024 bits.<br/>                                            |
| CALG\_RSA\_SIGN    | RSA public key signature algorithm.                                                                                                                             | Key length: Can be set, 384 bits to 16,384 bits in 8-bit increments. Default key length: 1,024 bits.<br/> Signature conforms to PKCS \#6.<br/> |
| CALG\_SHA          | SHA hashing algorithm.                                                                                                                                          | For more information, see [*Secure Hash Algorithm*](https://msdn.microsoft.com/en-us/library/ms721625(v=VS.85).aspx).               |
| CALG\_SHA1         | Same as **CALG\_SHA**.                                                                                                                                          | For more information, see [*Secure Hash Algorithm*](https://msdn.microsoft.com/en-us/library/ms721625(v=VS.85).aspx).               |
| CALG\_SHA\_256     | SHA hashing algorithm.                                                                                                                                          | Key length: 256 bits.**Windows XP:** This algorithm is not supported.<br/>                                                                           |
| CALG\_SHA\_384     | SHA hashing algorithm.                                                                                                                                          | Key length: 384 bits.**Windows XP:** This algorithm is not supported.<br/>                                                                           |
| CALG\_SHA\_512     | SHA hashing algorithm.                                                                                                                                          | Key length: 512 bits.**Windows XP:** This algorithm is not supported.<br/>                                                                           |
| CALG\_SSL3\_SHAMD5 | SSL3 client authentication algorithm.                                                                                                                           | For more information, see [Creating a CALG\_SSL3\_SHAMD5 Hash](creating-a-calg-ssl3-shamd5-hash.md).                                                      |



 

 

 



