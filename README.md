# SHA256
Brute-force attack demo against 4-digit SHA-256 hashed passcodes using a custom SHA-256 implementation in Python.
there is csv file containing some targets: (name, hashed password)
there is a Jupiter notebook which is used for the implementation.

basically i am :

Reading a CSV with name and sha256(passcode) entries.

Trying all possible 4-digit numbers (from 0000 to 9999).

Hashing each one using your custom SHA-256 implementation.

Comparing each hash to the ones in your CSV.

If matched, saving {name: passcode} into a dictionary.
