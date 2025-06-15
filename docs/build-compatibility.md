## Build Compatibility Matrix

| Build tag           | Analysis scope* | Boot.img verified | Patch status** | App status*** | Release date | Notes                                              |
|---------------------|-----------------|---------------|----------------|---------------|--------------|----------------------------------------------------|
| G1_FR-V3.03.250113  | Full            | ✅            | ✅ ready       | ✅ works      | 2025-05-11   | current firmware                                   |
| G1_EN-V2.14.250109  | Full            | ✅            | ✅ ready       | ✅ works      | 2025-05-11   | current firmware                                   |
| G1_DE-V2.08.250113  | Full            | ✅            | ✅ ready       | ✅ works      | 2025-05-11   | current firmware                                   |
| G1_DE-V2.07.241011  | Full            | ✅            | ✅ ready       | ✅ works      | 2025-05-11   | —                                                  |
| G1_EN-V2.07.241008  | Full            | ✅            | ✅ ready       | ✅ works      | 2025-05-11   | —                                                  |
| G1_FR-V3.02.241011  | Full            | ✅            | ✅ ready       | ✅ works      | 2025-05-11   | —                                                  |
| G1_EN-V2.06.240418  | Partial         | ❌            | ✅ ready       | ✅ works      | 2025-05-11   | subset only - patch tested & functional on G1      |
| G1-1.24             | Partial         | ❌            | ✅ ready       | ⚠️ update needed | Not planned  | different naming format – Lumos-G1 overhaul required   |
| G1-1.38             | Partial         | ❌            | ✅ ready       | ⚠️ update needed | Not planned  | different naming format – Lumos-G1 overhaul required   |

\* **Analysis scope** : `Full` = entire firmware, `Partial` = subset only  
\** **Patch status** : ability to create the patch/xdelta (`✅ ready`, `⚠️ tweak`, `❌ no`)  
\*** **App status** : whether the Lumos app can apply the patch (`✅ works`, `⚠️ update needed`, `❌ unsupported`)
