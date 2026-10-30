3DS emulator - GitHub Pages build
1. Make a GitHub repo, upload index.html and coi-serviceworker.js to the root (keep both together).
2. Settings -> Pages -> deploy from branch (main, / root).
3. Open https://<you>.github.io/<repo>/ ; the first load reloads once. This enables cross-origin isolation
   (SharedArrayBuffer / shared WebAssembly memory), which is needed for the multi-threaded engine.
The page is identical to the artifact build for now; the thread work will be switched on in this build only.
