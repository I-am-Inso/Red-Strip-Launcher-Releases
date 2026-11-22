> **Security notice:** Release **v1.8.8 is withdrawn and must not be installed.** Its update-signing key was exposed and has been rotated. Wait for a newer stable release with the replacement key. Existing v1.8.8 builds are not approved for use.

# Red Strip Launcher — Releases

This repository is the public distribution channel for the Windows application.

- Download installers from [Releases](https://github.com/I-am-Inso/Red-Strip-Launcher-Releases/releases).
- Only compiled distribution files belong here.
- Python source code and private build configuration remain in the private source repository.
- Release publication is automated from the private repository's Windows build workflow.

The signed update manifest and client-side Ed25519 verification are implemented in the application. The update feed remains inactive until the first signed stable release is published and an end-to-end Windows install/update/rollback test is completed.
