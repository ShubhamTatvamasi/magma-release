# magma-release

Update focal and debian repo:
```bash
find . -type f -name Dockerfile -exec \
  sed -i '' "s/focal-ci/focal-1.8.0/g" {} \;

find . -type f -name Dockerfile -exec \
  sed -i '' "s/debian-test/debian/g" {} \;
```
> command will only work on macOS


