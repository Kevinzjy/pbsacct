# pbstools

Usage accouting for torque-based HPC systems

# Usage 

## Installation

Download the latest release package, then

```bash
wget https://github.com/Kevinzjy/pbsacct/releases/download/v1.0.0/pbsacct_v1.0.0.tar.gz
tar zxvf pbsacct_v1.0.0.tar.gz
```

## Usage

```bash
conda activate ./pbsacct
pbsacct \
    -i /var/spool/torque/server_priv/accounting \
    -s 20230101 \
    -e 20231101 \
    -o /tmp/cpu_usage 
```
