# Network Troubleshooting Practice Lab

**Type:** Practice exercise  
**Goal:** Learn a basic workflow for investigating a device that cannot reach a website.

## Useful Windows commands
```bat
ipconfig
ipconfig /all
ping <default-gateway-address>
ping 1.1.1.1
nslookup example.com
tracert example.com
```
Replace placeholders with appropriate values. Record results from your own device; network policies and firewalls may affect results.

## Workflow
1. Check whether Wi-Fi or Ethernet is connected.
2. Run `ipconfig /all` and note the IPv4 address, default gateway, and DNS servers. Do not publish public IPs or other sensitive network details.
3. Test the default gateway if appropriate.
4. Test an external IP address, then use `nslookup` to check name resolution.
5. Compare whether one website or many services are affected.
6. Document the evidence and escalate if the issue may affect multiple users or requires network-admin access.

## Results to add after testing
- Device and connection type:
- Symptom:
- Commands run:
- Relevant output (redact private details):
- What the results suggest:
- Resolution or next test:
- Verification:
- Lesson learned:

**Caution:** A failed ping alone does not prove a device is offline; ICMP may be blocked.
