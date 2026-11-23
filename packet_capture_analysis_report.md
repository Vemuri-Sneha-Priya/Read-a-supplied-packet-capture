# Packet Capture Analysis Report

**Student:** Vemuri Sneha Priya  
**Organization:** EdBytes  
**Domain:** Cyber Security  
**Milestone:** 4 – Read a Supplied Packet Capture

## 1. Objective
Inspect the supplied synthetic packet capture in Wireshark, identify the HTTP method and path, identify the requested DNS training name, and explain the visibility limitations of encrypted traffic.

## 2. Environment
- Operating system: [Fill in]
- Wireshark version: [Fill in]
- Supplied capture filename: [Exact filename from starter pack]

## 3. HTTP Analysis
- **Display filter used:** `http`
- **Packet/frame number:** [Record actual frame number]
- **HTTP method:** [Record observed method]
- **Request path:** [Record observed path]
- **Observation:** [Briefly explain what the request shows]

## 4. DNS Analysis
- **Display filter used:** `dns`
- **Packet/frame number:** [Record actual frame number]
- **Requested training name / query:** [Record exact observed query name]
- **Observation:** [Briefly explain what the DNS query shows]

## 5. Encrypted Traffic and Visibility
HTTP traffic without transport encryption may expose application-layer details such as request methods and paths to a packet observer.

HTTPS protects HTTP application data using TLS. A passive observer ordinarily cannot read the encrypted HTTP method, path, headers, or body from the encrypted application-data records. Some metadata, such as IP addresses, ports, packet sizes, timing, and DNS information (depending on the DNS protocol and encryption), may still be visible. Do not claim that all traffic metadata is hidden.

## 6. Testing and Boundary Case
- **Ordinary inspection:** [Describe opening the supplied capture and applying `http` and `dns` filters.]
- **Boundary/failure case:** [Describe a relevant case supported by the supplied capture or guide, such as applying a filter with no matching packets. Record what Wireshark actually displayed.]
- **Result:** [Record actual observations.]

## 7. Conclusion
[Summarize the actual HTTP method, request path, DNS query name, and the visibility limitation introduced by encryption.]

## 8. Evidence
- Screenshot 1 – HTTP filter: [Filename]
- Screenshot 2 – DNS filter: [Filename]
