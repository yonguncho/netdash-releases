# NetDash releases

Download channel for **NetDash**, an offline network status dashboard for air-gapped
(closed) networks. It runs as a single Windows executable and makes no outbound calls.

## Download

- Latest build: [netdash.exe](https://github.com/yonguncho/netdash-releases/releases/latest/download/netdash.exe)
- Checksums: [SHA256SUMS.txt](https://github.com/yonguncho/netdash-releases/releases/latest/download/SHA256SUMS.txt)

Verify the download before running it:

```powershell
Get-FileHash netdash.exe -Algorithm SHA256
```

The hash must match the line for `netdash.exe` in `SHA256SUMS.txt`.

## More

- Guide and screenshots: <https://choiceguidelab.com/netdash-air-gapped-network-dashboard/>
- UI preview (sample data only): <https://yonguncho.github.io/netdash-releases/>
- Release notes: see each entry under [Releases](https://github.com/yonguncho/netdash-releases/releases).

This repository holds release binaries and the preview page only.
