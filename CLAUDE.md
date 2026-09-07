# Lightridge club directory — project notes

- Club data lives in the CLUBS/CATS arrays inside the logic class of "LHS Club Directory.dc.html" (the source of truth).
- "LHS Club Fair Floor Plan.dc.html" reads the same data from club-data.js, which is GENERATED from the directory file.
- After ANY edit to clubs, sponsors, categories or meeting times, regenerate club-data.js by re-extracting the CATS and CLUBS arrays from the directory file, so the two pages never drift.
- Sponsor names are shown in honorific form (Ms./Mr./Dr./Sr./Sra. + last name).
