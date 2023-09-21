# Github Docs Example

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create Codeblocks in markdown you need to use three backtics
- Not to be confused with single quotes.
```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
```

- Good Cloud Engineers use Codeblocks for both code and errors that appear in the console.

```bash
Error: division by zero
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[2]</sup>

- [x] Finish Setup 1
- [ ] Finish Setup 2
- [ ] Finish Setup 3

##Use Emojis (Optional)

Github Flavoured Markdown supports emoji shortcodes. <sup>[3]</sup>

Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud With Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |

# Step 5 - How to Create a Table

You can use the following markdown to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud With Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[4]</sup>](#references)

## References

- [Github Flavoured Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[2]</sup>
- [GTM Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet) <sup>[3]</sup>
- [GFM - Tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) <sup>[4]</sup>


