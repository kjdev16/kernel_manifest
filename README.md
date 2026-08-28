## Repo Init ##
```bash
repo init -u https://github.com/kjdev16/kernel_manifest.git -b devonf
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```