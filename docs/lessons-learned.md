# Engineering lessons learned

[Home](../README.md)

1. **Distinguish initial design from completed installation.** The early plan included a Hikvision label; the installed wireless devices were standardized to TP-Link Archer AX10 according to the lead.
2. **Centralize the network hierarchy.** A clear ISP modem → router → switch → wired AP arrangement is easy to explain and troubleshoot without inventing port details.
3. **Uniform SSIDs are not a protocol test.** The lead observed smooth movement across AP coverage, while roaming-assistance features and timed interruption remain candidates for a formal test.
4. **Keep traceable field evidence.** Dated cable-installation photos and the historical channel sheet provide a stronger engineering story than marketing metrics alone.
5. **Close the loop on incidents.** The publicly anonymized `AP-X` incident report and later normal-operation confirmation can coexist; the exact root cause still deserves a timestamped private incident record if available.
6. **Separate client permissions from technical truth.** A location can be publicly mapped without implying permission to publish detailed internal topology, site images, resident data or client contacts.

## Possible follow-on improvements

Document a consented as-built port map and per-floor measurement results. Maintain a separate private archive of original photographs while publishing only approved, sanitized derivatives.
