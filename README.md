# Note Taking Theme

**Typora NEEDED** This contains a simple theme to help aid in taking notes.

## What is Typora and How do I download

Read it yourself [here](https://typora.io/)

## What it contains

- Auto header numbering (with the exception of h1, h2 and h6)
- Additional CSS that aids in note taking 
  - Intentional page break when printing
  - Highlight in various colours
  - Change sizes of pictures
- And everything that Typora provides

## How to download this theme

- Just download from the "Clone or download" button
- Use `git clone ` followed by the link that can be obtained from the "Clone or download" button

## How do I use this theme

### Add the theme to the themes folder

Once downloaded you can add it to the themes folder, read [here](http://support.typora.io/About-Themes/) if you need more help

### How to use additional codes

These are all in html as there is no other way, pick it up it's easy

#### Intentional page break when printing

```html
<div class="page-break"></div>
```

Just paste at the place you want the page to break

#### Highlight in various colours

```html
<span class="highlight green-highlight">Content</span>
```

There are 3 colours

1. Green  ( `green-highlight` )
2. Blue ( `blue-highlight` )
3. Orange ( `orange-highlight` )

#### Change sizes of pictures

There's 2 different ways to do this

##### Part HTML

It seems to work in tables but not in the normal writing mode. No idea why don't ask me.

```html
<div class="picture50"></div>
```

##### Full HTML

As I said above there is are times when it is not possible to achieve with part HTML thus this is the alternative

These are the steps to follow

1. You will usually see this `![Screenshot](assets/Screenshot.png)` when you drag an image into Typora
2. Copy everything in the brackets and paste it into the `src` part of the code below

```html
<div class="picture60"><img src="assets/Screenshot.png"/></div>
```

There are other sizes

1. 50% ( `picture50` )
2. 60% ( `picture60` )
3. 70% ( `picture70` )
4. 80% ( `picture80` )

Adding `center` to it will center the image when printing (doesn't show in real-time)

```html
<div class="picture60 center"><img src="assets/Screenshot.png"/></div>
```

# Final words

Using this to take notes is easy, printing the notes may take some try and error here and there.

All the best for your work or school (since you are using this) (\*•̀ᴗ•́\*)و ̑̑

