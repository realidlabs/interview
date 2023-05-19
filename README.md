# Real ID

## Frontend

Inside of frontend-1 there will be html, css, js resources to two landing pages. 

For this exercise use the eviction-reports folder to use as a base template for styling purposes.
If needed you can copy or change the name of the custom.css to whatever naming convention you choose, ie. styles.css

For this create a React project you can share it with me via email. 

[Create a new React App](https://react.dev/learn/start-a-new-react-project) 

- `npx create-next-app`
or 
- `npx create-gatsby`

or any other ReactJs based framework you are comfortable with.

For this you do not need to worry about getting any of the custom js, jQuery, Mapbox or shopper approved functionality working.

For this you shouldn't need any css frameworks. Doing an import of the current css file should suffice.
ie. `import styles from 'css/custom.css';`

## Tasks

While recreating the eviction-reports page, I am looking to see at a minimum the header, footer, pricing and one more section broken out into components. You will see slight differences between the credit-check and eviction-reports examples. To the extent possible, create components that could be used for each page.

Additionally in the pricing component, allow someone to add/remove from cart. 
When someone clicks add to cart, it should update the header nav section to show (if not present) a shopping cart and number indicating number of items added.

The live examples are at: 
- https://www.rtenant.com/credit-checks/
- https://www.rtenant.com/eviction-reports/


Time permitting / extra:

### Create an interactive form: 

The credit checks page has a form in the hero section. Using something like [Formik](https://formik.org/) implement client-side validation to ensure that the inputs meet specific criteria.

