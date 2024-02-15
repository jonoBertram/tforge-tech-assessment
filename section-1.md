# Section 1: Front-end development

### Question 1

> Discuss your experience with frontend development frameworks and libraries such as React, Vue.js, and Gatsby. Provide examples of projects where you've utilized these technologies.

I have accumulated just over three years of front-end development experience in a range of different frameworks and libraries with React and Gatsby at the forefront of it. I have spent most of my professional career working on projects built with a combination of React and Gatsby such as [Yoco](yoco.com) and [Colab](wearecolab.com).

For one smaller internal project that needed to be lightweight for performance and hosting reasons, I have also worked with Vue.js although this is not publicly accessible. I've also used NextJS as the backbone of another internal Yoco tool that does not require the dynamic templating that makes Gatsby inviting and relies heavily on the performance benefits associated with NextJS's server-side rendering due to the large volumes of data that need to be queried, displayed, and manipulated.

### Question 2

> Describe a challenging frontend development task you encountered and how you overcame it.

Recently, I was developing a scrolling marquee banner that is intended to stretch the entire width. The tricky part was ensuring that this banner's text and icons would be fully customisable through the project's CMS of choice, Storyblok.

Since the content would have a variable width based on what an editor might type in Stpryblok, I could not rely on simple CSS translations to create the scrolling text effect. Instead, I had to make use of Javascript's `requestAnimationFrame` functionality to translate the content across the screen based on the content's width in relation to the screen width. This was a complex calculation that took a lot of tweaking to get right but the results in the video below I think show how smooth the final result was.

https://github.com/jonoBertram/tforge-tech-assessment/assets/54099984/8fc4c476-ecbf-4b91-a4e4-df8ffb3bedb4



