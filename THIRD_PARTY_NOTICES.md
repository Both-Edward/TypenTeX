# 第三方组件许可（Third-Party Notices）

TypenTeX 随安装包分发以下第三方组件。各组件的版权与许可条款归其作者所有，
本清单仅用于履行 MIT / BSD / Apache-2.0 等许可证的署名义务。

- 生成日期：2026-11-05
- 组件总数：360（Rust / Tectonic 侧；Dart 侧由 Flutter 许可证页汇总）
- 适用版本：TypenTeX 0.0.2（versionCode 40）

本文档由源码仓库的 `tool/gen_notices.py` 从 `rust/Cargo.lock` 自动生成后
随安装包一并发布，请勿手工修改。依赖升级时会在新版本发布前重新生成。

许可证全文随安装包分发（APK 内 `assets/third_party_notices.txt`），
同内容以纯文本形式随本仓库发布：[THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt)，
也可在应用内通过「TypenTeX 菜单 → 开源许可 → 查看完整许可证文本」查看。

本文件只含组件清单与统计，各组件的许可证原文请见上述全文文件。

## 组件清单

| 组件 | 版本 | 许可证 |
| --- | --- | --- |
| encoding_rs | 0.8.44 | (Apache-2.0 OR MIT) AND BSD-3-Clause |
| unicode-ident | 1.0.27 | (MIT OR Apache-2.0) AND Unicode-3.0 |
| unicode-normalization | 0.1.26 | (MIT OR Apache-2.0) AND Unicode-3.0 |
| borsh-derive | 1.8.1 | Apache-2.0 |
| ignore-files | 3.0.8 | Apache-2.0 |
| miette | 7.6.0 | Apache-2.0 |
| miette-derive | 7.6.0 | Apache-2.0 |
| project-origins | 1.4.4 | Apache-2.0 |
| sync_wrapper | 1.0.2 | Apache-2.0 |
| unicode-bom | 2.0.3 | Apache-2.0 |
| watchexec | 8.4.4 | Apache-2.0 |
| watchexec-filterer-globset | 8.0.6 | Apache-2.0 |
| watchexec-filterer-ignore | 7.0.6 | Apache-2.0 |
| zopfli | 0.8.4 | Apache-2.0 |
| fnv | 1.0.7 | Apache-2.0 / MIT |
| ring | 0.17.14 | Apache-2.0 AND ISC |
| hyper-rustls | 0.27.10 | Apache-2.0 OR ISC OR MIT |
| rustls | 0.23.46 | Apache-2.0 OR ISC OR MIT |
| async-priority-channel | 0.2.0 | Apache-2.0 OR MIT |
| atomic-waker | 1.1.2 | Apache-2.0 OR MIT |
| autocfg | 1.5.1 | Apache-2.0 OR MIT |
| concurrent-queue | 2.5.0 | Apache-2.0 OR MIT |
| const-oid | 0.10.2 | Apache-2.0 OR MIT |
| equivalent | 1.0.3 | Apache-2.0 OR MIT |
| event-listener | 4.0.3 | Apache-2.0 OR MIT |
| fastrand | 2.5.0 | Apache-2.0 OR MIT |
| idna_adapter | 1.2.2 | Apache-2.0 OR MIT |
| indexmap | 2.14.2 | Apache-2.0 OR MIT |
| multiversion_no_op | 1.0.0 | Apache-2.0 OR MIT |
| normalize-path | 0.2.2 | Apache-2.0 OR MIT |
| parking | 2.2.1 | Apache-2.0 OR MIT |
| pin-project-lite | 0.2.17 | Apache-2.0 OR MIT |
| process-wrap | 9.1.1 | Apache-2.0 OR MIT |
| rustc-hash | 2.1.3 | Apache-2.0 OR MIT |
| simd_cesu8 | 1.2.0 | Apache-2.0 OR MIT |
| utf8_iter | 1.1.0 | Apache-2.0 OR MIT |
| utf8parse | 0.2.2 | Apache-2.0 OR MIT |
| utf_types | 1.0.0 | Apache-2.0 OR MIT |
| watchexec-events | 6.1.3 | Apache-2.0 OR MIT |
| watchexec-signals | 5.1.1 | Apache-2.0 OR MIT |
| watchexec-supervisor | 5.4.1 | Apache-2.0 OR MIT |
| watchexec-supervisor | 6.0.0 | Apache-2.0 OR MIT |
| zeroize | 1.9.1 | Apache-2.0 OR MIT |
| linux-raw-sys | 0.12.1 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT |
| rustix | 1.1.6 | Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT |
| zerocopy | 0.8.63 | BSD-2-Clause OR Apache-2.0 OR MIT |
| deunicode | 1.6.2 | BSD-3-Clause |
| subtle | 2.6.1 | BSD-3-Clause |
| notify | 8.2.1 | CC0-1.0 |
| dunce | 1.0.5 | CC0-1.0 OR MIT-0 OR Apache-2.0 |
| inotify | 0.11.5 | ISC |
| inotify-sys | 0.1.8 | ISC |
| rustls-webpki | 0.103.16 | ISC |
| untrusted | 0.9.0 | ISC |
| aws-lc-rs | 1.19.0 | ISC AND (Apache-2.0 OR ISC) |
| aws-lc-sys | 0.47.0 | ISC AND (Apache-2.0 OR ISC) AND Apache-2.0 AND MIT AND BSD-3-Clause AND (Apache-2.0 OR ISC OR MIT) AND (Apache-2.0 OR ISC OR MIT-0) |
| atomic-take | 1.1.0 | MIT |
| byte-unit | 5.2.6 | MIT |
| bytes | 1.12.1 | MIT |
| cfg_aliases | 0.2.2 | MIT |
| combine | 4.6.9 | MIT |
| endian-type | 0.2.0 | MIT |
| faster-hex | 0.10.1 | MIT |
| fs_extra | 1.3.0 | MIT |
| globwalk | 0.9.1 | MIT |
| h2 | 0.4.20 | MIT |
| html-escape | 0.2.15 | MIT |
| http-body | 1.1.0 | MIT |
| http-body-util | 0.1.5 | MIT |
| hyper | 1.12.0 | MIT |
| hyper-util | 0.1.21 | MIT |
| is-docker | 0.2.0 | MIT |
| is-wsl | 0.4.0 | MIT |
| libm | 0.2.16 | MIT |
| matchers | 0.2.0 | MIT |
| mio | 1.2.4 | MIT |
| nibble_vec | 0.1.0 | MIT |
| nix | 0.31.3 | MIT |
| nu-ansi-term | 0.50.3 | MIT |
| open | 5.4.5 | MIT |
| parse-zoneinfo | 0.3.1 | MIT |
| phf | 0.11.3 | MIT |
| phf_codegen | 0.11.3 | MIT |
| phf_generator | 0.11.3 | MIT |
| phf_macros | 0.11.3 | MIT |
| phf_shared | 0.11.3 | MIT |
| prodash | 31.0.1 | MIT |
| quick-xml | 0.39.4 | MIT |
| radix_trie | 0.3.0 | MIT |
| rust_decimal | 1.43.0 | MIT |
| schemars | 1.2.3 | MIT |
| sharded-slab | 0.1.7 | MIT |
| simd-adler32 | 0.3.10 | MIT |
| slab | 0.4.12 | MIT |
| strsim | 0.11.1 | MIT |
| synstructure | 0.14.0 | MIT |
| tectonic | 0.17.0 | MIT |
| tectonic_bridge_core | 0.5.3 | MIT |
| tectonic_bridge_flate | 0.1.10 | MIT |
| tectonic_bridge_fontconfig | 0.1.3 | MIT |
| tectonic_bridge_freetype2 | 0.3.2 | MIT |
| tectonic_bridge_graphite2 | 0.3.2 | MIT |
| tectonic_bridge_harfbuzz | 0.3.3 | MIT |
| tectonic_bridge_icu | 0.2.4 | MIT |
| tectonic_bridge_png | 0.1.2 | MIT |
| tectonic_bundles | 0.4.2 | MIT |
| tectonic_cfg_support | 0.1.5 | MIT |
| tectonic_dep_support | 0.1.2 | MIT |
| tectonic_docmodel | 0.3.1 | MIT |
| tectonic_engine_bibtex | 0.3.4 | MIT |
| tectonic_engine_spx2html | 0.4.3 | MIT |
| tectonic_engine_xdvipdfmx | 0.4.4 | MIT |
| tectonic_engine_xetex | 0.5.3 | MIT |
| tectonic_errors | 0.3.0 | MIT |
| tectonic_geturl | 0.4.1 | MIT |
| tectonic_io_base | 0.6.0 | MIT |
| tectonic_pdf_io | 0.5.3 | MIT |
| tectonic_status_base | 0.2.2 | MIT |
| tectonic_xdv | 0.3.0 | MIT |
| tectonic_xetex_layout | 0.3.4 | MIT |
| tera | 1.20.1 | MIT |
| tokio | 1.54.1 | MIT |
| tokio-macros | 2.7.2 | MIT |
| tokio-stream | 0.1.19 | MIT |
| tokio-util | 0.7.20 | MIT |
| tower | 0.5.3 | MIT |
| tower-http | 0.6.11 | MIT |
| tower-layer | 0.3.3 | MIT |
| tower-service | 0.3.3 | MIT |
| tracing | 0.1.44 | MIT |
| tracing-attributes | 0.1.31 | MIT |
| tracing-core | 0.1.36 | MIT |
| tracing-log | 0.2.0 | MIT |
| tracing-subscriber | 0.3.23 | MIT |
| try-lock | 0.2.5 | MIT |
| utf8-width | 0.1.9 | MIT |
| want | 0.3.2 | MIT |
| which | 8.0.6 | MIT |
| winnow | 1.0.4 | MIT |
| zip | 8.6.0 | MIT |
| zmij | 1.0.23 | MIT |
| android_system_properties | 0.1.6 | MIT OR Apache-2.0 |
| anstream | 1.0.0 | MIT OR Apache-2.0 |
| anstyle | 1.0.14 | MIT OR Apache-2.0 |
| anstyle-parse | 1.0.0 | MIT OR Apache-2.0 |
| anstyle-query | 1.1.5 | MIT OR Apache-2.0 |
| anyhow | 1.0.104 | MIT OR Apache-2.0 |
| arrayvec | 0.7.8 | MIT OR Apache-2.0 |
| base64 | 0.23.1 | MIT OR Apache-2.0 |
| bitflags | 2.13.2 | MIT OR Apache-2.0 |
| block-buffer | 0.12.1 | MIT OR Apache-2.0 |
| borsh | 1.8.1 | MIT OR Apache-2.0 |
| bstr | 1.13.1 | MIT OR Apache-2.0 |
| bumpalo | 3.20.3 | MIT OR Apache-2.0 |
| cc | 1.11.0 | MIT OR Apache-2.0 |
| cfg-if | 1.0.5 | MIT OR Apache-2.0 |
| chacha20 | 0.10.2 | MIT OR Apache-2.0 |
| chrono | 0.4.45 | MIT OR Apache-2.0 |
| chrono-tz | 0.9.0 | MIT OR Apache-2.0 |
| chrono-tz-build | 0.3.0 | MIT OR Apache-2.0 |
| clap | 4.6.7 | MIT OR Apache-2.0 |
| clap_builder | 4.6.7 | MIT OR Apache-2.0 |
| clap_complete | 4.6.11 | MIT OR Apache-2.0 |
| clap_derive | 4.6.7 | MIT OR Apache-2.0 |
| clap_lex | 1.1.1 | MIT OR Apache-2.0 |
| cmake | 0.1.58 | MIT OR Apache-2.0 |
| colorchoice | 1.0.5 | MIT OR Apache-2.0 |
| cpufeatures | 0.3.1 | MIT OR Apache-2.0 |
| crc32fast | 1.5.4 | MIT OR Apache-2.0 |
| crossbeam-deque | 0.8.8 | MIT OR Apache-2.0 |
| crossbeam-epoch | 0.9.21 | MIT OR Apache-2.0 |
| crossbeam-utils | 0.8.23 | MIT OR Apache-2.0 |
| crypto-common | 0.2.2 | MIT OR Apache-2.0 |
| defmt | 0.3.101 | MIT OR Apache-2.0 |
| defmt | 1.2.0 | MIT OR Apache-2.0 |
| defmt-macros | 1.2.0 | MIT OR Apache-2.0 |
| defmt-parser | 1.1.0 | MIT OR Apache-2.0 |
| digest | 0.11.3 | MIT OR Apache-2.0 |
| digest-io | 0.1.0 | MIT OR Apache-2.0 |
| directories | 6.0.0 | MIT OR Apache-2.0 |
| dirs-sys | 0.5.0 | MIT OR Apache-2.0 |
| displaydoc | 0.2.7 | MIT OR Apache-2.0 |
| dyn-clone | 1.0.20 | MIT OR Apache-2.0 |
| enrede | 0.2.0 | MIT OR Apache-2.0 |
| errno | 0.3.14 | MIT OR Apache-2.0 |
| find-msvc-tools | 0.1.15 | MIT OR Apache-2.0 |
| flate2 | 1.1.10 | MIT OR Apache-2.0 |
| form_urlencoded | 1.2.2 | MIT OR Apache-2.0 |
| futures | 0.3.34 | MIT OR Apache-2.0 |
| futures-channel | 0.3.34 | MIT OR Apache-2.0 |
| futures-core | 0.3.34 | MIT OR Apache-2.0 |
| futures-executor | 0.3.34 | MIT OR Apache-2.0 |
| futures-io | 0.3.34 | MIT OR Apache-2.0 |
| futures-macro | 0.3.34 | MIT OR Apache-2.0 |
| futures-sink | 0.3.34 | MIT OR Apache-2.0 |
| futures-task | 0.3.34 | MIT OR Apache-2.0 |
| futures-util | 0.3.34 | MIT OR Apache-2.0 |
| getrandom | 0.2.17 | MIT OR Apache-2.0 |
| getrandom | 0.3.4 | MIT OR Apache-2.0 |
| getrandom | 0.4.3 | MIT OR Apache-2.0 |
| gix-actor | 0.43.0 | MIT OR Apache-2.0 |
| gix-config | 0.61.0 | MIT OR Apache-2.0 |
| gix-config-value | 0.20.0 | MIT OR Apache-2.0 |
| gix-date | 0.17.0 | MIT OR Apache-2.0 |
| gix-error | 0.4.0 | MIT OR Apache-2.0 |
| gix-features | 0.50.0 | MIT OR Apache-2.0 |
| gix-fs | 0.23.0 | MIT OR Apache-2.0 |
| gix-glob | 0.28.0 | MIT OR Apache-2.0 |
| gix-hash | 0.27.0 | MIT OR Apache-2.0 |
| gix-hashtable | 0.17.0 | MIT OR Apache-2.0 |
| gix-lock | 25.0.0 | MIT OR Apache-2.0 |
| gix-object | 0.65.0 | MIT OR Apache-2.0 |
| gix-path | 0.13.0 | MIT OR Apache-2.0 |
| gix-ref | 0.68.0 | MIT OR Apache-2.0 |
| gix-sec | 0.15.0 | MIT OR Apache-2.0 |
| gix-tempfile | 25.0.0 | MIT OR Apache-2.0 |
| gix-trace | 0.2.0 | MIT OR Apache-2.0 |
| gix-utils | 0.4.0 | MIT OR Apache-2.0 |
| gix-validate | 0.12.0 | MIT OR Apache-2.0 |
| hash32 | 0.3.1 | MIT OR Apache-2.0 |
| hashbrown | 0.17.1 | MIT OR Apache-2.0 |
| heapless | 0.8.0 | MIT OR Apache-2.0 |
| heck | 0.5.0 | MIT OR Apache-2.0 |
| http | 1.5.0 | MIT OR Apache-2.0 |
| httparse | 1.10.1 | MIT OR Apache-2.0 |
| hybrid-array | 0.4.15 | MIT OR Apache-2.0 |
| iana-time-zone | 0.1.65 | MIT OR Apache-2.0 |
| idna | 1.1.0 | MIT OR Apache-2.0 |
| ipnet | 2.12.2 | MIT OR Apache-2.0 |
| is_terminal_polyfill | 1.70.2 | MIT OR Apache-2.0 |
| itoa | 1.0.18 | MIT OR Apache-2.0 |
| jni | 0.22.4 | MIT OR Apache-2.0 |
| jni-macros | 0.22.4 | MIT OR Apache-2.0 |
| jni-sys | 0.4.1 | MIT OR Apache-2.0 |
| jni-sys-macros | 0.4.1 | MIT OR Apache-2.0 |
| jobserver | 0.1.35 | MIT OR Apache-2.0 |
| lazy_static | 1.5.1 | MIT OR Apache-2.0 |
| libc | 0.2.191 | MIT OR Apache-2.0 |
| libz-sys | 1.1.31 | MIT OR Apache-2.0 |
| lock_api | 0.4.14 | MIT OR Apache-2.0 |
| log | 0.4.35 | MIT OR Apache-2.0 |
| md-5 | 0.11.0 | MIT OR Apache-2.0 |
| memmap2 | 0.9.12 | MIT OR Apache-2.0 |
| mime | 0.3.17 | MIT OR Apache-2.0 |
| notify-types | 2.2.0 | MIT OR Apache-2.0 |
| num-traits | 0.2.19 | MIT OR Apache-2.0 |
| once_cell | 1.21.4 | MIT OR Apache-2.0 |
| parking_lot | 0.12.5 | MIT OR Apache-2.0 |
| parking_lot_core | 0.9.12 | MIT OR Apache-2.0 |
| percent-encoding | 2.3.2 | MIT OR Apache-2.0 |
| pest | 2.9.5 | MIT OR Apache-2.0 |
| pest_derive | 2.9.5 | MIT OR Apache-2.0 |
| pest_generator | 2.9.5 | MIT OR Apache-2.0 |
| pest_meta | 2.9.5 | MIT OR Apache-2.0 |
| pest_stack_guard | 1.0.1 | MIT OR Apache-2.0 |
| pinot | 0.1.5 | MIT OR Apache-2.0 |
| pkg-config | 0.3.34 | MIT OR Apache-2.0 |
| ppv-lite86 | 0.2.21 | MIT OR Apache-2.0 |
| proc-macro-crate | 3.5.0 | MIT OR Apache-2.0 |
| proc-macro2 | 1.0.107 | MIT OR Apache-2.0 |
| quinn | 0.11.12 | MIT OR Apache-2.0 |
| quinn-proto | 0.11.19 | MIT OR Apache-2.0 |
| quinn-udp | 0.5.16 | MIT OR Apache-2.0 |
| quote | 1.0.47 | MIT OR Apache-2.0 |
| rand | 0.8.8 | MIT OR Apache-2.0 |
| rand | 0.9.5 | MIT OR Apache-2.0 |
| rand | 0.10.3 | MIT OR Apache-2.0 |
| rand_chacha | 0.3.1 | MIT OR Apache-2.0 |
| rand_chacha | 0.9.0 | MIT OR Apache-2.0 |
| rand_core | 0.6.4 | MIT OR Apache-2.0 |
| rand_core | 0.9.5 | MIT OR Apache-2.0 |
| rand_core | 0.10.1 | MIT OR Apache-2.0 |
| rand_pcg | 0.10.2 | MIT OR Apache-2.0 |
| ref-cast | 1.0.27 | MIT OR Apache-2.0 |
| ref-cast-impl | 1.0.27 | MIT OR Apache-2.0 |
| regex | 1.13.1 | MIT OR Apache-2.0 |
| regex-automata | 0.4.18 | MIT OR Apache-2.0 |
| regex-syntax | 0.8.11 | MIT OR Apache-2.0 |
| reqwest | 0.13.5 | MIT OR Apache-2.0 |
| rustc_version | 0.4.1 | MIT OR Apache-2.0 |
| rustls-pki-types | 1.15.1 | MIT OR Apache-2.0 |
| rustls-platform-verifier | 0.7.1 | MIT OR Apache-2.0 |
| rustls-platform-verifier-android | 0.2.0 | MIT OR Apache-2.0 |
| rustversion | 1.0.23 | MIT OR Apache-2.0 |
| scopeguard | 1.2.0 | MIT OR Apache-2.0 |
| semver | 1.0.28 | MIT OR Apache-2.0 |
| serde | 1.0.229 | MIT OR Apache-2.0 |
| serde_core | 1.0.229 | MIT OR Apache-2.0 |
| serde_derive | 1.0.229 | MIT OR Apache-2.0 |
| serde_json | 1.0.154 | MIT OR Apache-2.0 |
| serde_spanned | 1.1.2 | MIT OR Apache-2.0 |
| sha1dc | 0.1.5 | MIT OR Apache-2.0 |
| sha2 | 0.11.1 | MIT OR Apache-2.0 |
| shlex | 2.0.1 | MIT OR Apache-2.0 |
| signal-hook-registry | 1.4.8 | MIT OR Apache-2.0 |
| simdutf8 | 0.1.5 | MIT OR Apache-2.0 |
| siphasher | 1.0.4 | MIT OR Apache-2.0 |
| smallvec | 1.16.4 | MIT OR Apache-2.0 |
| socket2 | 0.6.5 | MIT OR Apache-2.0 |
| stable_deref_trait | 1.2.1 | MIT OR Apache-2.0 |
| syn | 2.0.119 | MIT OR Apache-2.0 |
| syn | 3.0.9 | MIT OR Apache-2.0 |
| tar | 0.4.46 | MIT OR Apache-2.0 |
| tempfile | 3.27.0 | MIT OR Apache-2.0 |
| thiserror | 2.0.21 | MIT OR Apache-2.0 |
| thiserror-impl | 2.0.21 | MIT OR Apache-2.0 |
| thread_local | 1.1.10 | MIT OR Apache-2.0 |
| tokio-rustls | 0.26.6 | MIT OR Apache-2.0 |
| toml | 1.1.8+spec-1.1.0 | MIT OR Apache-2.0 |
| toml_datetime | 1.1.2+spec-1.1.0 | MIT OR Apache-2.0 |
| toml_edit | 0.25.18+spec-1.1.0 | MIT OR Apache-2.0 |
| toml_parser | 1.1.5+spec-1.1.0 | MIT OR Apache-2.0 |
| toml_writer | 1.1.3+spec-1.1.0 | MIT OR Apache-2.0 |
| typed-path | 0.12.4 | MIT OR Apache-2.0 |
| typenum | 1.20.1 | MIT OR Apache-2.0 |
| ucd-trie | 0.1.7 | MIT OR Apache-2.0 |
| unicode-segmentation | 1.13.3 | MIT OR Apache-2.0 |
| unicode-width | 0.1.14 | MIT OR Apache-2.0 |
| url | 2.5.8 | MIT OR Apache-2.0 |
| xattr | 1.7.0 | MIT OR Apache-2.0 |
| lru-slab | 0.1.3 | MIT OR Apache-2.0 OR Zlib |
| bitflags | 1.3.2 | MIT/Apache-2.0 |
| filetime | 0.2.29 | MIT/Apache-2.0 |
| humansize | 2.1.3 | MIT/Apache-2.0 |
| slug | 0.1.6 | MIT/Apache-2.0 |
| vcpkg | 0.2.15 | MIT/Apache-2.0 |
| option-ext | 0.2.0 | MPL-2.0 |
| icu_collections | 2.4.0 | Unicode-3.0 |
| icu_locale_core | 2.4.0 | Unicode-3.0 |
| icu_normalizer | 2.4.0 | Unicode-3.0 |
| icu_normalizer_data | 2.4.0 | Unicode-3.0 |
| icu_properties | 2.4.0 | Unicode-3.0 |
| icu_properties_data | 2.4.0 | Unicode-3.0 |
| icu_provider | 2.4.0 | Unicode-3.0 |
| litemap | 0.8.3 | Unicode-3.0 |
| potential_utf | 0.1.6 | Unicode-3.0 |
| tinystr | 0.8.5 | Unicode-3.0 |
| writeable | 0.6.4 | Unicode-3.0 |
| yoke | 0.8.4 | Unicode-3.0 |
| yoke-derive | 0.8.4 | Unicode-3.0 |
| zerofrom | 0.1.8 | Unicode-3.0 |
| zerofrom-derive | 0.1.8 | Unicode-3.0 |
| zerotrie | 0.2.5 | Unicode-3.0 |
| zerovec | 0.11.9 | Unicode-3.0 |
| zerovec-derive | 0.11.7 | Unicode-3.0 |
| aho-corasick | 1.1.5 | Unlicense OR MIT |
| byteorder | 1.5.0 | Unlicense OR MIT |
| globset | 0.4.21 | Unlicense OR MIT |
| ignore | 0.4.34 | Unlicense OR MIT |
| jiff | 0.2.39 | Unlicense OR MIT |
| jiff-core | 0.1.2 | Unlicense OR MIT |
| jiff-static | 0.2.39 | Unlicense OR MIT |
| memchr | 2.8.3 | Unlicense OR MIT |
| termcolor | 1.4.1 | Unlicense OR MIT |
| same-file | 1.0.6 | Unlicense/MIT |
| walkdir | 2.5.0 | Unlicense/MIT |
| zlib-rs | 0.6.8 | Zlib |
| bytemuck | 1.25.2 | Zlib OR Apache-2.0 OR MIT |
| bytemuck_derive | 1.12.1 | Zlib OR Apache-2.0 OR MIT |
| tinyvec | 1.13.3 | Zlib OR Apache-2.0 OR MIT |

