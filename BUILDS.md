# Build Log — Prime Download Manager

Sequential build numbers for every installer produced. The latest build is the one
currently published on the [Releases page](https://github.com/Emizo59/Prime-Download-Manager/releases).

> **Release rule:** every new public release **bumps the version** (`1.0 Beta N` → `1.0 Beta N+1`,
> `PROJECT_VERSION` `1.0.x`) **and** the build number, and updates `latest.json`. This keeps the
> in-app update check reliable for both older builds (version-based) and newer builds (build-based).

| Build | Date | Version | Notes |
|------:|------|---------|-------|
| **011** | 2026-06-22 | 1.0 Beta 10 | Fully verified Windows auto-update installation and relaunch logic. |
| 010 | 2026-06-22 | 1.0 Beta 9 | Fixed path resolution formatting for the silent installer on Windows using native path separators; improved administrative elevation prompt handling. |
| 009 | 2026-06-22 | 1.0 Beta 8 | Improved Windows auto-update installation and relaunch reliability; integrated official app logo in the update overlay UI; centralized browser extension ID configuration parameters; optimized standard input buffering. |
| 008 | 2026-06-22 | 1.0 Beta 7 | True one-click in-app auto-update; professional installer wizard imagery + refined pledge; 'Prime Download Manager (PDM)' user-agent; animated site download arrow. |
| 007 | 2026-06-22 | 1.0 Beta 6 | One-click in-app auto-update (download + silent install + relaunch); periodic update checks; Start-with-Windows on by default; tutorial only on first install; filename + outline + resize fixes. Built on the public repo's free Actions from private source. |
| 006 | 2026-06-22 | 1.0 Beta 5 | In-app feedback/crash form; build-number-based update detection; About + update check + crash reporting; EULA + publisher info; Apple-style site animations; download-filename fix. |
| 002 | 2026-06-21 | 1.0 Beta 4 | Windows exe + installer + downloads folder renamed to "Prime Download Manager". |
| 001 | 2026-06-21 | 1.0 Beta 4 | First public release build. |
