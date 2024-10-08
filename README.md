# HTML Email Signature Template ✉️

A minimalist and professional HTML email signature template design.

![Project Cover](https://raw.githubusercontent.com/coelhof12/custom_HTML_signature/main/assets/Repo_Cover.jpg)

## The Concept 💡

This template is easy to customize and compatible with major email clients like Apple Mail and Gmail. Offers a simple yet customizable HTML email signature template designed for seamless integration with major email clients. Follow the steps below to personalize the signature with your own information, logo, and social media links. 

## Preview 👀

![Siganture Preview](https://raw.githubusercontent.com/coelhof12/custom_HTML_signature/refs/heads/main/assets/signature_preview.png)

## Table of Contents 📚

1. [Features](#features)
2. [Preview](#preview)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Customization Steps](#customization-steps)
4. [Embedding Images in Email Signatures (Optional)](#embedding-images-in-email-signatures-optional)
   - [How to Use the Shortcut](#how-to-use-the-shortcut)
5. [Compatibility](#compatibility)
6. [Contact](#contact)

## Features ✨

- **Personal Logo Display or Picture**
- **Professional Title and Expertise**
- **Location Information**
- **Contact Details (Email and Website)**
- **Social Media Links (LinkedIn & GitHub)**
- **Compatibility with Major Email Clients**

## Getting Started 🚀

### **Prerequisites** ✅

- A text editor to customize the HTML code.
- Hosting for your images (logo and social media icons).

### **Customization Steps** 🎨

1. **Clone or Download the Repository** 

   ```bash
   git clone https://github.com/yourusername/email-signature-template.git
   ```

2. **Update Personal Information**

- Open the `signature.html` file in your text editor.
- Replace placeholder text with your personal details:
  - Name
  - Title
  - Location
  - Email Address
  - Website URL

3. **Add Your Logo and Icons**

- Upload your logo and social media icons to an image hosting service.
- Replace `YOUR_LOGO_URL_HERE`, `LINKEDIN_ICON_URL`, and `GITHUB_ICON_URL` with the direct image URLs.

4. **Adjust Colors and Fonts (Optional)**

- Update color codes if you wish to change the color scheme.
- Ensure fonts have appropriate fallbacks.

### **Implement the Signature** ✍️

- Copy the entire HTML code.
- Paste it into your email client's signature settings.

### **_Embedding Images in Email Signatures (Optional)_** 🖼️

Why Use Base64 for Images instead of internet hosting?

- No external image hosting: No need to upload your images to a separate server or hosting platform.
- No "Download Images" prompt: Some email clients like Outlook automatically block images until downloaded. With Base64 encoding, the image will load automatically without the need for user intervention.
- Reliable display: Ensures your logo or icons appear as intended in all major email clients.

To encode image files, you can use an online platform like [base64encode.org](base64encode.org), or if you are a macOS user, check out the [Base64 Image Encoder project on GitHub](https://github.com/coelhof12/ios-shortcuts-base64-encoder) I have created, specifically for embedding images in HTML email signatures. Full details and instructions are available on our GitHub repository.

Example:
`<img src="data:image/png;base64,ENCODED_BASE64_IMAGE_HERE" alt="Your Logo" />`

### Compatibility 📱

Tested on:

- Apple Mail
- Gmail
- Outlook

### Contact 📬

Feel free to reach out via email for any questions.
