# Output of the "make build-contract" command

```sh


cd contract && cargo build --release --target wasm32-unknown-unknown
    Updating crates.io index
 Downloading crates ...
  Downloaded autocfg v1.1.0
  Downloaded base64 v0.13.0
  Downloaded block-buffer v0.9.0
  Downloaded cfg-if v0.1.10
  Downloaded memory_units v0.4.0
  Downloaded hex v0.4.3
  Downloaded opaque-debug v0.3.0
  Downloaded rand v0.8.5
  Downloaded zeroize_derive v1.3.2
  Downloaded cfg-if v1.0.0
  Downloaded curve25519-dalek v3.2.1
  Downloaded num v0.4.0
  Downloaded radium v0.3.0
  Downloaded zeroize v1.3.0
  Downloaded casper-contract v1.4.4
  Downloaded crypto-mac v0.8.0
  Downloaded digest v0.9.0
  Downloaded itoa v1.0.1
  Downloaded rand_chacha v0.2.2
  Downloaded version_check v0.9.4
  Downloaded typenum v1.15.0
  Downloaded wyz v0.2.0
  Downloaded serde v1.0.136
  Downloaded signature v1.2.2
  Downloaded ryu v1.0.9
  Downloaded serde_bytes v0.11.5
  Downloaded hmac v0.10.1
  Downloaded uint v0.9.3
  Downloaded proc-macro2 v1.0.37
  Downloaded cpufeatures v0.2.2
  Downloaded crypto-mac v0.10.1
  Downloaded libc v0.2.124
  Downloaded casper-types v1.5.0
  Downloaded quote v1.0.18
  Downloaded ppv-lite86 v0.2.16
  Downloaded generic-array v0.14.5
  Downloaded serde_json v1.0.79
  Downloaded hex_fmt v0.3.0
  Downloaded ecdsa v0.10.2
  Downloaded byteorder v1.4.3
  Downloaded rand_core v0.6.3
  Downloaded rand v0.7.3
  Downloaded num-traits v0.2.14
  Downloaded ed25519-dalek v1.0.1
  Downloaded crunchy v0.2.2
  Downloaded bitvec v0.18.5
  Downloaded wee_alloc v0.4.5
  Downloaded unicode-xid v0.2.2
  Downloaded syn v1.0.91
  Downloaded sha2 v0.9.9
  Downloaded serde_derive v1.0.136
  Downloaded base16 v0.2.1
  Downloaded num-rational v0.4.0
  Downloaded num-iter v0.1.42
  Downloaded num-derive v0.3.3
  Downloaded k256 v0.7.3
  Downloaded group v0.8.0
  Downloaded funty v1.1.0
  Downloaded ff v0.8.0
  Downloaded elliptic-curve v0.8.5
  Downloaded ed25519 v1.2.0
  Downloaded synstructure v0.12.6
  Downloaded subtle v2.4.1
  Downloaded static_assertions v1.1.0
  Downloaded rand_core v0.5.1
  Downloaded num-integer v0.1.44
  Downloaded num-complex v0.4.0
  Downloaded num-bigint v0.4.3
  Downloaded blake2 v0.9.2
  Downloaded bitflags v1.3.2
   Compiling typenum v1.15.0
   Compiling version_check v0.9.4
   Compiling autocfg v1.1.0
   Compiling proc-macro2 v1.0.37
   Compiling unicode-xid v0.2.2
   Compiling syn v1.0.91
   Compiling subtle v2.4.1
   Compiling rand_core v0.5.1
   Compiling wyz v0.2.0
   Compiling radium v0.3.0
   Compiling funty v1.1.0
   Compiling serde_derive v1.0.136
   Compiling serde v1.0.136
   Compiling opaque-debug v0.3.0
   Compiling byteorder v1.4.3
   Compiling cfg-if v1.0.0
   Compiling crunchy v0.2.2
   Compiling ppv-lite86 v0.2.16
   Compiling serde_json v1.0.79
   Compiling ryu v1.0.9
   Compiling hex v0.4.3
   Compiling itoa v1.0.1
   Compiling rand_core v0.6.3
   Compiling wee_alloc v0.4.5
   Compiling static_assertions v1.1.0
   Compiling memory_units v0.4.0
   Compiling cfg-if v0.1.10
   Compiling bitflags v1.3.2
   Compiling hex_fmt v0.3.0
   Compiling base64 v0.13.0
   Compiling base16 v0.2.1
   Compiling rand v0.8.5
   Compiling rand_chacha v0.2.2
   Compiling bitvec v0.18.5
   Compiling generic-array v0.14.5
   Compiling uint v0.9.3
   Compiling num-traits v0.2.14
   Compiling num-integer v0.1.44
   Compiling num-bigint v0.4.3
   Compiling num-iter v0.1.42
   Compiling num-rational v0.4.0
   Compiling rand v0.7.3
   Compiling quote v1.0.18
   Compiling num-complex v0.4.0
   Compiling digest v0.9.0
   Compiling crypto-mac v0.10.1
   Compiling block-buffer v0.9.0
   Compiling crypto-mac v0.8.0
   Compiling signature v1.2.2
   Compiling blake2 v0.9.2
   Compiling hmac v0.10.1
   Compiling sha2 v0.9.9
   Compiling ed25519 v1.2.0
   Compiling ff v0.8.0
   Compiling group v0.8.0
   Compiling synstructure v0.12.6
   Compiling num v0.4.0
   Compiling zeroize_derive v1.3.2
   Compiling num-derive v0.3.3
   Compiling zeroize v1.3.0
   Compiling elliptic-curve v0.8.5
   Compiling curve25519-dalek v3.2.1
   Compiling ecdsa v0.10.2
   Compiling ed25519-dalek v1.0.1
   Compiling k256 v0.7.3
   Compiling serde_bytes v0.11.5
   Compiling casper-types v1.5.0
   Compiling casper-contract v1.4.4
   Compiling contract v0.1.0 (/workspace/blockchain-authenticator-contract/contract)
    Finished release [optimized] target(s) in 1m 01s
wasm-strip contract/target/wasm32-unknown-unknown/release/contract.wasm 2>/dev/null | true

```
