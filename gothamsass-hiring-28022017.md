---
title: Patterns for Hiring
revealOptions:
    transition: 'slide'
---

# Patterns for Hiring Leads & Candidates

Claudina Sarahe, @itsmisscs

Note: Important for both hiring managers and for us as developers and workers. In short,this is an area where I think everyone should be involved and care because it is a pivotal backbone to the culture and environment. We spend so much of our lives at work. Processes...institutions.

---

# v much not an expert

Note: these experiences from few years hiring at high growth startup
coupled with learnings from organizing and colleagues.

---

# Roundtable and Chat

Take a 10-15 minute break after the talk

Note: Do something different. Challenge us here as we gather. Keep your questions and jot them down. Break. Drinks. Food. Circle up chairs. Discussion / QA.

---

# Outline

* Global: Hiring leads + team <!-- .element: class="fragment" data-fragment-index="1" -->
* Candidate level <!-- .element: class="fragment" data-fragment-index="2" -->
* Hiring leads <!-- .element: class="fragment" data-fragment-index="3" -->

---

## Sustaining inclusive and diverse teams begin with inclusive processes within

Note: You are what you eat adage holds true. I believe that an
in order to have an enjoyable hiring that yields diverse, inclusive, creative,productive teams you must

----

## Bring the team into the process

### Be open and participatory

Note: If you have a hiring process or are putting in a more formal one, start by inviting those that want to be a part of it

----

## Form hiring teams/committees

### Share the process back to the whole team

----

## Establish core tenets

What qualities do you most value in a code and in a candidate?

* Simplicity <!-- .element: class="fragment" data-fragment-index="1" -->
* Consistency <!-- .element: class="fragment" data-fragment-index="2" -->

Note: Set these up early. Invite the whole team to be a part of it. Core tenets can function both as code and person

----

## Framework agnostic
### Tenet: Simplicity

Core languages of our craft: JS, CSS, HTML

Note: We valued JS, CSS, HTML. I stand that a good developer can and will know everything. Specialist are necessary. If you need a specialist, then test for that specialization.

----

## Establish guidelines for the role

Sets expectations for the candidate and your team

* What are some of the tasks this person will be doing? <!-- .element: class="fragment" data-fragment-index="1" -->
* Are you hiring for a specific project? What happens after it ends? <!-- .element: class="fragment" data-fragment-index="2" -->
* Are you filling a specific need? <!-- .element: class="fragment" data-fragment-index="3" -->

Note: Doing this may help you realize you need to define current team roles and responsibilities

----

## Establish guidelines for your process

* What are the steps in the process? (Phone screen, code, in person)<!-- .element: class="fragment" data-fragment-index="1" -->
* Whose going to participate in each step? Are the positions fixed?<!-- .element: class="fragment" data-fragment-index="2" -->
* What tools are we going to use? (Greenhouse)<!-- .element: class="fragment" data-fragment-index="3" -->
* How are we going to control against bias?<!-- .element: class="fragment" data-fragment-index="4" -->

Note: Key is that everyone is aware of process. Hiring is a huge load. Spread it as much as possible.

---

# First touch matters

Note: For us, phone Put someone the phone that cares, will listen, make conversation, and is invested in learning about that person.

---

## Become friends with talent team

Note: You need to collaborate. If you don't want to be on the phone, help them screen candidates by providing questions they can ask. Greenhouse for notes.

----

## Candidate interview profile

Note: Not everyone interviews well. This can either come directly via form sent to candidates or through references. Some ideas

----

## Questions for candidate profile

* Do you prefer morning or afternoon interviews?<!-- .element: class="fragment" data-fragment-index="1" -->
* Would you prefer in person or remote for your first conversation?<!-- .element: class="fragment" data-fragment-index="2" -->
* Do you have any needs we can assist with, such as an energy so to minimize walking?<!-- .element: class="fragment" data-fragment-index="3" -->

----


## What's your Preferred Gender Pronoun (PGP)?

<img src="images/pronounis.png">


---


# Be real about right fit later

Note: So many people I wanted to hire but needed to wait until there was stability. Be sincere about this by working with TS to keep in touch. As canddiate, if you really liked it, follow up, even if you do get a job. If no movement after 6 months, tell candidate.

---

## Provide Feedback. Get Feedback.

Note: Hiring leads you must be willing to provide feedback so TS send out. Be prepared to offer. Call candidates you personally connected with. Candidates, ask for feedback. What's one things I could improve on my test? If tenets, feedback becomes really easy to give.

---

# Thoughts for Candidates

----

## Define your tenets
### What do you want out of the position?

Note: What do you want to get out of the job? clear: room to grow, better process; for a new dev could be get a job on respectful teams

----

## Ask about day to day

