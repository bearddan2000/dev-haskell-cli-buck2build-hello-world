# Disclaimer
All projects that start with `dev`
are under active development.

This project is in development meaning
it does not produce expected results.

# Problem
Cant find toolchain.

# Error
BUILD FAILED
Error running analysis for `root//:cli (prelude//platforms:default#524f8da68ea2a374)`

Caused by:
    0: Error looking up configured node root//:cli (prelude//platforms:default#524f8da68ea2a374)
    1: Error looking up configured node toolchains//:cxx (prelude//platforms:default#524f8da68ea2a374) (prelude//platforms:default#524f8da68ea2a374)
    2: looking up unconfigured target node `toolchains//:cxx`
    3: Unknown target `cxx` from package `toolchains//`.
       Did you mean one of the 1 targets in toolchains//:BUCK?

# Possible solutions
Change config.