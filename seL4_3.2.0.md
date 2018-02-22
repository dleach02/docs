# Introducing seL4 3.2.0


  -   ARM Hypervisor support.
  -   ARM Jetson-TK1: Cleanup.
  -   Benchmarking now supports tracking of syscalls.
  -   Support for XSAVE feature set for x86 CPUs.
  -   Simplified ARM platform selection during configuration.

# Implementation improvements


-   Several enhancements for both {{{x86}}} and {{{ARM}}} have
    been made. Please see the commit log for details.

# API Changes


  -   No API changes in this release.

# ABI Changes


  -   {{{seL4\_BootInfo}}} has a new entry for IOSpace caps for
      ARM SMMU.

# Upgrade notes


  -   This release is source compatible.

# Full changelog


Use {{{git log 3.1.0..3.2.0}}} in <https://github.com/seL4/seL4>

# More details


See the
[3.2.0 manual](http://sel4.systems/Info/Docs/seL4-manual-3.2.0.pdf) included in the release for detailed descriptions of the new
features. Or ask on the mailing list!