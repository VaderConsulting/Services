# Services

VB6 ActiveX DLL (`Service.dll` / `clsService`): query, start, stop, and pause Windows services on a named machine through the Service Control Manager APIs. Distinct from sibling `Service-Monitoring` (which also ships a monitor exe).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Service` (`Service.vbp`) | VB6 | ActiveX DLL | SCM query/start/stop/pause helpers (`clsService`) |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Service.vbp`

Then compile and register the DLL.

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Services`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
