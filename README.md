# docs-dev

> [!CAUTION]
> I recommend not committing anything to this repository. The repository may not be around for long (TBD).

The current state:
- `docs/index.html` is a placeholder HTML page hosted at `docs-dev.microbiomedata.org`
- When someone visits that web page in a web browser, the web browser gets redirected to the production docs site (i.e. `docs.microbiomedata.org`)

The plan (tentative):
- Implement a GitHub Actions workflow that can be used to pull source files from the `docs` repo, build a website from them, and deploy that website to `docs-dev.microbiomedata.org`. Team members unfamiliar with Docker can use that to preview changes they make.
- (OR) Delete this repository and the associated DNS records
