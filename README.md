# cinnamon

**This image is considered alpha**

[![release-please](https://github.com/ublue-os/cinnamon/actions/workflows/release-please.yml/badge.svg)](https://github.com/ublue-os/cinnamon/actions/workflows/release-please.yml)

![image](https://user-images.githubusercontent.com/1264109/236370188-cbbfa831-65b7-48ca-9c8c-d67c777b0f62.png)


## Rebase

    rpm-ostree rebase ostree-image-signed:docker://ghcr.io/legacy-images/cinnamon-main:latest

or if you have an NVIDIA GPU:

    rpm-ostree rebase ostree-image-signed:docker://ghcr.io/legacy-images/cinnamon-nvidia:latest

<br>

## Caveats

- Thanks to @jerbmega for the lightdm workaround!
