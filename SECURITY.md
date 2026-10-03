# Security policy

## Supported versions

Security fixes go into the latest release of TypeMaster. At the moment that is **0.1.2**.

| Version | Supported |
|:--------|:---------:|
| 0.1.2 | Yes |
| Earlier releases | No |

## Reporting a vulnerability

Please **do not open a public issue** for a security problem.

Email **[contact@ntxm.org](mailto:contact@ntxm.org)** with:

- what you found and the version of TypeMaster (shown in the installer and in Settings > Apps),
- your version of Windows,
- steps to reproduce it, and the impact you think it has.

Do not attach private or confidential files. If a file is needed to reproduce the problem, describe it or make a harmless sample.

You can expect an acknowledgement and a plain reply on whether we can reproduce it. Please give us reasonable time to fix a problem before you publish details.

## Good to know

- TypeMaster works offline and has no accounts. It makes two optional requests when online (a launch counter and Google Fonts). See [PRIVACY.md](PRIVACY.md).
- Check your download against the SHA-256 in the [README](README.md#download) or on the [release page](https://github.com/typemaster-by-ntxm/typemaster/releases/tag/v0.1.2). Only download the app from this repository or from [ntxm.org](https://ntxm.org).
- The Windows installer is not code-signed yet, so SmartScreen will warn you on first start. That is expected for this build.
