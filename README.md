# vendor_xiaomi_pudding — moved to GitLab

The proprietary files for the **Xiaomi 17** (`pudding`) are hosted on GitLab:

**https://gitlab.com/xiaomi17-pudding-dev/vendor_xiaomi_pudding**

They are too large for GitHub: the stock odm partition alone is about 4.5 GB, and several
camera libraries are over GitHub's 100 MB file limit.

The local manifests in
[local_manifests_pudding](https://github.com/xiaomi17-pudding-dev/local_manifests_pudding)
fetch the vendor repository from GitLab; nothing in this GitHub repository is used by the
build.
