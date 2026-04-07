# Firebase Studio

This is a NextJS starter in Firebase Studio.

To get started, take a look at src/app/page.tsx.
# BCA

## ✅ Submission Mode Checklist

- [x] **inference.py** follows sample format  
- [x] Environment variables present:
  - `API_BASE_URL` (default allowed)
  - `MODEL_NAME` (default allowed)
  - `HF_TOKEN` (read from env, no default)
- [x] Dockerfile CMD → `["python", "inference.py"]`
- [x] `openenv.yaml` present with 3+ tasks
- [x] Logs format compliant:
  - `[START] task=... env=... model=...`
  - `[STEP] step=... action=... reward=... done=... error=null`
  - `[END] success=... steps=... score=... rewards=...`
