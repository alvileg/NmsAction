# NmsAction

This action builds NMS and adds artifacts to `$WORKSPACE/nms-build`.


# Usage

```yaml
- uses: alvileg/nmsaction@v1
  with:
    rev: 1.18.2
- name: Install nms into m2
  	run: mkdir -p $HOME/.m2/repository && cp -a nms-build/.m2/repository/. $HOME/.m2/repository
```
