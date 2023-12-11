# Git Commands

### Setup Git
```bash
git config --global user.name "Your Name"
git config --global user.email "yourname@example.com"
```
```bash
git config --global init.defaultBranch main
```

```bash
git config --global color.ui auto
```

```bash
git config --global pull.rebase false
```

## Create an SSH key

Check if ed25519 key is already installed.
```bash
ls ~/.ssh/id_ed25519.pub
```

To generate a key:
```bash
ssh-keygen -t ed25519 -C "your@email.com"
```

Read the public key to the console:
```bash
cat ~/.ssh/id_ed25519.pub
```

