---
layout: page
title: "Intel 80286 CPU Errata: Extra Prefixes"
permalink: /pubs/pc/reference/intel/80286/extra_prefixes/
---

Intel 80286 CPU Errata: Extra Prefixes
---

[The following information is from an Intel document titled "80286 ARPL and Overlength Instructions, 15 October 1984"]

### Instructions Longer than 10 Bytes

When the CPU detects an instruction that is illegal due to being greater than 10 bytes in length, it generates an
exception #13 (General Protection Violation) instead of exception #6 (Invalid Opcode). The only way an instruction
greater than ten bytes can occur is by using the assembler to intentionally place multiple redundant prefix bytes
(e.g. multiple lock prefixes and/or segment override prefixes) before the opcode bytes.

There are no plans to change this functionality of the 80286 and future editions of the "iAPX286 Programmer's Reference
Manual" and 80286 datasheet will accurately describe how 80286 reacts to instructions greater than 10 bytes in length.

[Return to [Intel 80286 CPU Information](/pubs/pc/reference/intel/80286/)]
