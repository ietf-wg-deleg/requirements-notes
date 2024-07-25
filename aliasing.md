# Aliasing

## Support on the parent side

- The protocol must be able to specify multiple target servers that will serve the authoritative information about the child zone
- The protocol must be able to specify expected transports for target servers
- The protocol might be able to specify public keys for secure transports
- The protocol might be able to specify address records for target servers

## Support on the aliased side

- The pointed-to server must be able to specify all authoritative records for the child zone
- The pointed-to server might be able to re- point to different authoritative servers (to some level of depth)
- The pointed-to server might be able to indicate the list of names that it serves so that resolvers can pre-populate delegation records
