Hashcat Benchmarks using Nvidia GeForce 940MX GM107


PS C:\Program Files\hashcat> ./hashcat.exe -b -d 1
hashcat (v6.2.6) starting in benchmark mode

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

* Device #1: WARNING! Kernel exec timeout is not disabled.
             This may cause "CL_OUT_OF_RESOURCES" or related errors.
             To disable the timeout, see: https://hashcat.net/q/timeoutpatch
nvmlDeviceGetFanSpeed(): Not Supported

CUDA API (CUDA 12.1)
====================
* Device #1: NVIDIA GeForce 940MX, 1684/2047 MB, 4MCU

OpenCL API (OpenCL 3.0 CUDA 12.1.98) - Platform #1 [NVIDIA Corporation]
=======================================================================
* Device #2: NVIDIA GeForce 940MX, skipped

OpenCL API (OpenCL 3.0 ) - Platform #2 [Intel(R) Corporation]
=============================================================
* Device #3: Intel(R) HD Graphics 620, skipped

Benchmark relevant options:
===========================
* --backend-devices=1
* --optimized-kernel-enable

-------------------
* Hash-Mode 0 (MD5)
-------------------

Speed.#1.........:  2559.0 MH/s (51.36ms) @ Accel:512 Loops:1024 Thr:64 Vec:8

----------------------
* Hash-Mode 100 (SHA1)
----------------------

Speed.#1.........:   873.9 MH/s (75.11ms) @ Accel:64 Loops:512 Thr:512 Vec:1

---------------------------
* Hash-Mode 1400 (SHA2-256)
---------------------------

Speed.#1.........:   310.5 MH/s (52.87ms) @ Accel:16 Loops:512 Thr:512 Vec:1

---------------------------
* Hash-Mode 1700 (SHA2-512)
---------------------------

Speed.#1.........:   105.4 MH/s (78.28ms) @ Accel:16 Loops:1024 Thr:128 Vec:1

-------------------------------------------------------------
* Hash-Mode 22000 (WPA-PBKDF2-PMKID+EAPOL) [Iterations: 4095]
-------------------------------------------------------------

Speed.#1.........:    43547 H/s (89.61ms) @ Accel:8 Loops:1024 Thr:512 Vec:1

-----------------------
* Hash-Mode 1000 (NTLM)
-----------------------

Speed.#1.........:  4226.5 MH/s (58.15ms) @ Accel:128 Loops:1024 Thr:512 Vec:8

---------------------
* Hash-Mode 3000 (LM)
---------------------

Speed.#1.........:  2505.3 MH/s (51.34ms) @ Accel:512 Loops:1024 Thr:64 Vec:1

--------------------------------------------
* Hash-Mode 5500 (NetNTLMv1 / NetNTLMv1+ESS)
--------------------------------------------

Speed.#1.........:  2339.7 MH/s (55.94ms) @ Accel:128 Loops:512 Thr:512 Vec:2

----------------------------
* Hash-Mode 5600 (NetNTLMv2)
----------------------------

Speed.#1.........:   171.7 MH/s (47.37ms) @ Accel:4 Loops:1024 Thr:512 Vec:1

--------------------------------------------------------
* Hash-Mode 1500 (descrypt, DES (Unix), Traditional DES)
--------------------------------------------------------

Speed.#1.........:   110.2 MH/s (74.76ms) @ Accel:32 Loops:1024 Thr:64 Vec:1

------------------------------------------------------------------------------
* Hash-Mode 500 (md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5)) [Iterations: 1000]
------------------------------------------------------------------------------

Speed.#1.........:   757.6 kH/s (69.82ms) @ Accel:32 Loops:1000 Thr:512 Vec:1

----------------------------------------------------------------
* Hash-Mode 3200 (bcrypt $2*$, Blowfish (Unix)) [Iterations: 32]
----------------------------------------------------------------

Speed.#1.........:     1064 H/s (81.57ms) @ Accel:2 Loops:32 Thr:12 Vec:1

