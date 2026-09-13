# Agent development rules

## Architecture: no God Files

If source code is ever added to this release repository, keep each module cohesive and responsibility-focused. Do not accumulate unrelated UI, domain, networking, persistence, configuration, security or orchestration responsibilities in one source file. Split modules when responsibilities or coupling become unrelated. Generated binaries and release artifacts are exempt.
