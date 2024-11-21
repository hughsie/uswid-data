# uSWID-data

These are CycloneDX SBOMs already sent upstream; do not add here until submitted.

These can be used to suppliment building firmware while we wait for upstream projects to review,
and tag a new release with the trusted SBOM data.

To use this data, do something like this:

    uswid --fallback-path ~/uswid-data --find ~/edk2 --fixup

# Contributing

Pull requests will only be accepted if the commit description has a link to the upstream submission.
