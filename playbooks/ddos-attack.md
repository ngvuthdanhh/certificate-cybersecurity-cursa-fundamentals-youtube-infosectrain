# Playbook – DDoS Attack Response

## Objective
Maintain service availability during a Distributed Denial of Service attack.

## Steps
1. **Identification**
   - Detect traffic anomalies (sudden spikes, SYN floods).

2. **Containment**
   - Rate-limit traffic.
   - Apply geo-blocking if attack source is localized.

3. **Eradication**
   - Engage ISP or cloud DDoS mitigation services.
   - Block malicious IP ranges.

4. **Recovery**
   - Restore normal traffic routing.
   - Validate system performance.

5. **Lessons Learned**
   - Improve load balancing and redundancy.
   - Test DDoS mitigation strategy regularly.
