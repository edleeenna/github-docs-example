# Writing Good Documentation
Github docs example - Terraform Bootcamp prep

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')

```
print("Hello, World!")
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```python
print("Hello, World!")
```
- Make note of where the backtick buttong is located.
- It should appear above the tab key
- It may vary based on your keyboard layout.

![Backtick key](https://github.com/edleeenna/github-docs-example/assets/19589499/3475492f-c3fe-4a1b-bc9c-3ca04e6e5731)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  File "example.py", line 2, in <module>
    print(variable_does_not_exist)
NameError: name 'variable_does_not_exist' is not defined
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis
Github flaboured Markdown (GFM) supports
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` |:cloud:|
| Cloud | `:cloud_with_lightning` |:cloud_with_lightning:|

## Step 5 - How to create a table

You can use the following markdown formate to create tables:

```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` |:cloud:|
| Cloud | `:cloud_with_lightning` |:cloud_with_lightning:|
```

Github extends the functionalist of Markdown tables to provide more alignment and table cell formatting options [<sup>[2]</sup>](#references)

## References
- [Github Flavored Markdown Spec](https://github.github.com/gfm/)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists) <sup>[1]</sup>
- [GTM - Emjoi CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM -Tables (with Extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
