# Authentication Methods

## HTTPS

- Username
- Personal Access Token

---

## SSH

- Public Key
- Private Key

---

## API Keys

Used for applications to access services.

Not the same as SSH keys.


# SSH Authentication

SSH provides secure communication between your computer and GitHub.

Benefits:

- No password every push
- Secure authentication
- Faster workflow

Generate key

```bash
ssh-keygen
```

View public key

```bash
cat ~/.ssh/id_ed25519.pub
```

Test authentication

```bash
ssh -T git@github.com
```