* What's the process for a typical feature or sprint?<!-- .element: class="fragment" data-fragment-index="1" -->
* How do you spend your day?<!-- .element: class="fragment" data-fragment-index="2" -->
* What does a typical day for team member look like?<!-- .element: class="fragment" data-fragment-index="3" -->

Note: Ask about someone at your level and also ask above is you are looking to grow

----

## Care about your growth
### Ask about mentorship and career growth

----

* Pairing <!-- .element: class="fragment" data-fragment-index="1" -->
* Code review process <!-- .element: class="fragment" data-fragment-index="2" -->
* How are code decisions and standards formed? <!-- .element: class="fragment" data-fragment-index="3" -->
* Learning budget—encouraged to learn<!-- .element: class="fragment" data-fragment-index="4" -->
* Developer ratio (Junior to Senior)<!-- .element: class="fragment" data-fragment-index="5" -->
* Tech stack<!-- .element: class="fragment" data-fragment-index="6" -->

Note: A job for jobs sake will not help you. Signs to look for.

---

## Preparing for code challenge

Note: All in the details. Areas. Pitfalls to pay attention to

---

## Documentation
### Does your project include a `README.md`?

Note: how detailed does it get. if you do something different, note it. documentation helps people.

----

## Code documentation


JSDOC style syntax across all file types

<img src="images/jsdoc.png">

---

# Directory Organization

Note: Lots of patterns here. Here's good vs signs of lack of organization

----

## Common patterns

Within the root folder:

* Core code files: `src/` or `app/` <!-- .element: class="fragment" data-fragment-index="1" -->
* Compiled files: `dist`, `public/`, `build/` <!-- .element: class="fragment" data-fragment-index="2" -->

----

### Example: Good Directory Structure

```
app
├── js
│   │── vendor/
│   │   ├── jquery.js
│   └── main.js
├── css
│   └── main.css
├── views
│   └── index.html
├──
dist
├── // compiled assets

```

---

# Code Consistency

* Spacing <!-- .element: class="fragment" data-fragment-index="1" -->
* Indentation<!-- .element: class="fragment" data-fragment-index="2" -->
* Stale code (e.g. commented out)<!-- .element: class="fragment" data-fragment-index="3" -->

----

# CSS Linters & Style Guides

----

### Harry Roberts, CSS Guidelines

<img src="images/cssguidelines.png">

----

## Hugu G, Sass Guidelines

<img src="images/sassguidelines.png">

----

## MDO, Code Guide

<img src="images/mdo.png">

----

## Stylelint

<img src="images/stylelint.png">

----

## csscomb

<img src="images/csscomb.png">

----

## Other CSS/Sass Linters

