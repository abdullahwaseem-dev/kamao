<p align="center"><img src="docs/readme-banner.svg" width="100%" alt="Kamao: Account, verification, and balance-management screens." /></p>

<p align="center"><a href="#project-guide">Project guide</a> · <a href="https://github.com/abdullahwaseem-dev/kamao/tree/master">Browse source</a> · <a href="https://github.com/abdullahwaseem-dev">Developer profile</a></p>

<a id="project-guide"></a>

# Kamao — Flutter · GetX

A Flutter application prototype centred on account onboarding, verification, dashboard, balance, package, and withdrawal screens. It demonstrates GetX navigation and responsive UI structure.

## Highlights

- Login, signup, OTP, and password-reset screens.
- Dashboard and account/settings interfaces.
- Balance, packages, verification, and withdrawal UI.

## Run locally

Use a Flutter SDK whose bundled Dart version satisfies `>=3.4.4 <4.0.0`, as declared in [pubspec.yaml](pubspec.yaml). Configure the platform toolchain for your intended device.

```sh
git clone https://github.com/abdullahwaseem-dev/kamao.git
cd kamao
flutter pub get
flutter run
```

## Source map

- [lib/main.dart](lib/main.dart)
- [lib/views/dashboard.dart](lib/views/dashboard.dart)
- [lib/views/withdraw_view.dart](lib/views/withdraw_view.dart)

## Current scope

The presence of balance and withdrawal screens does not establish a working payment or payout service. Treat financial operations as unverified until the backend and transaction flows are tested.

## Verification

```sh
flutter analyze
flutter test
```

These commands describe how to check the project; they were not run as part of the documentation refresh. Platform directories and declared dependencies do not prove that every target builds successfully.


---

## Author and project links

Built by [Muhammad Abdullah Waseem](https://github.com/abdullahwaseem-dev). [Portfolio](https://abdullah-waseem.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/abdullahwaseem-dev/) · [Project enquiries](mailto:maw112266@gmail.com)

For a bug report, include the affected version, environment, reproduction steps, and expected behaviour in [Issues](https://github.com/abdullahwaseem-dev/kamao/issues). If the project is useful to you, a star is appreciated.

**Reuse:** no root license file was found during this review. Public visibility alone does not grant permission to reuse the code; contact the author for terms.

