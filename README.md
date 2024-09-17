# HTML Email Signature Template

A minimalist and professional HTML email signature template design.

## Table of Contents
1. [Features](#features)
2. [Preview](#preview)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Customization Steps](#customization-steps)
4. [Embedding Images in Email Signatures (Optional)](#embedding-images-in-email-signatures-optional)
   - [How to Use the Shortcut](#how-to-use-the-shortcut)
5. [Compatibility](#compatibility)
6. [Contact](#contact)


## Features

- **Personal Logo Display or Picture**
- **Professional Title and Expertise**
- **Location Information**
- **Contact Details (Email and Website)**
- **Social Media Links (LinkedIn & GitHub)**
- **Compatibility with Major Email Clients**

## Preview

![Email Signature Preview](https://raw.githubusercontent.com/coelhof12/custom_HTML_signature/main/signature_preview.png)

## Getting Started

### **Prerequisites**

- A text editor to customize the HTML code.
- Hosting for your images (logo and social media icons).

### **Customization Steps**

1. **Clone or Download the Repository**

   ```bash
   git clone https://github.com/yourusername/email-signature-template.git
   ```

2. **Update Personal Information**

- Open the ```signature.html``` file in your text editor.
- Replace placeholder text with your personal details:
  - Name
  - Title
  - Location
  - Email Address
  - Website URL

3. **Add Your Logo and Icons**

- Upload your logo and social media icons to an image hosting service.
- Replace ```YOUR_LOGO_URL_HERE```, ```LINKEDIN_ICON_URL```, and ```GITHUB_ICON_URL``` with the direct image URLs.

4. **Adjust Colors and Fonts (Optional)**

- Update color codes if you wish to change the color scheme.
- Ensure fonts have appropriate fallbacks.

### **Implement the Signature**

- Copy the entire HTML code.
- Paste it into your email client's signature settings.

### ***Embedding Images in Email Signatures (Optional)***
Why Use Base64 for Images instead of internet hosting?
- No external image hosting: No need to upload your images to a separate server or hosting platform.
- No "Download Images" prompt: Some email clients like Outlook automatically block images until downloaded. With Base64 encoding, the image will load automatically without the need for user intervention.
- Reliable display: Ensures your logo or icons appear as intended in all major email clients. 

To encode image files, you can use an online platform like [base64encode.org](base64encode.org), or if you are a macOS user, I have created a shortcut specifically for this project.

#### How to Use the Shortcut

Encode Images with Ease Using Our iOS Shortcut

If you're a macOS or iPhone user, simplify your workflow by using the Base64 Image Encoder Shortcut I have created, specifically for embedding images in HTML email signatures. Full details and instructions are available on our GitHub repository.

How to Use the Shortcut:
Visit the Base64 Image Encoder project on GitHub.
Follow the instructions to download and use the shortcut.
To learn more about the shortcut and stay updated with future versions, check out the [Base64 Image Encoder project on GitHub](https://github.com/coelhof12/ios-shortcuts-base64-encoder).

Example:
```<img src="data:image/png;base64,ENCODED_BASE64_IMAGE_HERE" alt="Your Logo" />```

### Compatibility
Tested on:
- Apple Mail
- Gmail
- Outlook

### Contact

Feel free to reach out via email for any questions.