* [Sass-lint](https://github.com/sasstools/sass-lint)
* [SCSS Lint](https://github.com/brigade/scss-lint)

----

## JS Linters

* Plugins available for most editors

----

## ESLint

<img src="images/eslint.png">

Note: Pluggable different standards

----

## AirBnb Code Standards

<img src="images/airbnbstyles.png">

----

## Lots of standards

* [JS Standard](https://github.com/feross/standard)
* [Google](https://github.com/google/eslint-config-google)

----

# Naming

* Clear, concise, patterns <!-- .element: class="fragment" data-fragment-index="1" -->
* Remix from other frameworks <!-- .element: class="fragment" data-fragment-index="2" -->

Note: Check out semantic UI or frameworks for ideas. visit sites you like.

---

## Command & Understanding of HTML

* Are you using more semantically appropriate element? <!-- .element: class="fragment" data-fragment-index="1" -->
* Is accessibility a fore or afterthought? <!-- .element: class="fragment" data-fragment-index="2" -->

----

## Know your tags

```
<div class="price">
  ${{ price }}
</div>
```

----

## Answer: Daily Double

```
<output for="price-field" name="price" class="price">
  ${{ price }}
</output>
```

Represents the result of a calculation or user action.

Note: Okay. Esoteric. But this isn't..

----

```
<div class="btn">
  Get it
</div>
```

## `<div>` is not `<button>`

----

## HTML is more than divs

```html
<div class='item'>
  <div class='item__name'>
    {{ name }}
  </div>
  <div class='item_description'>
    {{ description }}
  </div>
  <div class='item_price'>
    {{ price }}
  </div>
  <div class='item__purchase' data-name='{{ name }}' data-price='{{ price }}'>
    <div class='btn'>
      Get it
    </div>
  </div>
</div>
```

----

```html
<article class='item'>
  <h2 class='item__name'>
    {{ name }}
  </h2>
  <p class='item_description'>
    {{ description }}
  </p>
  <output for="price-field" name="price" class="price">
    ${{ price }}
  </output>
  <div class='item__purchase' data-name='{{ name }}' data-price='{{ price }}'>
    <button class='btn'>
      Get it
    </button>
  </div>
</article>
```

----

# CSS

* Understanding of specificity <!-- .element: class="fragment" data-fragment-index="1" -->
* CSS Architecture<!-- .element: class="fragment" data-fragment-index="2" -->
* Organization<!-- .element: class="fragment" data-fragment-index="3" -->
* Style<!-- .element: class="fragment" data-fragment-index="4" -->

----

## Over-qualifying elements

```
button.delete {

}
```

----

## Empty Rule Sets

```
.price {
}
```

----

## Unit consistency or pattern

```
.sidebar {
  margin-left: 3%;
  padding: 1.5em 40px;
}
```

----

## CSS Architecture

* SMACSS <!-- .element: class="fragment" data-fragment-index="1" -->
* BEM <!-- .element: class="fragment" data-fragment-index="2" -->
* CSS Modules <!-- .element: class="fragment" data-fragment-index="3" -->
* ITCSS <!-- .element: class="fragment" data-fragment-index="4" -->
* ExpressiveCSS <!-- .element: class="fragment" data-fragment-index="5" -->
* FunctionalCSS <!-- .element: class="fragment" data-fragment-index="6" -->

Note: some are more about styles and less prescriptive about organization. others are more coupled.

----

## Solve problem at hand first
### before adding complexity

----

## Setup your own simple build process

* Process your CSS <!-- .element: class="fragment" data-fragment-index="1" -->
* Transpile your JavaScripts <!-- .element: class="fragment" data-fragment-index="2" -->
* Compile your HTML Templates <!-- .element: class="fragment" data-fragment-index="3" -->

----

# Gulp.js for making builds

* Easy to grok <!-- .element: class="fragment" data-fragment-index="1" -->
* Lots of tutorials and good content <!-- .element: class="fragment" data-fragment-index="2" -->
* More intuitive working with HTML templates <!-- .element: class="fragment" data-fragment-index="3" -->

----

### But isn't Webpack the thing?!?!

Note: If react job or JS heavy, sure. Any of the followign can work in either

----

## Autoprefixer for vendor prefixing

```css
@mixin box-sizing( $type: border-box ) {
    -webkit-box-sizing: $type;
       -moz-box-sizing: $type;
         -o-box-sizing: $type;
        -ms-box-sizing: $type;
            box-sizing: $type;
}

*,
*::before,
*::after {
  @include box-sizing(border-box);
}
```

Note: If you are using a build process, this is must @EXTRA Webpack way vs gulp way.

----

```css
@mixin box-sizing( $type: border-box ) {
  box-sizing: $type;
}

*,
*::before,
*::after {
  @include box-sizing(border-box);
}
```

----


## Avoid coupling HTML + JS

```
$(".cart .count").html(count);
$(".cart .total").html(total);
```

Note: Going to refactor.... better

----

## Use JS Selectors

```
$(".js-cart .js-count").html(count);
$(".js-cart__count").html(count);
```

----

# Add linters to your code editors

----

# Keep up with the Industry

Note: Scientiest doesn't keep up with research in their field. They will become obsolete

----

## Find your method

* Digest Lists & Newsletter
* Podcasts
* Meetups
* Conferences
* Twitter accounts and lists
* Slack groups
* Medium

Note: Volunteer at conferences.

----

## Hack the industry pulse

* Bleeding edge. Hottest. (0-18 months)
* Best practices (3+ years)
* What’s on the mind of the community?

----

## Test your code before submitting
### Dreaded `-g`

* Wipe your node modules
* Re-install node version
* Ask a friend to try out

----

## Manage node

* nvmrc
* n

---

## Give credit were it is due
### We all copy pasta

Note: Include license files or mentions in code comments. Add mention in your
readme. This also shows that you keep up.

---

## Does it work?

### Depends ;)


Note: Seniors (must work)  and mid-levels. recap should flag it. hopefully discussed in the interview

---

## Thoughts for Hiring Leads

----

## Drive & Passion
### Look for this quality

----

* Why are you looking to leave your current position? <!-- .element: class="fragment" data-fragment-index="1" -->
* What do you like to do when you aren’t coding (and the answer can be coding)<!-- .element: class="fragment" data-fragment-index="2" -->
* Tell me about a project or moment you were most proud of in the last year<!-- .element: class="fragment" data-fragment-index="3" -->

----

# `recap.md`

* What went well? <!-- .element: class="fragment" data-fragment-index="1" -->
* What would you improve given/more time resources?<!-- .element: class="fragment" data-fragment-index="2" -->
* Do you have any feedback on the challenge (what would you change, improve, keep…)?<!-- .element: class="fragment" data-fragment-index="3" -->

Note: Anecdote—story about how got this from a candidate. These are great way to provide more perspective about the work of the candidate
