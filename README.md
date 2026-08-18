# Evonic

AI Agent Platform (Streamlit + Python)

## Deployment

Image tersedia di GHCR:

```bash
docker pull ghcr.io/khamami13/evonic:latest
docker run -d --name evonic -p 8080:8080 ghcr.io/khamami13/evonic:latest
```

## Notes

- Source code tidak disertakan di repo ini (built image only).
- Konfigurasi dan secrets harus disediakan via env vars atau volume mount.
- Jangan commit file sensitif ke repo.
