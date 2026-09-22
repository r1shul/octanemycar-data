# OctaneMyCar Station Registry data

This public repository will hold versioned, machine-readable Station Registry
exports for India. The registry is derived from OpenStreetMap data distributed
by Geofabrik and may include accepted factual station corrections.

After the first successful import:

- `latest/` contains the current `stations.geojson`, `schema.json`,
  `manifest.json`, `SHA256SUMS`, and `LICENSE.txt`.
- `versions/<snapshot-id>/` keeps the corresponding immutable export.

Each manifest records source URL and timestamp, source checksum, generation
time, record count, attribution, and licence. Verify exported files against
`SHA256SUMS` before use.

Station Registry data is shared under the [Open Database License 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
Credit OpenStreetMap contributors and retain the licence and attribution when
redistributing a derived database. Contributor accounts, Availability Reports,
trust and moderation records, and private enrichment are not included.

No export has been published yet. The first version appears only after a
validated live import completes.
