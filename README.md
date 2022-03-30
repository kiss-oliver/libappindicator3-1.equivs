# libappindicator3-1.equivs
A built equivs package to circumvent `libappindicator3-1` dependencies in bullseye. `libappindicator3-1` is no longer supported in Debian 11 but multiple apps (including Slack for example) depend on it. An alternative is using `libayatana-appindicator3-1`. This is repo contains a mock `libappindicator3-1` package that points to `libayatana-appindicator3-1`. This way you don't need to install fishy versions of `libappindicator3-1` and the dependency remains satisfied even if your app receives an update.

## Usage

Download the `.deb` package then `sudo dpkg -i libappindicator3-1_1.0_all.deb`.

Alternatively, you can build the package yourself by downloading the `.equivs` file and then `equivs-build libappindicator3-1.equivs`

## Checksums

Checksums-Md5:

 80706d9c4aacc091685a1c01f2929bd0 2148 libappindicator3-1_1.0_all.deb
 
Checksums-Sha1:

 355b02140a3fb6ce3905e9ceb71a5420f83919cc 2148 libappindicator3-1_1.0_all.deb
 
Checksums-Sha256:

 7557d20a565f3d6efd40b1f8a48ca3cce9c234111351efb117b65963f38dee69 2148 libappindicator3-1_1.0_all.deb
