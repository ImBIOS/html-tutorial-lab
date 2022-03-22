# HTML File Paths

## Examples

```html
<!-- The "picture.jpg" file is located in the same folder as the current page -->
<img src="picture.jpg" />
<!-- The "picture.jpg" file is located in the images folder in the current folder -->
<img src="images/picture.jpg" />
<!-- The "picture.jpg" file is located in the images folder at the root of the current web -->
<img src="/images/picture.jpg" />
<!-- The "picture.jpg" file is located in the folder one level up from the current folder -->
<img src="../picture.jpg" />
```

## Best Practice

It is best practice to use relative file paths (if possible).

When using relative file paths, your web pages will not be bound to your current base URL. All links will work on your own computer (localhost) as well as on your current public domain and your future public domains. (source: w3schools)

## Good Reference

- https://www.w3schools.com/html/tryit.asp?filename=tryhtml_files_relative

- https://www.w3schools.com/html/tryit.asp?filename=tryhtml_files_relative_1

- https://www.w3schools.com/html/tryit.asp?filename=tryhtml_files_relative_2
