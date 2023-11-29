# PWOSPF Test Cases

## Script to Check Link Failures
This Bash script is designed to automate the testing of network topology changes by turning off links (vhost1-vhost2 or vhost1-vhost3 or vhost2-vhost3) and pinging all the IP addresses in the toplogy. It takes two command-line arguments: `<topology_number>` and `<convergence_time>`.

### Usage

Copy all the files in the repo into your directory (stub_sr).

```bash ./check_link_failure.sh <topology_number> <convergence_time> ```

## Script to Ping All IP Addresses

This Bash script pings all the IP addresses present in your topology for 5 seconds and reports the success count. It also provides details about which IP addresses passed and which ones failed. It takes one command-line argument: `<topology_number>`


### Usage

Copy all the files in the repo into your directory (stub_sr).

```bash ./ping_all_ips.sh <topology_number>```
