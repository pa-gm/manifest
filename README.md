# Paranoid Android #

```bash

# Init local repo
repo init -u https://github.com/pa-gm/manifest -b uvite

# Lazy
repo init --depth=1 -u https://github.com/pa-gm/manifest -b uvite

# Sync
repo sync --current-branch --no-tags -j$(nproc --all)
```