## 按许可证统计

| 许可证 | 组件数 |
| --- | --- |
| MIT OR Apache-2.0 | 179 |
| MIT License | 85 |
| Apache-2.0 OR MIT | 25 |
| Unicode License v3 | 18 |
| Apache License 2.0 | 11 |
| Unlicense OR MIT | 9 |
| MIT/Apache-2.0 | 5 |
| ISC License | 4 |
| Zlib OR Apache-2.0 OR MIT | 3 |
| (MIT OR Apache-2.0) AND Unicode-3.0 | 2 |
| Apache-2.0 OR ISC OR MIT | 2 |
| Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT | 2 |
| BSD 3-Clause License | 2 |
| Unlicense/MIT | 2 |
| (Apache-2.0 OR MIT) AND BSD-3-Clause | 1 |
| Apache-2.0 / MIT | 1 |
| Apache-2.0 AND ISC | 1 |
| BSD-2-Clause OR Apache-2.0 OR MIT | 1 |
| CC0 1.0 Universal | 1 |
| CC0-1.0 OR MIT-0 OR Apache-2.0 | 1 |
| ISC AND (Apache-2.0 OR ISC) | 1 |
| ISC AND (Apache-2.0 OR ISC) AND Apache-2.0 AND MIT AND BSD-3-Clause AND (Apache-2.0 OR ISC OR MIT) AND (Apache-2.0 OR ISC OR MIT-0) | 1 |
| MIT OR Apache-2.0 OR Zlib | 1 |
| Mozilla Public License 2.0 | 1 |
| zlib License | 1 |

## 关于内置（vendored）修改

为适配平板编辑与预览，TypenTeX 修改了两个开源组件并以内置（vendored）
方式编译进安装包：

- `flutter_code_editor`（Apache-2.0）：行号对齐、折叠与输入法修复；
- `pdfx`（MIT）：渲染线程、翻页预取、页码同步与失败重试。

修改后的源码不对外分发，仅以二进制形式随应用发布。按 Apache-2.0 第 4(b) 条，修改事实与范围在应用内许可证页首条「TypenTeX 内置修改的开源组件」中说明，
相关源文件均带 `VENDORED PATCH` 注释。
