# Introduction

This repo contains a number of insecure sample projects for testing purposes. The source code were pulled from various other projects on GitHub and might fall under any license. Please do not use them for any commercial or production purposes.

## Some sample use cases

To test [sast-scan](https://github.com/AppThreat/sast-scan) project

Produce SAST report for a node.js project

```bash
docker run --rm --tmpfs /tmp -v ~/work/appthreat/insecure-sample-projects:/app appthreat/sast-scan scan --src /app --type nodejs --out_dir /app/reports --convert
```

## License

This repo is under MIT license but the underlying source code can be with any license attached. This repo should therefore be used only for local testing purposes.
