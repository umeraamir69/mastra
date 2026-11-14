---
"@mastra/modal": patch
---

Map `clone({ idleTimeoutMinutes })` to Modal's native `idleTimeoutMs` instead of the hard `timeoutMs` lifetime, and pass `idleTimeoutMs` on sandbox create
