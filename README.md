# Persona Harness Attestation Claim Fixture

This public Java/Spring Gradle fixture exists only to produce an original
GitHub Artifact Attestation from a fixed push-to-main workflow for claim
inspection research.

The workflow runs fixed Gradle test and build commands, uploads a jar plus a
digest-only bundle, and attests that bundle. It does not receive secrets or
upload raw build logs. No branch-protection policy is assumed or claimed.
