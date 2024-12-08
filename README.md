# cljd_min_repro_ext_types

Demonstrates type hinting issues on dart extension types via the web package

Dynamic warnings:

```
DYNAMIC WARNING: can't resolve member document on target type Window of library package:web/web.dart  at line: 13, column: 9, file: acme/main.cljd
DYNAMIC WARNING: can't resolve member createElement on target type Document of library package:web/web.dart  at line: 16, column: 9, file: acme/main.cljd
DYNAMIC WARNING: can't resolve member src on target type HTMLIFrameElement of library package:web/web.dart  at line: 48, column: 26, file: acme/main.cljd
```

Run on web platform:

```
clj -M:cljd flutter -d chrome
```
