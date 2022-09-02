# magma-release

Update focal repo:
```bash
find . -type f -name Dockerfile -exec \
  sed -i '' "s/focal-ci/focal-1.8.0/g" {} \;
```
> command will only work on macOS


