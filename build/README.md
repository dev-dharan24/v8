# V8 prebuilt zip

The prebuilt V8 archive is stored as split parts because GitHub rejects normal
repository files over 100 MiB and Git LFS uploads are blocked for public forks.

Reassemble it from this directory with:

```bash
cat linux-release_d8-asan-fuzzilli-sandbox-testing-linux-release-v8-component-108220.zip.part-* > linux-release_d8-asan-fuzzilli-sandbox-testing-linux-release-v8-component-108220.zip
sha256sum linux-release_d8-asan-fuzzilli-sandbox-testing-linux-release-v8-component-108220.zip
```

Expected SHA-256:

```text
7182d32aa0df7957789743b491dae7dcbf35608329ec510f299732ca40af8247
```

Original size: 305878621 bytes.
