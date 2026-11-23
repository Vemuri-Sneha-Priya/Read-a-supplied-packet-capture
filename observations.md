# Packet Capture Observations

Use only the supplied synthetic EdBytes capture.

## HTTP observation
- Filter: `http`
- Frame number: [Actual frame]
- Method: [Actual method]
- Path: [Actual path]
- Notes: [Your observation]

## DNS observation
- Filter: `dns`
- Frame number: [Actual frame]
- Query name: [Actual training name]
- Notes: [Your observation]

## Ordinary test
- Action: Opened the supplied capture and applied the HTTP and DNS display filters.
- Actual result: [Record what Wireshark displayed.]

## Boundary/failure test
- Action: [For example, apply a filter that has no matches, if appropriate to the supplied capture and guide.]
- Actual result: [Record the exact result.]
- Learning: [Explain what an empty result means; it does not prove that the network has no such traffic outside this capture.]

## Learning
Encrypted HTTPS application data is not ordinarily readable as plain HTTP by a passive packet observer. DNS visibility depends on whether traditional DNS or an encrypted DNS protocol is used.
