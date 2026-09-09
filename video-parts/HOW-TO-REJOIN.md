# Demo Video — Split Into Parts

The demo video is split into 6 parts because GitHub rejects any single file over 100 MB.

Download **all 6 parts** into the same folder, then rejoin them with one of the commands below.

| Part | Size |
|------|------|
| `video.zip.part01` | 20 MB |
| `video.zip.part02` | 20 MB |
| `video.zip.part03` | 20 MB |
| `video.zip.part04` | 20 MB |
| `video.zip.part05` | 20 MB |
| `video.zip.part06` | 18.5 MB |

## Rejoin

**Windows (Command Prompt)**

```cmd
copy /b video.zip.part01+video.zip.part02+video.zip.part03+video.zip.part04+video.zip.part05+video.zip.part06 video.zip
```

**Windows (PowerShell)**

```powershell
cmd /c "copy /b video.zip.part01+video.zip.part02+video.zip.part03+video.zip.part04+video.zip.part05+video.zip.part06 video.zip"
```

**macOS / Linux**

```bash
cat video.zip.part* > video.zip
```

Then extract `video.zip` to get `Traditional APIs to Kong MCP servers.mp4`.

## Verify (optional)

The rejoined `video.zip` should have this SHA-256:

```
d6801623e45420d18cdabe6a933c6ddc7ca36df9338f4e285b82d7d48648071f
```

**Windows:**

```powershell
Get-FileHash video.zip -Algorithm SHA256
```

**macOS / Linux:**

```bash
shasum -a 256 video.zip
```

If the hash does not match, one of the parts downloaded incompletely — re-download it and rejoin.
