Description:
------------
iperf is a tool for active measurements of the maximum achievable
bandwidth on IP networks.

Inputs Needed To Run Tests:
---------------------------
interface		- interface on which test run
peer_ip			- IP of the Peer interface to be tested
peer_user_name		- Username in Peer system to be used
IPERF_SERVER_RUN	- Whether to run iperf server in peer or not (1 to run, 0 to not run)
EXPECTED_THROUGHPUT	- Expected Throughput as a percentage (1-100)

Requirements:
-------------
1. Generate sshkey for your test partner to run the test uninterrupted.
2. Install netifaces using pip. command: pip install netifaces
Peer machine.
