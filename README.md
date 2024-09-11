# nspk -- Needham-Schroeder Public-Key

Model of the NSPK protocol and example with actors a & b as shown in four examples.
1. NSPK-UNSIGNED: Sender information extracted from payload. 
2. NSPK-SIGNED: Sender information extracted from header.
3. NSPK-UNSIGNED included in module with intruder which successfully spoofs both actors. 
4. NSPK-SIGNED include in module with intruder which connects with b authentically without spoofs.


# Setup
After installing Maude 3.4+, execute the following commands.
- `maude nspk.maude > trace.txt`
- `cat trace.txt`
