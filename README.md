# Awesome-Readme_Markup

## Table of Contents
1. [Headers](#Headers)
3. [Text Selection](#selection)
4. [Lists](#Lists)
	1. [Numbered list](#numbered)
	2. [Bulleted list](#bulleted)
	3. [Task list](#Task)
	4. [Dropdown list](#Dropdown)
6. [Links](#Links)
7. [Badges](#Badges)
8. [Buy me a coffe](#coffe)
9. [Images](#Images)
10. [Gif](#Gif)
11. [Tables](#Tables)
12. [Quotes](#Quotes)
13. [Footnote](#Footnote)
14. [Code Blocks](#Code)
15. [Ignore Markdown Formatting](#Ignore)
16. [Emoji](#Emoji)
17. [GitHub stats](#stats)
18. [Markdown Editors](#Editor)
19. [Others resources](#Resources)

# <a name="Headers">Headers</a> 

# <a name="H1">H1</a> 

```
# H1
```

## <a name="H2">H2</a> 

```
## H2
```

### <a name="H3">H3</a> 

```
### H3
```

#### <a name="H4">H4</a> 

```
#### H4
```

##### <a name="H5">H5</a> 

```
##### H5
```

###### <a name="H6">H6</a> 

```
###### H6
```

H1
=

```
H1
=
```

H2
-

```
H2
-
```

# <a name="selection">Text selection</a> 

asterisk *italic*

```
*italic*
```

underline sign _italic_

```
_italic_
```

asterisk **bold**

```
**bold**
```

underline sign __bold__

```
__bold__
```

*italic and __bold__*

```
*italic and __bold__*
```

~~crossed out text~~

```
~~crossed out text~~
```

`code highlight`

```
`code highlight`
```

This is <sub>subscript!</sub>

```
This is <sub>subscript!</sub>
```

This is <sup>superscript!</sup>

```
This is <sup>superscript!</sup>
```

# <a name="Lists">Lists</a> 
<a name="numbered">numbered list:</a> 
1. one
2. two

   indentations
3. three

```
numbered list:
1. one
2. two
[space][space][space]indentations
3. three
```

multilevel numbered list:
1. level 1
    1. level 2
2. level 1
    1. level 2
    2. level 2
    	1. level 3

```
multilevel numbered list:
1. level 1
[4 spaces]1. level 2
2. level 1
[4 spaces]1. level 2
[4 spaces]2. level 2
[8 spaces]1. level 3
```

<a name="bulleted">bulleted list:</a> 
+ one
- two
* three

```
bulleted list:
+ one
- two
* three
```

multilevel bulleted list:
- level 1
    - level 2
- level 1
    - level 2
    - level 2
    	- level 3

```
multilevel bulleted list:
- level 1
[4 spaces]- level 2
- level 1
[4 spaces]- level 2
[4 spaces]- level 2
[8 spaces]- level 3
```

<a name="Task">Task list:</a>
- [ ] todo 1
- [x] todo 2
- [x] todo 3
- [ ] todo 4
	- [ ] todo 4.1
	- [ ] todo 4.2
```
Task list:
- [ ] todo 1
- [x] todo 2
- [x] todo 3
- [ ] todo 4
	- [ ] todo 4.1
	- [ ] todo 4.2
```

<a name="Dropdown">Dropdown list</a>

<details open>
<summary>language</summary>
Java<br>
C++<br>
C#
</details>

```
<details open>
<summary>language</summary>
Java<br>
C++<br>
C#
</details>
```

<details>
<summary>language</summary>
<ul>
<li>Java</li>
<li>C#</li>
<li>C++</li>
</ul>
</details>

```
<details>
<summary>language</summary>
<ul>
<li>Java</li>
<li>C#</li>
<li>C++</li>
</ul>
</details>
```

```python
print('Hello world!')
```

<details>
<summary>Show markdown</summary>
```python<br>
print('Hello world!')
```
</details>

# <a name="Links">Links</a>

[Link to GitHub](https://github.com/)

```
[Link to GitHub](https://github.com/)
```

[Link to GitHub with title](https://github.com/ "GitHub")

```
[Link to GitHub with title](https://github.com/ "GitHub")
```

[Reference to a repository file](../file)

```
[Reference to a repository file](../file)
```

<https://github.com>

```
<https://github.com>
```

<example@example.com>

```
<example@example.com>
```

**[Link to GitHub](https://github.com)**

```
**[Link to GitHub](https://github.com)**
```

*[Link to GitHub](https://github.com)*

```
*[Link to GitHub](https://github.com)*
```

# <a name="Images">Images</a>

![GitHub](https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png)

```
![GitHub](https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png)
```

[![GitHub](https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png)](https://github.com/)

```
[![GitHub](https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png)](https://github.com/)
```

![alt text][logo]

[logo]:https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png

```
![alt text][logo]

[logo]:https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png
```

<img src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png" height="100" />

```
<img src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png" height="100" />
```

### Left align

<img align="left" width="100" height="100" src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png">

```
<img align="left" width="100" height="100" src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png">
```
<br><br>
### Rigth align

<img align="right" width="100" height="100" src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png">

```
<img align="right" width="100" height="100" src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png">
```

### Center align

<p align="center">
<img width="100" height="100" src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png">
</p>

```
<p align="center">
<img width="100" height="100" src="https://cdn0.iconfinder.com/data/icons/social-network-9/50/29-512.png">
</p>
```

# <a name="Gif">Gif</a>

![Gif](https://giffiles.alphacoders.com/398/3987.gif)

```
![Gif](https://giffiles.alphacoders.com/398/3987.gif)
```

If you want **add video into readme** you can [convert](https://gist.github.com/harunawaizumi/958f4a613f626dbd22f7840245cdd1cf) him to gif format.

# <a name="Badges">Badges</a>

[![Build][awesome-image]][awesome-url]

[awesome-url]: https://github.com/redduxi/Awesome-Readme-Markdown/
[awesome-image]: https://p.kindpng.com/picc/s/736-7368452_grunge-awesome-label-psd-graphic-design-hd-png.png

```
[![Build][awesome-image]][awesome-url]

[awesome-url]: https://github.com/redduxi/Awesome-Readme-Markdown/
[awesome-image]: https://p.kindpng.com/picc/s/736-7368452_grunge-awesome-label-psd-graphic-design-hd-png.png
```

[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://github.com/redduxi/Awesome-Readme-Markdown/)

```
[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://github.com/redduxi/Awesome-Readme-Markdown/)
```

:dizzy: [See other budges](https://shields.io/)
:dizzy: [Version Badge](https://badge.fury.io/)

# <a name="coffe">Buy me a coffe</a>

[Buy me a coffe](https://github.com/appcraftstudio/buymeacoffee)


# <a name="Tables">Tables</a>

|        LEFT       |      CENTER      |       RIGHT      |
|:------------------|:----------------:|----------------: |
|  ................ | ................ | ................ |

```

|        LEFT       |      CENTER      |       RIGHT      |
|:------------------|:----------------:|----------------: |
|  ................ | ................ | ................ |
```

italic | bold
---    | ---
*text* | **text**

```
italic | bold
---    | ---
*text* | **text**
```

[HTML table syntax into Markdown](https://jmalarcon.github.io/markdowntables/)

[Tables Generator](https://www.tablesgenerator.com/markdown_tables)

# <a name="Quotes">Quotes</a>
> Lorem Ipsum is simply dummy text of the printing and typesetting industry.
> 
```
> Lorem Ipsum is simply dummy text of the printing and typesetting industry.
```

> > Lorem Ipsum is simply dummy text of the printing and typesetting industry.

```
> > Lorem Ipsum is simply dummy text of the printing and typesetting industry.
```

> Lorem Ipsum is simply dummy text of the printing and typesetting industry.
>
> Lorem Ipsum is simply dummy text of the printing and typesetting industry.

```
> Lorem Ipsum is simply dummy text of the printing and typesetting industry.
>
> Lorem Ipsum is simply dummy text of the printing and typesetting industry.
```

> ### Lorem Ipsum
>
> - What is Lorem Ipsum?
>
> 	Lorem Ipsum is simply dummy text of the printing and typesetting industry.
> - Why do we use it?
> 	
> 	 Used to fill pages and test the appearance of layouts

```
> ### Lorem Ipsum
>
> - What is Lorem Ipsum?
>
> 	Lorem Ipsum is simply dummy text of the printing and typesetting industry.
> - Why do we use it?
> 	
> 	 Used to fill pages and test the appearance of layouts
```
# <a name="Footnote">Footnote</a>

Footnote<sup>1</sup>

Footnote<sup>2</sup>

```
Footnote<sup>1</sup>

Footnote<sup>2</sup>
```

Lorem Ipsum <sup id="lorem">[1](#Footnote1)</sup>

<b id="Footnote1">1</b> Lorem Ipsum is simply dummy text of the printing and typesetting industry. [↩](#lorem)

```
Lorem Ipsum <sup id="lorem">[1](#Footnote1)</sup>
<b id="Footnote1">1</b> Lorem Ipsum is simply dummy text of the printing and typesetting industry. [↩](#lorem)
```

# <a name="Code">Code Blocks</a>

```c++
 #include <iostream> 
 ///
 int main(){///}
```

```
```c++
#include <iostream> 
///
int main(){///}
```(used without brackets)
```
# <a name="Ignore">Ignore Markdown formatting</a>

Lorem Ipsum is simply \*dummy\* text of the printing and \*typesetting industry\*.

```
Lorem Ipsum is simply \*dummy\* text of the printing and \*typesetting industry\*.
```

# <a name="Emoji">Emoji</a>
:smile: I use emoji

:dizzy: [Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908)

# <a name="stats">GitHub stats</a>
<img src="https://github-readme-stats.vercel.app/api?username=redduxi&show_owner=true&show_icons=true&theme=dark">

```
<img src="https://github-readme-stats.vercel.app/api?username=redduxi&show_owner=true&show_icons=true&theme=dark">
```

:dizzy: [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats#github-stats-card) 
##### Includes:
- GitHub Stats Card
- GitHub Extra Pins
- Top Languages Card
- Wakatime Week Stats
- Themes
- Customization

# <a name="Editor">Markdown Editors</a>

- [Markdown editor](https://jbt.github.io/markdown-editor/)
- [Bywor‪d‬](https://bywordapp.com/)
- [Ulysse‪s‬](https://ulysses.app/)
- [MacDown](https://macdown.uranusjr.com/)
- [Caret](https://chrome.google.com/webstore/detail/caret/fljalecfjciodhpcledpamjachpmelml?hl=ru)
- [Typora](https://typora.io/)
- [Haroopad](http://pad.haroopress.com/)
- [HackMD](https://hackmd.io/)
- [StackEdit](https://stackedit.io/)
- [Dillinger](https://dillinger.io/)

# <a name="Resources">Other resources</a>

- [Awesome README](https://github.com/matiassingers/awesome-readme)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

:wink: :revolving_hearts:
