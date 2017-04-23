# PyColor

## Description:

PyColor is a Python library for working with html and css color code in Python with ease. User can define a color name, the corresponding RGB hexcode srting and RGBA and RGB tuples will be resolved from a wide collection of built in colors.

User can also specify the custom color code for custom user defined colors by using either RGB hexcode string or tuple containing RGB hexcode value (R,G,B) or RGBA hexcode value (R,G,B,A). RGBA format is needed when user wants to add transparency with the color. The transparency value is a floating point and must be within the range 0.0 to 1.0 where 0.0 defines fully opaque and 1.0 defines fully transparent color.

## Example:

`RedColor = PyColor("Red")` <br />
`print(RedColor.name)             # will display 'Red'` <br />
`print(RedColor.rgb_hex_string)   # will display #FF0000` <br />
`print(RedColor.rgb_hex_tuple)    # will display (255,0,0)` <br />
`print(RedColor.rgba_hex_tuple)   # will display (255,0,0,0.0)` <br />
<br />
`# Update the color` <br />
`RedColor.update_color('Blue', 1.0)` <br />
`print(RedColor.name)             # will display 'Blue'` <br />
`print(RedColor.rgb_hex_string)   # will display #0000FF` <br />
`print(RedColor.rgb_hex_tuple)    # will display (0,0,255)` <br />
`print(RedColor.rgba_hex_tuple)   # will display (0,0,255,1.0)` <br />
<br />






























## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/farshad112/PyColor/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/farshad112/PyColor/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
