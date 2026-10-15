<!-- written by scripts/status-collect on 2026-10-15T01:38:33Z -->
The Worker passes every probe.

Worker: https://ghcr.mirror.archlinux.pkgforge.dev. Each probe is a GET with no redirect followed. A target with `latest` must answer 302 to https://*.githubusercontent.com. A target with no `latest` must answer 404.

| target | probe | HTTP | expected | seconds | result |
| --- | --- | --- | --- | --- | --- |
| aarch64-alarm | db | 302 | 302 | 0.475413 | ok |
| aarch64-alarm | package | 302 | 302 | 0.567153 | ok |
| aarch64-aur | db | 302 | 302 | 0.323563 | ok |
| aarch64-aur | package | 302 | 302 | 0.309384 | ok |
| aarch64-core | db | 302 | 302 | 0.318463 | ok |
| aarch64-core | package | 302 | 302 | 0.342785 | ok |
| aarch64-extra | db | 302 | 302 | 0.402804 | ok |
| aarch64-extra | package | 302 | 302 | 0.359694 | ok |
| armv7h-alarm | db | 302 | 302 | 0.314485 | ok |
| armv7h-alarm | package | 302 | 302 | 0.233904 | ok |
| armv7h-aur | db | 302 | 302 | 0.310699 | ok |
| armv7h-aur | package | 302 | 302 | 0.313206 | ok |
| armv7h-core | db | 302 | 302 | 0.339321 | ok |
| armv7h-core | package | 302 | 302 | 0.307516 | ok |
| armv7h-extra | db | 302 | 302 | 0.319012 | ok |
| armv7h-extra | package | 302 | 302 | 0.305303 | ok |
| loong64-core | db | 302 | 302 | 0.314185 | ok |
| loong64-core | package | 302 | 302 | 0.216227 | ok |
| loong64-extra | db | 302 | 302 | 0.289090 | ok |
| loong64-extra | package | 302 | 302 | 0.371157 | ok |
| riscv64-core | db | 302 | 302 | 0.360155 | ok |
| riscv64-core | package | 302 | 302 | 0.230013 | ok |
| riscv64-extra | db | 302 | 302 | 0.557761 | ok |
| riscv64-extra | package | 302 | 302 | 0.305344 | ok |
| x86_64-core | db | 302 | 302 | 0.287376 | ok |
| x86_64-core | package | 302 | 302 | 0.225795 | ok |
| x86_64-extra | db | 302 | 302 | 0.307300 | ok |
| x86_64-extra | package | 302 | 302 | 0.216600 | ok |
| x86_64-multilib | db | 302 | 302 | 0.299964 | ok |
| x86_64-multilib | package | 302 | 302 | 0.216863 | ok |

This issue closes itself when the Worker passes its probes again.
