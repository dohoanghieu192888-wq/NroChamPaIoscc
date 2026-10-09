# NroChamPaIoscc

Unity iOS export của **NroChamPa**, build file `.ipa` (unsigned) trên GitHub Actions.

- Hướng dẫn build: [BUILD-IPA.md](BUILD-IPA.md)
- Workflow CI: [.github/workflows/build-ipa.yml](.github/workflows/build-ipa.yml)

Các thư viện Unity lớn (`Libraries/libiPhone-lib.a`, `libil2cpp.a`, `baselib.a`)
được lưu bằng **Git LFS** — cần `git lfs pull` trước khi build.
