# Triptych artifacts

Exact archival assets for [Triptych](https://github.com/spincyc/triptych).
The Git tree contains delivery manifests and preservation tools; archival payloads
are attached to immutable releases.

Each delivery manifest records the original logical path, SHA-256, size, media
type and archive membership. The source repository retains the controlling
source identity, edition, rights record and page or line mapping. Downloading an
asset does not extend the distribution rights recorded for it.

The evidence release preserves exact source and historical publication bytes
from Triptych commit `2f23107c105e1f91f3cfebb64027ace149142416`. The print
release preserves the 278 PDFs served by the public site when the migration
was prepared, each checked against its published manifest digest. These are
archived print snapshots; current editions can be generated from their canonical
plaintext sources with Triptych's `print-document` tool. The review-handoff
release preserves the original five split ZIP chunks, including their embedded
PDFs, with exact chunk hashes and a reconstruction manifest.

Project-created metadata and software retain the source project's licenses.
Third-party source works and acquired facsimiles retain their individual rights;
see the original artifact records and `THIRD_PARTY.md` at the source commit.

The `papal-inputs-84c2f7e-v1` release preserves all 372 original frozen papal
release-input JSON and JSONL snapshots (685,669,809 exact bytes).
`papal-input-delivery.json` retains their original paths, hashes, sizes and
archive membership. Compact checked metadata in Triptych supports ordinary
reader validation; this archive retains the full original evidence for explicit
audit and offline replay. Storage relocation grants no new review or approval.
