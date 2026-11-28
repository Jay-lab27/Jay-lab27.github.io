# HARI tariff updates

This directory serves HARI's signed, maintained tariff catalog. It is not a government service or an official government endorsement.

Catalog v2 currently contains two reviewed LRT-2 single-journey ticket route pairs: Recto - Antipolo (PHP 18) and Recto - Cubao (PHP 13), either direction. LRTA Citizen's Charter 2026, 2nd Edition, Annex A and B was visually checked against LRTA's current tickets-and-fares page on 28 November 2026. These published prices already include the applicable 50% reduction; no additional discount is stacked. Stored-value Beep fares differ.

This is limited route-pair coverage, not verification of the whole rail line or all Philippine fares. Existing bus, jeepney, tricycle and other presets remain unverified until their applicable documents can be reviewed. LTFRB retrieval returned HTTP 403; Dagupan's document requires additional effectivity and fare-rule review.

App version code 9 uses `catalog-v2.json` (schema 2). The earlier `catalog-v1.json` remains unchanged for older app compatibility. Installing the new build is necessary to add these exact route presets and read the new feed.

Only entries reviewed against an applicable official document may update eligible app-managed presets. Source URLs, issuing authorities, effective dates, review dates and document hashes accompany approved entries. Custom rates remain under the user's control.

Catalog expiry or a failed download preserves existing rates. HARI displays the check result without claiming that preserved rates are current. Publication occurs only after maintained source review; daily download does not mean every source was independently rechecked that day.

Contact: bitdevwork@gmail.com
