# Make Changes to the Code

The default currency countries in the code are set to India and USA. If you wish to change the default countries and their flags, follow these steps:

1. For changing the default country currency:
   - Open the `index.js` file.
   - Locate the line with the code:
     ```javascript
     const selected = (i === 0 && curCode === "INR") || (i === 1 && curCode === "USD") ? "selected" : "";
     ```
   - Replace "INR" and "USD" with your desired country codes. For example, if you want to set the default currency to British Pound, replace "USD" with "GBP".
    ```javascript
     const selected = (i === 0 && curCode === "INR") || (i === 1 && curCode === "USD") ? "selected" : "";
    ```

2. For changing the default flags:
   - Open the `index.html` file.
   - Locate lines 26 and 34:
     ```html
     <img src="https://flagcdn.com/48x36/in.png" alt="Currency Flag" />
     ```
     ```html
     <img src="https://flagcdn.com/48x36/us.png" alt="Currency Flag" />
     ```
   - Replace "in" and "us" with the country codes for the flags you desire. For example, replace "us" with "gp" if you want the flag.
```html
     <img src="https://flagcdn.com/48x36/us.png" alt="Currency Flag" />
```   

3. Delete the unnecessary files:
- Remove unnecessary files by deleting the following: `README.md`,` DoThis.md`, and `Changes.md`.

- The `README.md`, `DoThis` file, and `Changes` file are not integral to the code's functionality.
- Deleting these files won't impact the smooth operation of the code.
- If you intend to submit the project, feel free to delete these files; they are not essential for the code's functionality.


> #### If you encounter any issues or have questions, feel free to reach out to us through:

- Email: adityakakadeoffice@gmail.com

- Contact Form: [Contact Form](https://forms.gle/cEcJ9uEiz1XVbsuw8)

