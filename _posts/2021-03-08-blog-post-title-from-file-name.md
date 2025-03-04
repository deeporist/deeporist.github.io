## This is the first line of the source file and served as the title

Due to a plugin called [`jekyll-titles-from-headings`](https://github.com/benbalter/jekyll-titles-from-headings) which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

>If you have a Jekyll page that doesn't have a title specified in the YAML Front Matter, but the first non-whitespace line in the page is a Markdown H1 / H2 / H3, this plugin instructs Jekyll to use that first heading as the page's title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post. You can talk about all sorts of fun (~~or not fun~~) things here.

---

### Code Sample

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
