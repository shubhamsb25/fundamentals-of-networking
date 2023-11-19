
## Client server architecture

- machines are expensive, application are complex
- separate application in two components
- expensive workload on servers
- clients call servers to do expensive work
- RPC came into existence

## Benefits

- Servers can have beefy h/w, and can support multiple clients
- Clients have commodity h/w
- Clients can still perform lightweight work
- Client does not need dependencies, e.g. database drivers
- To communicate, we need standarized communication model