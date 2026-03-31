# mounriver-toolchain-mirror

Mirror repository for MounRiver toolchain artifacts used by CI/build environments.

This repository is intended to host large toolchain files as GitHub Release assets,
not as regular git-tracked files.

Planned first asset:

- `MRS_Toolchain_Linux_X64_V240.tar.xz`

Why releases:

- avoids GitHub's normal file-size limits in git history
- keeps clone size small
- gives us a stable download target for Docker/CI
