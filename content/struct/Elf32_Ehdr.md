---
title: "Elf32_Ehdr"
current_name: "Elf32_Ehdr"
aliases: ["Elf32_Ehdr"]
tags: ["type/struct"]
address: "Elf32_Ehdr"
last_sync: "2026-03-09"
---

> [!info] Auto-Generated Specs
> **Struct:** `Elf32_Ehdr`
> **Size:** `52` bytes

## Fields
| Offset | Field | Type | Description |
| --- | --- | --- | --- |
| 0x0 | `e_ident_magic_num` | `byte` |  |
| 0x1 | `e_ident_magic_str` | `string` |  |
| 0x4 | `e_ident_class` | `byte` |  |
| 0x5 | `e_ident_data` | `byte` |  |
| 0x6 | `e_ident_version` | `byte` |  |
| 0x7 | `e_ident_osabi` | `byte` |  |
| 0x8 | `e_ident_abiversion` | `byte` |  |
| 0x9 | `e_ident_pad` | `byte[7]` |  |
| 0x10 | `e_type` | `word` |  |
| 0x12 | `e_machine` | `word` |  |
| 0x14 | `e_version` | `dword` |  |
| 0x18 | `e_entry` | `dword` |  |
| 0x1C | `e_phoff` | `dword` |  |
| 0x20 | `e_shoff` | `dword` |  |
| 0x24 | `e_flags` | `dword` |  |
| 0x28 | `e_ehsize` | `word` |  |
| 0x2A | `e_phentsize` | `word` |  |
| 0x2C | `e_phnum` | `word` |  |
| 0x2E | `e_shentsize` | `word` |  |
| 0x30 | `e_shnum` | `word` |  |
| 0x32 | `e_shstrndx` | `word` |  |

## Analysis
empty for now

## Manual Relations
empty for now
