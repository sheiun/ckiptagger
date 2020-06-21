# CkipTagger

## Documentation

- [Wiki](https://github.com/ckiplab/ckiptagger/wiki)
- [GitHub](https://github.com/ckiplab/ckiptagger/)

## New feature

Get top k possible pos

```python
>>> pos([["友", "增", "吾", "簡"]], k=2)
[[['Nb', 'Na'], ['VC', 'VJ'], ['Nep', 'Nh'], ['Na', 'VH']]]
>>> pos([["友", "增", "吾", "簡"]], k=3)
[[['D', 'Nb', 'Na'], ['VG', 'VC', 'VJ'], ['Nes', 'Nep', 'Nh'], ['Nb', 'Na', 'VH']]]
```
