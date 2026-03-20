<div align="center">

🌟 &nbsp; **h** &nbsp; ⚡

an inline-only microframework of generic pure-swift hashes, checksums, and binary utilities

[documentation and api reference](https://swiftinit.org/docs/h)

</div>


## Requirements

The h library requires Swift 6.0 or later.


| Platform | Status |
| -------- | ------ |
| 💬 Documentation | [![Documentation](https://github.com/rarestype/h/actions/workflows/Documentation.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/Documentation.yml) |
| 🐧 Linux | [![Tests](https://github.com/rarestype/h/actions/workflows/Tests.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🍏 Darwin | [![Tests](https://github.com/rarestype/h/actions/workflows/Tests.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/Tests.yml) |
| 🍏 Darwin (iOS) | [![iOS](https://github.com/rarestype/h/actions/workflows/iOS.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/iOS.yml) |
| 🍏 Darwin (tvOS) | [![tvOS](https://github.com/rarestype/h/actions/workflows/tvOS.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/tvOS.yml) |
| 🍏 Darwin (visionOS) | [![visionOS](https://github.com/rarestype/h/actions/workflows/visionOS.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/visionOS.yml) |
| 🍏 Darwin (watchOS) | [![watchOS](https://github.com/rarestype/h/actions/workflows/watchOS.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/watchOS.yml) |
| 🤖 Android | [![Tests](https://github.com/rarestype/h/actions/workflows/Android.yml/badge.svg)](https://github.com/rarestype/h/actions/workflows/Android.yml) |


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
