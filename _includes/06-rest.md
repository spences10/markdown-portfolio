## Here's where the other cool Markdown stuff goes

<details>
  <summary>Quotes</summary>

### Quotes

You can create quote text with a `>`.

    ```text
    In the words of Ken Wheeler:

    > “as developers almost everything we do is building elaborate lists
    > of shit”
    ```

In the words of Ken Wheeler:

> “as developers almost everything we do is building elaborate lists
> of shit”

  <hr>
</details>

<details>
  <summary>Tables</summary>

### Tables

You can create tables by assembling a list of words and dividing them
with hyphens `-` (for the first row), and then separating each column
with a pipe `|`:

    ```text
    | First Header                | Second Header                |
    | --------------------------- | ---------------------------- |
    | Content from cell 1         | Content from cell 2          |
    | Content in the first column | Content in the second column |
    ```

| First Header                | Second Header                |
| --------------------------- | ---------------------------- |
| Content from cell 1         | Content from cell 2          |
| Content in the first column | Content in the second column |

For more detail on formatting with tables, see "Organizing information
with tables" in the _GitHub Help_.

<hr>
</details>

<details>
  <summary>Inline Code Blocks</summary>

### Inline Code Blocks

Certain words and phrases need to be formatted in monospace fonts,
especially when writing about code. As you've seen throughout this
lab, words can be distinguished in markdown with `inline code blocks`.

Inline code is just one ``` character on either side of the text, and
can be used within paragraphs, headers, or other Markdown.

    ```
    `inline code is just one backtick`
    ```

`inline code is just one backtick`

  <hr>
</details>

<details>
  <summary>Separate Code Blocks</summary>

### Separate Code Blocks

To separate out a larger block of code, use three ``` characters
instead of one, and set the text aside in its own paragraph.

What we type:

    ```
    Anything written in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
    ```

What we see:

```
Anything written in this **paragraph** will not be _formatted_ even if it would normally be recognized in this setting. :taco:
```

<hr>
</details>

<details>
  <summary>Syntax Highlighting</summary>

### Syntax Highlighting

In addition to code blocks, some code blocks should be rendered
differently depending on the language, such as Javascript or
command-line text.

What we type:

    ```sh
    github-learning-lab ~/Projects/recipe-repository
    $ git init
    Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
    ```

What we see:

```sh
github-learning-lab ~/Projects/recipe-repository
$ git init
Initialized empty Git repository in /Users/github-learning-lab/Projects/recipe-repository/.git/
```

  <hr>
</details>

<details>
  <summary>Summary dropdown</summary>

### Summary dropdown

Most of the text in this issue is formatted in collapsible summary
blocks. Here's how to make them with Markdown:

    ```
    <details>
      <summary>Title</summary>

      Content here

    </details>
    ```

  <hr>
</details>
