### AHB-to-APB UVM Testbench – Package and Test

The `ahb2apb_pkg.sv` file defines the UVM package and includes the components required for the AHB-to-APB bridge verification environment, including AHB and APB agents, transaction classes, drivers, monitors, sequencers, virtual sequences, scoreboard, environment configuration, and test classes. The `ahb2apb_test.sv` file defines the base test, which configures the AHB and APB agents, retrieves their virtual interfaces through the UVM configuration database, and creates the verification environment. It also includes `single_test` and `burst_test`, which execute virtual sequences to verify single and burst transfers through the bridge.

