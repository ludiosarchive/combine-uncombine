# combine-uncombine

`combine-files` combines files into one big file (with filename headers).
This is useful for batch edit operations in a text editor.

`uncombine-files` takes the combined file and writes out the individual files.

```bash
combine-files one two > combined
# (edit combined)
uncombine-files < combined
```
