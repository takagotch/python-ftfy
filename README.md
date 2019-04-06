### python-ftfy
---
https://github.com/LuminosoInsight/python-ftfy

```py
print(fix_encoding("(xxx)"))

print(fix_text('xxx'))
print(fix_text('xxx'))
print(fix_text('Broken text&hellip; it&#x2019;s flubberific!',
  normalization='NFKC'))
print(fix_text('HTML entities &lt;3'))
print(fix_text('<em>HTML entities in HTML &lt;3</em>'))
print(fix_text('\001\033[xxx '
  'doo&#133;\033[0m', normalization-'NFKC'))
print(fix_text(''))
print(fix_text('', fix_character_width=False))
```

```
pip install ftfy
pip install 'ftfy<5'
```

```
@misc{speer-2019-ftfy,
  author = {Robyn Speer},
  title = {ftfy},
  note = {Version 5.5},
  year = 2019,
  howpublished = {Zendo},
  doi = {10.5281/zenodo.2591652},
  url = {https://doi.org/10.5281/zenodo.2591652}
}
```


