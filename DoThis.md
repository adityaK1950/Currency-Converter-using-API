# ExchangeRate-API

## To set up your ExchangeRate API key for the Currency Converter, follow these steps:

1. Visit the [ExchangeRate-API website](https://www.exchangerate-api.com/).

2. Click on "Get Free Key!" to start the process.
- ![CC 1](https://github.com/adityaK1950/Calculator-in-Python/assets/156563981/f009b92d-c0b5-4d58-ba90-79315f144e39)


3. If you already have an account, enter your email and password to log in. If not, click on "Don't have an account yet? Sign Up."


4. For new users, fill in the required details like email and password. Accept the terms and create your API key.
- ![CC 2](https://github.com/adityaK1950/Calculator-in-Python/assets/156563981/a4201fa7-b257-43a9-a8e0-c4ddf9ecc625)

5. After creating an account, go to the API Keys section.
- ![CC 3](https://github.com/adityaK1950/Calculator-in-Python/assets/156563981/b8e894d7-64c5-4917-960e-2f608b3bba77)


6. Copy the API key that is generated.

7. Paste the API key into the appropriate location in your code.
   > Open the `index.js` file in the code and update line number 29, replacing `[YOUR KEY]` with your generated API key. To simplify, replace the API key in the following line as well:

```javascript
const response = await fetch(`https://v6.exchangerate-api.com/v6/[YOUR API KEY]/latest/${fromCur.value}`);
```

Now, your Currency Converter is configured with the ExchangeRate-API!

> #### If you encounter any issues or have questions, feel free to reach out to us through:

- Email: adityakakadeoffice@gmail.com

- Contact Form: [Contact Form](https://forms.gle/cEcJ9uEiz1XVbsuw8)
