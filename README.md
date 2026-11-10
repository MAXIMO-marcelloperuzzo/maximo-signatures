# Email signature images

Managed by the Email Signature Hub — please don't rename or move files by hand.
Signatures that are already installed (and emails already sent) load images from
these exact addresses.

| Path | What it is |
|---|---|
| `campaigns/manifest.json` | Current banner and click-through link for each brand |
| `campaigns/<brand>/banner.jpg` | The banner **every** signature of that brand shows. Replaced by **Admin → Publish banner to everyone** |
| `campaigns/<brand>/archive/` | Every banner published before, for reference |
| `go/<brand>/` | The banner's fixed link. Redirects to the current campaign |
| `signatures/<brand>/<person>-<date>/` | One person's signature images (7 files) |

Brands: `maximo`, `gmx`, `lumber`.

Folders directly under `signatures/` (no brand) and the images in the top level
come from earlier versions. Keep them while anyone's signature still uses them.
