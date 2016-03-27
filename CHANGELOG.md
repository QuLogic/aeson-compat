# 0.3.2.0

- Introduce instances from `aeson-0.11.1.0`: `Const`, `Tagged`, `Proxy` and `NonEmpty`
- Fix bug with `Natural` instance, `aeson-0.11.1.0` and `base <=4.7`

# 0.3.1.0

- `aeson-0.11` support
- GHC 8.0.1 support
- Add `ToJSON` `Day` and `LocalTime` instances
  - *NOTE* this instances are broken in `aeson-0.10.0.0`
- Add `Natural`, `Ordering` and `Version` instances

# 0.3.0.0

Split out `aeson-extra`
