# Namada Trusted Setup Claimer

CLI util to sign arbitrary messages with. The signing keys are obtained from
Namada's trusted setup ceremony.

To run it just type:

```shell
cargo run
```

You will be asked to provide the seed used during the trusted setup ceremony.
Once you've done that, you can choose to:

1. Show the public key
2. Sign a message
name = "namada-trusted-setup-claimer"
version = "0.1.0"
dependencies = [
 "anyhow",
 "bip39",
 "ed25519-compact",
 "hex",
 "inquire",
 "zeroize",
