# Incident Summary

**Incident Type:** Distributed Denial of Service (DDoS) – ICMP Flood  
**Duration:** 2 hours  
**Target:** Internal network services of a multimedia company offering web design, graphic design, and social media marketing.

### Event Description
- The company’s network services became unresponsive due to a flood of incoming ICMP packets.
- Normal traffic was blocked, preventing access to network resources.
- The incident management team blocked ICMP traffic, took non-critical services offline, and restored critical services.

### Root Cause
- An unconfigured firewall allowed unrestricted ICMP traffic.
- A malicious actor exploited this vulnerability to launch an ICMP flood.

### Immediate Response Actions
1. Blocked incoming ICMP packets at the firewall.  
2. Disabled non-essential network services to conserve bandwidth.  
3. Restored critical system functionality under controlled traffic conditions.  
