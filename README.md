# Bug Hunter

Find the bug in beginner-friendly JavaScript puzzles. Bug Hunter is a free,
standalone game for [FreeGameStore](https://freegamestore.online).

## Run from the project root:

```powershell
pnpm install
pnpm dev
```

Build and type-check with `pnpm build` and `pnpm typecheck`.

## Publish

From the project root, run `fgs check` and resolve any reported failures. Then
publish with:

```powershell
fgs publish --name bug-hunter --category "brain training" --type standalone --oneliner "Find the bug in beginner-friendly JavaScript puzzles."
```

The FGS CLI provisions the game repository and hosting when available. If
automatic provisioning is unavailable, it provides a submission issue for
maintainer review.

## Project layout

- `web/` — Vite, React, TypeScript, and the FreeGameStore Games SDK.
- `.github/workflows/deploy.yml` — FreeGameStore CI and deployment workflow.

## License

MIT.
