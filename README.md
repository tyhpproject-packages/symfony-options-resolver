<!-- tyhp-readme:start -->
# tyhpdef/symfony-options-resolver

Tyhp type definitions for `symfony/options-resolver` `7.4.8`.

```bash
composer require --dev tyhpdef/symfony-options-resolver:7.4.8
```

This is a metapackage. Composer also installs `tyhpdef/symfony-options-resolver-impl` (type files).
Require **this** name, not `tyhpdef/symfony-options-resolver-impl`.

See https://tyhplang.com.

## Maintain `symfony/options-resolver`? Ship the types yourself

If you are a Packagist maintainer of `symfony/options-resolver`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-options-resolver-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/options-resolver` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-options-resolver": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/options-resolver` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/options-resolver` with a real constraint,
   `"replace": { "tyhpdef/symfony-options-resolver": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/options-resolver` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-options-resolver` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
