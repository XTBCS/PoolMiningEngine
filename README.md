
## PoolMining Engine
### Powered by XTBCS Group

### Features

- Supports clusters of pools each running individual currencies
- Ultra-low-latency Stratum implementation using asynchronous I/O (LibUv)
- Adaptive share difficulty ("vardiff")
- PoW validation (hashing) using native code for maximum performance
- Session management for purging DDoS/flood initiated zombie workers
- Payment processing
- Banning System for banning peers that are flooding with invalid shares
- Live Stats API on Port 4000
- POW (proof-of-work) & POS (proof-of-stake) support
- Detailed per-pool logging to console & filesystem
- Runs on Linux and Windows

### Coins

Coin | Implemented | Tested | Planned
:--- | :---: | :---: | :---:
Bitcoin | Yes | Yes |
Bitcoin Cash | Yes | Yes |
Litecoin | Yes | Yes |
Monero | Yes | Yes |
DASH | Yes | Yes |
Groestlcoin | Yes | Yes |
Ethereum | No |  | Oct 2017
Ethereum Classic | No |  | Oct 2017
Zcash | No |  | Nov 2017
Dogecoin | Yes | No |
DigiByte | Yes | No |
Namecoin | Yes | No |
Viacoin | Yes | No |
Peercoin | Yes | No |
MusicCoin | No |  | Dec 2017
UBIQ | No |  | Dec 2017


### Runtime Requirements

- [.Net Core 2.0 Runtime](https://www.microsoft.com/net/download/core#/runtime)
- [PostgreSQL Database](https://www.postgresql.org/)
- Coin Daemon (per pool)


### Building from Source (Visual Studio)

- Install Visual Studio 2017 (Community Edition is sufficient)
- Install the [.Net Core 2.0 SDK](https://www.microsoft.com/net/download/core) for your platform
- Open MiningCore.sln in VS 2017
