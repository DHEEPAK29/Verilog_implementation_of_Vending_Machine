# Verilog_implementation_of_Vending_Machine

A circuit that can be used to control a vending machine. The circuit has five inputs: Q (quarter), D (dime), N (nickel), Coin, and Resetn. When a coin is deposited in the machine, a coin-sensing mechanism generates a pulse on the appropriate input (Q, D, or N). To signify the occurrence of the event, the mechanism also generates a pulse on the line Coin. The circuit is reset by using the Resetn signal (active low). When at least 30 cents has been deposited, the circuit activates its output, Z. No change is given if the amount exceeds 30 cents.
