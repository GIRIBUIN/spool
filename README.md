# SPOOL

A bounded durable forwarding buffer for a single Linux host.

SPOOL accepts events, durably stores acknowledged data, forwards it to a remote destination, and rejects new input rather than silently dropping previously accepted events when storage capacity is exhausted.

## Status

Design complete. Implementation in progress.