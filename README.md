<div align="center">

🌟 &nbsp; **h** &nbsp; ⚡

an inline-only microframework of generic pure-swift hashes, checksums, and binary utilities

[documentation and api reference](https://swiftinit.org/docs/h)

</div>


## Requirements

The h library requires Swift 6.0 or later.

<!-- DO NOT EDIT BELOW! AUTOSYNC CONTENT [STATUS TABLE] -->
| Platform | Status |
| -------- | ------ |
| 💬 Documentation | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Documentation/_all/status.svg)](https://github.com/rarestype/h/actions/workflows/Documentation.yml) |
|  | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Documentation/Linux/status.svg)](https://github.com/rarestype/h/actions/workflows/Documentation.yml) |
|  | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Documentation/macOS/status.svg)](https://github.com/rarestype/h/actions/workflows/Documentation.yml) |
| 🐧 Linux | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Tests/Linux/status.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🍏 Darwin | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Tests/macOS/status.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🍏 Darwin (iOS) | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Tests/iOS/status.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🍏 Darwin (tvOS) | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Tests/tvOS/status.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🍏 Darwin (visionOS) | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Tests/visionOS/status.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🍏 Darwin (watchOS) | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Tests/watchOS/status.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🤖 Android | [![Status](https://raw.githubusercontent.com/rarestype/h/refs/badges/ci/Tests/Android/status.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
<!-- DO NOT EDIT ABOVE! AUTOSYNC CONTENT [STATUS TABLE] -->

[Check deployment minimums](https://swiftinit.org/docs/h#ss:platform-requirements)


## products

This package vends the following library products:

1.  [`Base16`](https://swiftinit.org/docs/h/base16)

    Tools for encoding to and decoding from base-16 strings.

1.  [`Base64`](https://swiftinit.org/docs/h/base64)

    Tools for encoding to and decoding from base-64 strings.

1.  [`CRC`](https://swiftinit.org/docs/h/crc)

    Implements [CRC-32](https://en.wikipedia.org/wiki/Cyclic_redundancy_check) checksums.

1.  [`MD5`](https://swiftinit.org/docs/h/md5)

    Implements [MD5](https://en.wikipedia.org/wiki/MD5) hashing function.

1.  [`MessageAuthentication`](Sources/MessageAuthentication)

    Implements [hash-based message authentication codes](https://en.wikipedia.org/wiki/HMAC) (HMACs) through protocols that types in the other modules conform to.

1.  [`SHA1`](https://swiftinit.org/docs/h/sha1)

    Unimplemented: [SHA-1](https://en.wikipedia.org/wiki/SHA-1) hashing function.

1.  [`SHA2`](https://swiftinit.org/docs/h/sha2)

    Implements the [SHA-256](https://en.wikipedia.org/wiki/SHA-2) hashing function.

1.  [`UUID`](https://swiftinit.org/docs/h/uuid)

    Provides a UUID type.
