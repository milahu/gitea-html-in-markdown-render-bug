# gitlab bugs

## html tags as plain text

some html tags are rendered as plain text

```
<!doctype html>
  
some title body { font-size: 10pt; }
```

`some title` is the content of the `<title>` tag

`body { font-size: 10pt; }` is the content of the `<style>` tag

## symlink from readme.md is not working

gitlab renders the path of the symlink target, for example `index.html`,
instead of rendering the contents of the symlink target file like github or gitea

for testing gitlab, i added the folder [copy-instead-of-symlink/](copy-instead-of-symlink/)
