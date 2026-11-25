# AHB-to-APB-Bridge-Protocol-Verification-using-UVM
- Developed a UVM-based testbench to verify the communication between the AHB and APB interfaces of a bus bridge.
- Created AHB and APB agents with their respective drivers, monitors, sequencers, and transaction classes to generate and observe bus activity.
- Implemented single-transfer and burst-transfer test scenarios, including incrementing and wrapping address patterns.
- Built a scoreboard to compare AHB and APB transaction data and addresses, with functional coverage to track transfer sizes, types, address regions, read/write operations, and APB slave selections.
