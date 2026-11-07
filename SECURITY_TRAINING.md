# Secret-scanning training — verified exercise evidence

This repository exists solely for the free **GitHub Skills Introduction to Secret Scanning** course.

- Public-repository secret scanning and push protection were enabled and verified.
- The instructor-provided inactive AWS and MongoDB examples were detected by GitHub secret scanning.
- The sample AWS access-key ID alert was resolved as **Used in tests**, rather than claiming that a real key had been revoked.
- An attempt to commit the instructor-provided *inactive* GitHub PAT example was **blocked** by GitHub repository push protection (HTTP 409).
- **No push-protection bypass was requested**, and no real credentials or user API keys were used.
- The inactive examples were deleted from the current default branch after the course; previous Git history retains educational commits.

For real incidents: revoke exposed credentials at their provider, rotate replacements, remove exposed materials from current source and consider documented history-rewrite procedures.
