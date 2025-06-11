# waku-conflicting-hmr-port-reproduction


Bug:

```sh
demo-app-2:dev: warn: Port 3000 is in use, trying 3001 instead.
demo-app-1:dev: ready: Listening on http://localhost:3000/
demo-app-2:dev: ready: Listening on http://localhost:3001/
demo-app-1:dev: WebSocket server error: Port 24678 is already in use
```

Repliace via `bun run dev`

Issue: https://github.com/wakujs/waku/issues/1464#issuecomment-2958946653