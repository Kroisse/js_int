# 0.1.1

* Add doctests for every inherent method of `Int` and `UInt`
* Fix buggy implementation of `Int::saturating_mul`
* Add (optional) implementations of `rocket::{FromFormValue, FromParam}` (for rocket 0.4)

# 0.1.0

Initial release containing the `Int` and `UInt` types, `serde` support and many of the methods that
`std`'s integer types provide.
