# Section 6: Problem-Solving and Adaptability

### Question 1

> Describe a complex technical problem you encountered in a project and how you approached solving it.

On a particular internal tool I built for Yoco, we were given the objective of making the tool as lightweight and as simple to maintain and run as possible. This involved having as few API calls as possible to the custom backend being built for the tool as well as server-side rendering as much as we could through NextJS.

The tool had to handle a lot of data including user profiles, statements attached to those profiles, and the ability for a user to save and continue editing a statement at any time. This was a huge challenge to plan when trying to trigger as few API requests as possible while still providing all the functionality requested by the client.

I achieved this in the end by using React's built-in [context](https://react.dev/learn/passing-data-deeply-with-context) functionality to create a deep copy of the user's target statement upon querying it from the back-end. This allowed for all statement data manipulation to happen locally while the user was editing and only mutate that data on the backend once the user hit save.

### Question 2

> How do you stay updated with the latest trends and technologies in software development and design?

I follow key figures and innovative companies on LinkedIn which allows me to see any interesting updates they post on my feed there. These include [From Business to Buttons](https://www.linkedin.com/company/from-business-to-buttons/), [The UX Collective](https://www.linkedin.com/newsletters/6915077941559189504/), and [UX Magazine](https://www.linkedin.com/company/ux-magazine/). I also check the Awwwards featured websites often for cutting-edge inspiration. I find [this Youtube channel](https://www.youtube.com/@codegrid) very insightful and inspirational as well