--------------------------------------------------------------------
* Hash-Mode 1800 (sha512crypt $6$, SHA512 (Unix)) [Iterations: 5000]
--------------------------------------------------------------------

Speed.#1.........:    17313 H/s (90.60ms) @ Accel:128 Loops:512 Thr:128 Vec:1

--------------------------------------------------------
* Hash-Mode 7500 (Kerberos 5, etype 23, AS-REQ Pre-Auth)
--------------------------------------------------------

Speed.#1.........: 28372.7 kH/s (73.13ms) @ Accel:64 Loops:256 Thr:32 Vec:1

-------------------------------------------------
* Hash-Mode 13100 (Kerberos 5, etype 23, TGS-REP)
-------------------------------------------------

Speed.#1.........: 28863.3 kH/s (71.91ms) @ Accel:64 Loops:256 Thr:32 Vec:1

---------------------------------------------------------------------------------
* Hash-Mode 15300 (DPAPI masterkey file v1 (context 1 and 2)) [Iterations: 23999]
---------------------------------------------------------------------------------

Speed.#1.........:     7592 H/s (87.99ms) @ Accel:8 Loops:1024 Thr:512 Vec:1

---------------------------------------------------------------------------------
* Hash-Mode 15900 (DPAPI masterkey file v2 (context 1 and 2)) [Iterations: 12899]
---------------------------------------------------------------------------------

Speed.#1.........:     3428 H/s (89.64ms) @ Accel:2 Loops:1024 Thr:512 Vec:1

------------------------------------------------------------------
* Hash-Mode 7100 (macOS v10.8+ (PBKDF2-SHA512)) [Iterations: 1023]
------------------------------------------------------------------

Speed.#1.........:    39242 H/s (61.58ms) @ Accel:4 Loops:511 Thr:512 Vec:1

---------------------------------------------
* Hash-Mode 11600 (7-Zip) [Iterations: 16384]
---------------------------------------------

Speed.#1.........:    36203 H/s (51.51ms) @ Accel:16 Loops:4096 Thr:128 Vec:1

------------------------------------------------
* Hash-Mode 12500 (RAR3-hp) [Iterations: 262144]
------------------------------------------------

Speed.#1.........:     5946 H/s (84.27ms) @ Accel:8 Loops:16384 Thr:256 Vec:1

--------------------------------------------
* Hash-Mode 13000 (RAR5) [Iterations: 32799]
--------------------------------------------

Speed.#1.........:     3849 H/s (65.70ms) @ Accel:8 Loops:512 Thr:512 Vec:1

--------------------------------------------------------------------------------
* Hash-Mode 6211 (TrueCrypt RIPEMD160 + XTS 512 bit (legacy)) [Iterations: 1999]
--------------------------------------------------------------------------------

Speed.#1.........:    28768 H/s (64.42ms) @ Accel:8 Loops:256 Thr:512 Vec:1

-----------------------------------------------------------------------------------
* Hash-Mode 13400 (KeePass 1 (AES/Twofish) and KeePass 2 (AES)) [Iterations: 24569]
-----------------------------------------------------------------------------------

Speed.#1.........:     3676 H/s (91.49ms) @ Accel:4 Loops:1024 Thr:512 Vec:1

----------------------------------------------------------------
* Hash-Mode 6800 (LastPass + LastPass sniffed) [Iterations: 499]
----------------------------------------------------------------

Speed.#1.........:   199.0 kH/s (63.92ms) @ Accel:8 Loops:499 Thr:512 Vec:1

--------------------------------------------------------------------
* Hash-Mode 11300 (Bitcoin/Litecoin wallet.dat) [Iterations: 200459]
--------------------------------------------------------------------

Speed.#1.........:      467 H/s (88.11ms) @ Accel:128 Loops:32 Thr:512 Vec:1

Started: Thu Apr 13 04:55:39 2023
Stopped: Thu Apr 13 04:59:42 2023
PS C:\Program Files\hashcat>
