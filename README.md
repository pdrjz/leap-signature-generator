# Email Signature Generator

This is a simple web-based Email Signature Generator that allows users to input their information and generate a professional email signature in HTML format. The generator provides options to include or exclude certain fields such as pronouns, mobile phone, and work phone, allowing for personalized signatures.

## Features

- **Toggle Fields:** Users can choose to include or exclude the pronoun, mobile phone, and work phone fields using checkboxes.
- **Automatic Phone Number Formatting:** Phone numbers are automatically formatted in the `###.###.####` format.
- **Customizable Pronouns:** Users can specify their preferred pronouns, which will appear next to their name in the signature.
- **Start and Stop Copy Indicators:** Visual indicators are provided to guide users on where to start and stop copying the signature.
- **Flexible Design:** The signature includes the company's logo, a secondary logo, and links to social media profiles.

## How to Use

1. **Fill in Your Information:**
   - Enter your **Name** and **Title** in the respective fields.
   - If you wish to include pronouns, check the "Include Pronoun" box and provide your pronouns in the text field that appears.
   - To include your mobile phone number, check the "Include Mobile Phone" box and enter your mobile phone number.
   - To include your work phone number, check the "Include Work Phone" box and enter your work phone number.
   - Enter your **Email Address** in the designated field.

2. **Generate Your Signature:**
   - Click the `Generate Signature` button. Your customized email signature will be generated and displayed in the output section below the form.

3. **Copy Your Signature:**
   - Use the visual indicators ("⬇️ Start copying below ⬇️" and "⬆️ Stop copying above ⬆️") to highlight the signature. Be sure to include the empty line above the signature when copying.

4. **Paste Your Signature:**
   - Paste the copied signature into your email client (e.g., Gmail, Outlook) to use it as your email signature.

## Files

- `index.html`: The main HTML file containing the structure of the webpage and the form for inputting user information.
- `style.css`: (Optional) A CSS file that can be used to style the form and the output section for better visual presentation.
- `script.js`: (Optional) A separate JavaScript file that contains the logic for generating the signature, toggling fields, and formatting phone numbers.
- `README.md`: This readme file providing an overview and instructions on how to use the Email Signature Generator.

## Customization

- **Logos:** The logos used in the signature (`Leap Logo` and `NAA Top Employer Logo`) are hardcoded in the HTML. If you need to replace these logos, update the `src` attributes of the corresponding `<img>` tags in the HTML file.
- **Default Address:** The address used in the signature is locked to "111 Town Square Pl., Suite 401, Jersey City, NJ 07310". You can change this by editing the `streetAddress` and `cityAddress` variables in the JavaScript code.
- **Website URL:** The signature uses `www.leapeasy.com` as the website URL. This can be modified in the JavaScript code if needed.

## Dependencies

This project uses basic HTML, CSS, and JavaScript, and does not require any external libraries or frameworks.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you encounter any issues or have any questions, please feel free to reach out via the support channels provided.
