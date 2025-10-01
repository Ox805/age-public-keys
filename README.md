# Public Keys

This repository contains my **public keys** for various cryptographic purposes.

## Keys

- `age-key` - [age](https://github.com/FiloSottile/age) encryption public key
- `id_ed25519.pub.txt` - SSH public key (ED25519)

## Usage

### age encryption

To encrypt a file for me using age:

```bash
age -r <my-public-key> -o file.txt.age file.txt
```

### SSH access

Use the public key from `id_ed25519.pub.txt` to grant SSH access.

---

**Note:** This repository contains **public keys only**.
My private keys are stored securely and are never shared.
