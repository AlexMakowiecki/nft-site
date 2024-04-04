# NFT side
## What is it? 
It's a website that displays information about the NFTs. It's a website only to practice CSS
It's also the ninth project, part of the Scrimba Course, that I've uploaded to Github. This project is part of module 4, where they teach you CSS essential concepts.
## What did I use?
I used HTML, CSS and a couple of images
## Concepts learned for this project and practiced during it
- **Semantic HTML:** how to use new tags to organize your document correctly
  - ```HTML
    <body>
      <header> Here is where the logo, page title, navigation bar of the page, all the things that will be shared between others pages for the same domain are written. </header>
      <main>  Here is where the main content, the unique content of this page, is written. 
        <section>
          Used to group content that has information related to each other.
        </section>
        <section>
          Used to group content that has information related to each other.
        </section>
      </main>
      <footer>
        Here is where the information that normally is in a footer is written
      </footer>
    </body>
    ```
- **CSS Pseudo selectors** to change styles of elements when an event occurs.
  - `:hover` `:active` `:visited` and `:focus` for `hover` but with keyboard
- **CSS specificity** to know which selector is going to override or be overridden. 
  - __more points = more specificity__
  - element: 1 points
  - class: 10 points
  - id: 100 points
- **Compound Selectors:** in this case to select items inside other
  - ```CSS
    parent child{
      color: blue;
    }
    ```
- **display: inline-block** to open the use of properties of display:block but without taking all the line. 
- Use multiple classes in one element to have a better organization in CSS
- Use `<a>` tags to redirect to other parts of the page, or other websites, and `<button>` for website functionality
- **Float** CSS property for ONLY adapting big elements to text.
- **Display: flow-root** To prevent float elements from overflowing the container. 
## Preview 
<img style="text-align:center" src="https://github.com/AlexMakowiecki/nft-site/assets/122258496/2cde9755-0fd6-47a4-964e-aa793892ac33" width="500"/> 

## About Scrimba!


At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!
