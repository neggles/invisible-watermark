# invisible-watermark

A no-op implementation of [invisible-watermark](https://github.com/ShieldMnt/invisible-watermark/) designed
as a straight drop-in replacement, for use with libraries that depend on the original even when that
functionality is not used.

## How to use

```
python -m pip install 'git+https://github.com/neggles/invisible-watermark.git#egg=invisible-watermark'
```

If you need a specific version, clone the repo, add a git tag with the version # you need,
and run `python -m pip install -e .` - setuptools-scm should handle it from there. you can also build a
wheel if you like.
