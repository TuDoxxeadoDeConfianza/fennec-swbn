# Fennec IWA update channel

- Web Bundle ID: `sxngouk6j3mxffldg6valxhhgeput5vmpc4abyjf2skgeylvobeaaaic`
- Current version: `1.1.42`
- Update manifest: [updates.json](https://raw.githubusercontent.com/TuDoxxeadoDeConfianza/fennec-swbn/main/updates.json)
- Signed bundle: [fennec-chromeos.swbn](https://raw.githubusercontent.com/TuDoxxeadoDeConfianza/fennec-swbn/main/fennec-chromeos.swbn)

The bundle is signed locally. The signing key is not stored in this repository.

To publish a later update, build and sign the new `.swbn` with the same signing key, replace the bundle, and change the matching version and `src` in `updates.json`. Keep the update manifest URL stable. Devices need to have installed version 1.1.42 once to start checking this update channel.
