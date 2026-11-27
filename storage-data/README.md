# Encrypted backup storage

This branch is not the website publishing branch. Only client-side AES-256-GCM encrypted backup envelopes belong in this directory. Never commit plaintext journal exports, credentials or encryption keys. This is a public repository: ciphertext, commit history and update times are public. Keep the randomly generated recovery key separately in a password manager. The application uses the GitHub Contents API to write backup.json only after the owner provides a repository-scoped token in the browser. No data has been uploaded by this setup.
