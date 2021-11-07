# Solana BE with Anchor

see frontend: https://github.com/ertyurk/FE_solana_gif_portal

```sh
solana config set --url devnet
```

// Make sure you're on devnet.
```sh
solana config get
```

```sh
anchor build
```

// Get the new program id.
```sh
  solana address -k target/deploy/myepicproject-keypair.json
```
// Update Anchor.toml and lib.rs w/ new program id.
// Make sure Anchor.toml is on devnet.

// Build again.
```sh
  anchor build
```

// Deploy 
```sh
anchor deploy
```
