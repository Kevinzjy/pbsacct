# pbstools

Usage accouting for torque-based HPC systems

# Usage 

## Installation

Download the latest release package, then

```bash
tar zxvf pbstools_v1.0.0.tar.gz
```

## Usage

```bash
conda activate ./pbstools
pbsacct \
    -i /home/zhangjy/data/test/pbsacct/accounting_mu01 \
    -s 20230101 \
    -e 20231101 \
    -o /home/zhangjy/data/test/pbsacct/usage_mu01
```
