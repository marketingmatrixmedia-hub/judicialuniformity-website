# judicialuniformity.website
Public evidence site for the Advocates for Judicial Uniformity audit of Georgia Magistrate Court
compliance with O.C.G.A. § 24-13-21(c). Static site (no build step). `index.html` is the report;
`evidence/` holds the 2026-07-28 source captures and `evidence/2026-11-26/` the re-verification
captures, each folder with its own SHA-256 manifest (`sha256sum -c SHA256SUMS.txt`).

Not yet deployed. The domain's DNS is on Vercel (nameservers ns1/ns2.vercel-dns.com); no project
is attached yet.
