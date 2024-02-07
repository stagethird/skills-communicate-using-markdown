# First steps of _Markdown_ lesson

This `index.md` file is a lesson in markdown file features.

> Note that i'm not sure that I will learn anything from this,
> but here goes.

* This is the first commit.

## Second step of _Markdown_ lesson

* Add an image 🎉

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

## Third step - Code sample samples
#### Python:

``` python
if len(line.split()) > 2:
```
#### C:

``` c
if ((argc == 1) || (tempChar == '?')) // help info if '?' or no arg.
{	
  printf("\n%s accepts multiple input numbers and \n", argv[0]);
  printf("returns the total parallel resistance. i.e. :\n");
  printf("\n%s 10 20 30\n\nTotal resistance = 5.45455 Ohms\n\n", argv[0]);
  printf("Note that (for example) '20000000' can be expressed as '20M'.\n");
}
else // do the math
```
#### bash:

``` bash
if [ $# -eq 0 ]; then # if number of command line args = 0
  read -p "Machine to backup? " machine
else
  machine=$1
fi
```
## Fourth step of _Markdown_ lesson
#### Checklists!
- [x] Finish step 4 of Markdown lesson.
- [ ] Merge branch?
- [ ] Finish lesson.
- [ ] Profit!

* Note that the checkboxes are __not__ interactive 😢

## Trying some additional tricks

1. Add a hyperlink to the published HTML version of this document on
[GitHub pages](https://stagethird.github.io/skills-communicate-using-markdown/)
2. Add a link from the HTML version to the project main page. 
[Markdown project](https://github.com/stagethird/skills-communicate-using-markdown)
3. Collapsed Text
<details>

<summary>Click here to see details!</summary>

### You can add a header

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

More details can be found here:
[Github Docs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections)
</details>
