# Distributed-Shell-Environment

This project simulates the working of a distributed shell, that acts as an interface to interact with powerful systems, without the use of SSH.
This approach uses sockets, transferring commands and outputs back and forth between the two systems. This is applicable to applications which have high computation time, but provide smaller length results. This is a very basic approach to the problem, working with very small files and assuming the system connected to has the same configuration of the system querying it.

## Usage
On system 1 : `gcc shell.c`
On system 2 : `gcc master.c`
Then you may run any command from shell.c and the desired output is displayed below.
