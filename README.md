# Order summary card

> 🔖 This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## 🌈 ✨ 🎉 Have Fun Building! 🚀 🎊 🎈
> 🖥️ **Welcome** <br>
> Thanks for checking out this front-end coding challenge.
[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.
***To do this challenge, you need a basic understanding of HTML and CSS.*** Press <kbd>Enter</kbd> 🚀 to start the game!!

## 📍Table of Contents
- [Brief](#brief)
	- [The challenge](#the-challenge)
	- [Links](#links)
- [My process](#my-process)
	- [Built with](#built-with)
	- [What I learned](#what-i-learned-)
	- [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Brief
Your challenge is to build out this **order summary card component** and get it looking as close to the design as possible. You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

**Preview** :eyeglasses:

![Design preview for the Order summary card coding challenge](./design/desktop-preview.jpg)

### The challenge
Users should be able to:

| Challenge | Newbie | Junior | Intermediate | Advanced |
| --- | :---: | :---: | :---: | :---: |
| See hover states for interactive elements | ⭕ |  |  |  |

### Links
- Solution URL: [Add solution URL here]()
- Live Site URL: Add live site URL here

## My process
> ⏱️ My estimate time for this challenge is 2 days
### Built with
- VSCode
- HTML
- Sass

### What I learned 🥳
I Learnt how to center a `<button>`, so the trick is you wrap the button with 'element wrapper' like `<div>` next in the wrapper element we can use `grid` to center it. So Easy I love it!
###### stylesheets/scss/components/\_card.scss
```scss
  .wrap-cancel {
  display: grid;
  place-items: center;
  .cancel {
    text-align: center;
    color: $desaturated-blue;
    font-weight: map-get($font-weights, bold);
    text-decoration: none;
    &:hover {
    color: $dark-blue;
    }
  }
}
```

### Continued development
- [ ] Mobile First
- [ ] Make text for 'Annual Plan' **Bold**

## Author
| [<img src="https://avatars.githubusercontent.com/u/47988956?v=4" alt="xvferdy" width="100px"/>](https://github.com/xvferdy) </br> [🌍](https://berlianto.netlify.app/) |
|:---:| 
| Berlianto | 
| [<samp>Frontend Mentor<samp>](https://www.frontendmentor.io/profile/xvferdy) | 

## Acknowledgments
- [Copy paste Tailwind's `box-shadow`](https://tailwindcss.com/ "Tailwind")

<h3 align="right">
      <a href="#order-summary-card">To Top ⤴️</a>
</h3>
