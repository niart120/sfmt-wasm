# sfmt-wasm

既に先駆者による素晴らしい実装(https://github.com/rust-math/sfmt) があるため, 通常用途に関してはそちらを使うことを推奨します.

web-assemblyは2021年にsimdをサポートするようになりましたが, SFMTの実装に必要な命令がサポートされていないことから, simd無しでの実装を行っています.
