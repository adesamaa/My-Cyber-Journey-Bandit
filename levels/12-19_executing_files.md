# Levels 12-19: Text Processing & Data Extraction 

These levels teach you to manipulate and search text efficiently which is one of the most useful parts for SOC.
•  Level 12–13: Extracting readable text from binary/data files.
    •  Key takeaway: `strings` command + piping with `grep`.
    •  Real-world use: Searching logs or memory dumps for suspicious strings (very SOC-relevant).
•  Level 14–19: Base64 decoding, hexdump, compression (`gzip`/`bzip2`/`tar`/`zip`), and more advanced filtering.
    •  Key takeaway: `base64 -d`, `hexdump`, `gzip`, `tar`, and combining commands with pipes.
    •  Real-world use: Decoding encoded data or handling compressed logs/files in incident response.
occasionally, you would encounter files that are not human-readable until you decode them and these sets of commands helped unravel how to go about it step by step.﻿


