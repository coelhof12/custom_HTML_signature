# HTML Email Signature Template

A minimalist and professional HTML email signature template design.

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

- Download the shortcut: [Base64 Image Encoder Shortcut](https://www.icloud.com/shortcuts/f29f2577e88f4158954279fd6b61acca)
- Add the shortcut to your iPhone or Mac (macOS 12+).
- Provide a photo file in ***.png,*** ***.jpg,*** or ***.gif*** format.
- The shortcut will encode the image and generate the correct Base64 syntax, copying it to your clipboard.
- Paste the Base64 image code into your signature.html file where your image URLs are located.

Example:
```<img src="data:image/png;base64,ENCODED_BASE64_IMAGE_HERE" alt="Your Logo" />```

### Compatibility
Tested on:
- Apple Mail
- Gmail
- Outlook

### Contact

Feel free to reach out via email for any questions.
