### [Go live Buddy!](https://tushar-ojha-microsoft.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/08792b0d-05a4-4f99-97ad-0f08934f1468/deploy-status)](https://app.netlify.com/sites/tushar-ojha-web-design-landing-page/deploys)
### Key Points to note:-

- They need my attention:
    - inline-flex, flex-baseline, text-base.
    
- npm i gets us the node_modules folder while npm init just generates a basic package.json file.

- We can save svg code in assets/search.svg file and include it using img tag inside html file.

- Dirty fix is not bad. Sometimes we really need to use it and there is nothing wrong about it.

- Trick: Always give logical class name to elements so that we can easily search them to add classes as and when needed.

- underline-offset sets distance between the element and it's underline.

- wesiteURL/favicon.ico to get favicon.

- space-x; very important property. Applies space among all children.

- text-left

- justify-center = justify-content: center; takes all element to center across main axis (means by default on horizontal axis).

- items-center aligns items along center of container along cross-axis (means by default on vertical line).

- hidden class display: none; we can directly use it. Use case: when we want to render any element when certain breakpoint is hit. hidden md:block

- justify-between is leaves space in between the elements similar to justify-content: space-between while justify-around is like space-around

- When elements/items are of different sizes in container of type flex, then shorter elements just sticks to the top which doesn't give uniform look. To solve this problem we can do **justify-center** **items-center**

- md:order-1; interesting use case of order! When we want to change the order of elements of container of type flex on different screens.
