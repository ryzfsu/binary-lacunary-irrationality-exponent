# Timestamps

[OpenTimestamps](https://opentimestamps.org) proofs for the assets of release `v1`.
Each proof commits to the SHA-256 of the file below.

| file | SHA-256 |
|---|---|
| `binary-lacunary-irrationality-exponent-v1.pdf` | `23cdf850ff9c21f68aed5fd619c420d90abbbb9985b877d840da4fcef670350a` |
| `binary-lacunary-irrationality-exponent-v1.tar.gz` | `5acdb8c754eedd0004a92977cd78463c24bccbb9cb4ed24576a49e40ad307ef5` |

To verify, download the release asset into this directory and run

    pip install opentimestamps-client
    ots verify timestamps/<file>.ots
