━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
✅ Elasticsearch security features have been automatically configured!
✅ Authentication is enabled and cluster connections are encrypted.

ℹ️  Password for the elastic user (reset with `bin/elasticsearch-reset-password -u elastic`):
  N6scTaBydV5VDk5OFEqz

ℹ️  HTTP CA certificate SHA-256 fingerprint:
  da613e3cd8b6de490f6ccff07240d73bee3cc64374d4d970330e94e4f2d032d0

ℹ️  Configure Kibana to use this cluster:
• Run Kibana and click the configuration link in the terminal when Kibana starts.
• Copy the following enrollment token and paste it into Kibana in your browser (valid for the next 30 minutes):
  eyJ2ZXIiOiI4LjUuMiIsImFkciI6WyIxMDAuNjQuMTAwLjY6OTIwMCJdLCJmZ3IiOiJkYTYxM2UzY2Q4YjZkZTQ5MGY2Y2NmZjA3MjQwZDczYmVlM2NjNjQzNzRkNGQ5NzAzMzBlOTRlNGYyZDAzMmQwIiwia2V5IjoiRFR2aDNZUUJOUGRsbFd4M05hTUE6ei1BNW83czZRdjJ3WGhQYXExM3BwZyJ9

ℹ️  Configure other nodes to join this cluster:
• On this node:
  ⁃ Create an enrollment token with `bin/elasticsearch-create-enrollment-token -s node`.
  ⁃ Uncomment the transport.host setting at the end of config/elasticsearch.yml.
  ⁃ Restart Elasticsearch.
• On other nodes:
  ⁃ Start Elasticsearch with `bin/elasticsearch --enrollment-token <token>`, using the enrollment token that you generated.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━