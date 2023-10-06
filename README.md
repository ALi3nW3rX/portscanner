# Rust Port Scanner

A simple Rust port scanner that can scan a range of ports on a target IP address using multiple threads.

## Table of Contents

- [Rust Port Scanner](#rust-port-scanner)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Usage](#usage)

## Features

- Multi-threaded port scanning for faster results.
- Customizable IP address and thread count.
- Uses the Clap crate for command-line argument parsing.
- Progress bar display using the Indicatif crate.

## Usage

To use this port scanner, you need to provide the target IP address and the number of threads to use for scanning.

```bash
portscanner.exe --ip <target_ip> --threads <num_threads>
```

```
Simple rust portscanner

Usage: portscanner.exe --ip <IP> --threads <THREADS>

Options:
  -i, --ip <IP>            Ip address of target
  -t, --threads <THREADS>  Number of threads to use
  -h, --help               Print help
  -V, --version            Print version
  ```