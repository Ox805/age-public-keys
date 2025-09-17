# age Public Keys

This repository contains my **public keys** for use with the [age](https://github.com/FiloSottile/age) encryption tool.

## Usage

To encrypt a file for me, use my public key from `keys.pub`:

age -r <my-public-key> -o file.txt.age file.txt

Only I can decrypt files encrypted with this key.

---

**Note:** This repository contains **public keys only**.  
My private keys are stored securely and are never shared.
