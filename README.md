hexcamp-coredns-sites
=====================

This is a temporary site containing just the "sites" CSV file which contains mappings of hexagons to IPFS CIDs.

When the repo is pushed to, a webhook on the Knative cluster is called, which triggers the Knative Eventing
pipeline to rebuild and publish DNS records to Hex.Camp.

# Testing

This section is used for test commits to see if events are being picked up by Knative.

* test21

# License

MIT or Apache 2
