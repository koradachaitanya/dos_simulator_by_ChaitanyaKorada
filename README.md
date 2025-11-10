# Security Automation & Ethical DoS Simulation

## Overview

This repository showcases one of the foundational cybersecurity automation task.  
All work was performed solely for educational and learning purposes as part of my Internship.


## Task : Ethical DoS Attack Simulation

### Description

Simulates a Denial of Service (DoS) attack in a controlled, ethical environment to illustrate resource exhaustion and monitoring strategies.

### How It Works

- Uses the requests library to send a configurable number of HTTP requests to a specified test server
- Includes a delay parameter to control the rate of requests and prevent accidental harm
- Implements safety prompts and configuration checks to ensure ethical use in isolated environments

### Features

- Configurable request count and delay
- Built-in safeguards and explicit user confirmation
- Designed for test environments only

### Challenges & Solutions

- **Preventing misuse:** Added explicit user confirmation and rate limiting
- **Testing safely:** Used only test servers and low request counts

## Key Learnings

- Building offensive (DoS simulation) tool deepened my understanding of network security
- Ethical boundaries and safeguards are essential when simulating attacks, even in a lab setting

### Usage

#### Ethical DoS Attack Simulation

Run the script with the target URL, number of requests to send, and (optionally) the delay between requests.

## How to Run

### Prerequisites

- Python 3.8 or higher
- Install required packages:
  - `requests`
  - `pyOpenSSL`


#### Ethical DoS Attack Simulation :
python dos_simulation.py --target <TARGET_URL> 

## Disclaimer

- Use these script only on systems you own or have explicit permission to test.
- Unauthorized attack simulation is illegal and unethical.

## Summary

These project gave me hands-on experience with Python for understanding attack techniques—skills that are vital in today’s cybersecurity landscape.

I completed these project solely for educational and learning purposes, undertaking them exclusively as part of my educational training.  

## Created by 
Korada Chaitanya  


## License:
This project is for educational purposes only.
