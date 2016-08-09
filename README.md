# linux-jaguar package for Arch &amp; Manjaro Linux
The Linux kernel with Interactive CPUFreq governor, BFQ i/o scheduler and tweaked config, for AMD Jaguar/Puma family CPU only.

This kernel is targeted at users on real AMD Jaguar/Puma-based mobile hardware.

Config tweaks so far:
- Set target CPU family to Jaguar (and Puma)
- Enable Interactive CPUFreq governor and set as default, remove others
- Enable BFQ and set as default
- Enable audio (AC97 &amp; HDA) power-save modes
- Enable support for new ACPI functions for AMD Carrizo and newer
- Set PCI-E ASPM to powersave by default
- Remove all virtualization guest support
- Remove a few of non-AMD CPU features
- Remove Intel P-state and Cpuidle drivers
- Remove KSM
- Remove KEXEC


Suggestions welcome, please make GitHub issues.
