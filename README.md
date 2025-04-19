# mini-rpa-playwright

## 1. Repository Setup

- [x] Create GitHub repo `mini-rpa-playwright`
- [x] Initialize with:
  - `README.md`
  - `.gitignore` (Python, Docker)
  - `LICENSE` (MIT)
  - `CODE_OF_CONDUCT.md`
  - `CHANGELOG.md`
- [x] Add directory structure:

  ```bash
  .
  ├── src/
  ├── tests/
  ├── .github/
  │   └── workflows/
  ├── Dockerfile
  ├── requirements.txt
  └── .env.example
  ```

## 2. Core Script Development

- [ ] Define dependencies in `requirements.txt`
- [ ] Write `src/main.py`:
  - [ ] Load config via `dotenv`
  - [ ] Launch Playwright headless browser
  - [ ] Perform scripted actions to simulate RPA flow
  - [ ] Log each step and handle errors
  - [ ] Exit with status code 0 on success
- [ ] Implement CLI entrypoint with `argparse` flags

## 3. Testing

- [ ] Create `tests/test_main.py`
  - [ ] Test `.env` loads successfully
  - [ ] Test `main()` returns success code
- [ ] Run `pytest` locally; ensure tests pass

## 4. Continuous Integration

- [ ] Add `.github/workflows/ci.yml`
- [ ] Verify CI passes on GitHub
- [ ] Add CI status badge to `README.md`

## 5. Documentation & Demo

- [ ] Draft `README.md` with elevator pitch, prerequisites, quickstart, usage examples, architecture diagram, license
- [ ] Record 15‑sec GIF of script running
- [ ] Embed GIF and Mermaid diagram in README
- [ ] Update `CHANGELOG.md` for `v0.1.0`

## 6. Containerization

- [ ] Write `Dockerfile` to package app
- [ ] Build & test image locally
- [ ] Push image to Azure Container Registry (optional)

## 7. (Stretch) Azure Container App Deployment

- [ ] Draft deployment template or CLI commands
- [ ] Deploy and schedule 30‑min job trigger

## 8. Release & Share

- [ ] Tag `v0.1.0` and create release notes
- [ ] Pin repo on GitHub profile
- [ ] Link repo in `PORTFOLIO_PLAN.md`