# Privacy Frames installer

GitHub Pages publication for <https://install.pf.damenh.com/>.

Implementation and tests live in [privacy-frames/host](https://github.com/privacy-frames/host).
`installation-host-ref.txt` selects the tested host commit. The workflow builds
only its installation role and publishes the resulting static files. It does
not run application interfaces or serve confined applications.

Deployment requires the repository variable `PAGES_ENABLED=true`. Update the
source pin only after verifying the corresponding host, runtime and installer.
