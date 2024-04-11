# copium

patches to chromium allowing to build with gcc, libstdc++,
and some other common distro fixes (like unbundle scripts).

as of M124, chromium still cannot be built with both clang
and libstdc++. choose your poison. if it's the former,
you're in the right place.

some patches are cherry-picks from chromium main branch,
some sourced from gentoo.

patches are prefixed by software and its version branch,
e.g. `cr124-` means chromium M124, and `e30-` means electron 30-x-y.
chromium might still require patches made for previous versions
without any changes - the number will not change in that case.
similarly, building electron 30 will require `cr124` patches as well.

---

still looking for a job. see [liberda.nl](https://liberda.nl/)
if interested.

these patches are provided "as-is", with no warranty of any kind.
use at your own risk. might stop getting updated for new releases.
