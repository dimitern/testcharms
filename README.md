# testcharms
Juju charms and bundles used for testing networking features

## server-nc
Simple ubuntu charm with extra-bindings in metadata and hooks, which just log what's happening..
Can be related to the client-nc charm below.

## client-nc
Same as above, simple ubuntu charm with (different) extra-bindings and hooks.
Can be related to the server-nc charm.

## bundle
Deploys one unit of server-nc and client-nc in LXD containers, specifying bindings.
