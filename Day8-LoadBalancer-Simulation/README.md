# Day 8 – Load Balancer Simulation (CLI)

Simulated cloud load balancing using bash scripting  
Created 3 mock servers (`server_a.txt`, `server_b.txt`, `server_c.txt`)  
Wrote a `lb.sh` script to randomly route requests to these servers  
Repeated execution showed varied routing results, like real cloud load balancers

### Commands Used:
- echo
- nano
- chmod
- cat
- bash scripting
- RANDOM

# Reflection:
Today's lab helped me understand the concept of traffic distribution used by load balancers like Google Cloud Load Balancer. This simulation made clear how traffic is directed across multiple backend services to ensure high availability and scalability.
