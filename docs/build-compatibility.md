## Build Compatibility Matrix - Lumos-G1 v1.1

| Build tag           | Analysis scope* | Boot.img verified | Patch status** | App status***    | Release date | Notes                                            |
|---------------------|-----------------|:-----------------:|----------------|------------------|--------------|--------------------------------------------------|
| G1_DE-V2.10.250416  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-06-24   | current firmware in app                         |
| G1_EN-V2.20.250410  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-06-24   | current firmware in app                         |
| G1_FR-V3.06.250510  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-06-24   | current firmware in app                         |
| G1_FR-V3.03.250113  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-05-11   | —                                               |
| G1_EN-V2.14.250109  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-05-11   | —                                               |
| G1_DE-V2.08.250113  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-05-11   | —                                               |
| G1_DE-V2.07.241011  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-05-11   | —                                               |
| G1_EN-V2.07.241008  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-05-11   | —                                               |
| G1_FR-V3.02.241011  | Full            | ✅               | ✅ ready       | ✅ works         | 2025-05-11   | —                                               |
| G1_FR-V3.00.240418  | Partial         | ✅               | ✅ ready       | ✅ works         | 2025-06-30   | —                                               |
| G1_EN-V2.06.240418  | Partial         | ❌               | ✅ ready       | ✅ works         | 2025-05-11   | subset only - patch tested & functional on G1   |
| V2.00.231120-       | Partial         | ❌               | ✅ ready       | ⚠️ test needed | 🕐 WIP  | — |
| G1-1.39             | Partial         | ❌               | ✅ ready       | ⚠️ BETA TEST   | 🕐 WIP  | — |
| G1-1.38             | Partial         | ✅               | ✅ ready       | ⚠️ test needed | 🕐 WIP  | — |
| G1-1.36             | Partial         | ✅               | ✅ ready       | ⚠️ test needed | 🕐 WIP  | — |
| G1-1.35             | Partial         | ✅               | ✅ ready       | ⚠️ test needed | 🕐 WIP  | — |
| G1-1.30             | Partial         | ❌               | ✅ ready       | ⚠️ test needed | 🕐 WIP  | — |
| G1-1.24             | Partial         | ❌               | ✅ ready       | ⚠️ test needed | 🕐 WIP  | — |
| G1-1.17             | Partial         | ❌               | ✅ ready       | ⚠️ test needed | 🕐 WIP  | — |

\* **Analysis scope** : `Full` = entire firmware, `Partial` = subset only  
\** **Patch status** : ability to create the patch/xdelta (`✅ ready`, `⚠️ tweak`, `❌ no`)  
\*** **App status** : whether the Lumos app can apply the patch (`✅ works`, `⚠️ update needed`, `❌ unsupported`)
