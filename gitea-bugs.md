# gitea bugs

## html tags as plain text

some html tags are rendered as plain text

```
<!doctype html>

<html lang="en"> <head> </head>

</html>
```

## headings with broken permalinks

headings without ids like

```
<h1>heading 1</h1>
```

have the broken permalink `#`

on github, this heading has the permalink `#heading-1`
