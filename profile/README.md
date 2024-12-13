## Mobile Verification Toolkit (MVT) Project

Welcome to the **MVT Project** repository! This open-source community is focused on developing tools to help to identify potential compromise of Android and iOS devices.

Our primary projects include **MVT** and **AndroidQF**.

---

## Key Projects

### Mobile Verification Toolkit (MVT)

<img src="https://docs.mvt.re/en/latest/mvt.png" width="200" />

**MVT** is a powerful **consensual** forensic tool designed to help analyze mobile devices for signs of spyware. It provides:

- Support for both iOS and Android devices.
- Automated scans for traces of spyware, malware, or other malicious activities based on a set of [community-maintained Indicators of Compromise (IOCs)](https://github.com/mvt-project/mvt-indicators).
- Outputs data in JSON for use in manual threat hunting and further analysis.  

[Explore the MVT docs]()
[Explore MVT](https://github.com/mvt-project/mvt)
[Read the MVT Quick Start](_)

---

### AndroidQF

**AndroidQF** (Android Quick Forensics) is a forensic data collection tool for Android devices.

No analysis is performed by AndroidQF itself. Data collected with AndroidQF can later be parsed and analysed using MVT. AndroidQF features include: 

- Automated collection of Android forensic data which can be relevant for spyware forensics (Bugreport, Android backup etc.)
- Deploying on-device `collector` agent to reliably collect forensic data without relying on limited Android shell environments. 
- Collecting suspicious or unknown Android APK files from a device.
- Cross-platform support on Windows, Mac and Linux.

[Explore AndroidQF ](https://github.com/mvt-project/androidqf)

---

## Contributing

We welcome contributions from the community! Here’s how you can get involved:

1. **Read the Contribution Guidelines**: Make sure to review our [MVT Contribution Guidelines](https://github.com/mvt-project/mvt/blob/main/CONTRIBUTING.md) to understand the process.
2. **Open a Discussion**: Have a feature request, bug report, or idea? Start a conversation in the [Discussions](https://github.com/mvt-project/mvt/discussions) section.
3. **Submit a Pull Request**: If you’ve implemented a feature or fixed a bug, submit a PR for review.

---

## License

This project is licensed under the [MVT License](https://github.com/mvt-project/license).

---

## Join the Community

- [GitHub Discussions](https://github.com/mvt-project/mvt/discussions)
- [Issue Tracker](https://github.com/mvt-project/mvt/issues)

---

We’re excited to have you on board and can’t wait to see how you contribute to the MVT Project! Together, we can make security and quality assurance accessible to all.
