# Privacy Policy for PhotoGulo AI Photo Color Grading

**Last Updated:** October 26, 2026  
**Application Name:** PhotoGulo AI Photo Color Grading  
**Application ID:** `com.github.pbseudocoder.photogulo`  
**Developer:** PhotoGulo App Team  

---

## Overview & Privacy Guarantee

Welcome to **PhotoGulo AI Photo Color Grading** ("PhotoGulo", "the Application", "we", "us", or "our"). We are committed to protecting your privacy.

> **Key Guarantee: 100% On-Device Processing**  
> PhotoGulo is designed from the ground up to operate entirely on your device. All photo enhancement, color grading, neural inference, and image processing happen strictly on your hardware. **No photos, media files, facial data, or personal information are ever uploaded, transmitted, or stored on external servers or cloud services.**

---

## 1. Information We Do NOT Collect

We believe that the best way to protect your privacy is not to collect your data in the first place:

- **No Photo Uploads:** We do not transmit, upload, copy, or store your photographs or media to any remote server or cloud infrastructure.
- **No Personal Information:** We do not ask for or collect personal identifiers such as your name, email address, physical address, phone number, or login credentials. No account registration is required to use the Application.
- **No Biometric or Facial Recognition Data:** The on-device artificial intelligence does not scan, extract, map, or store facial geometry, biometric signatures, or facial landmarks. The model strictly evaluates color values to predict photographic tone curve adjustments.
- **No Telemetry or Behavioral Tracking:** We do not track your usage habits, click events, photo editing frequency, or personal preferences.
- **No Advertising IDs:** The Application does not contain third-party advertising SDKs and does not collect Android Advertising IDs (AAID) for ad targeting.

---

## 2. How the Application Operates Locally

When you use PhotoGulo, all operations are isolated to your device:

1. **Photo Selection:** You select photos through Android's secure system Photo Picker (`PickVisualMedia`). The photo is opened locally and held in temporary device memory solely for editing.
2. **On-Device AI Inference:** The parametric color grading network executes on your local hardware using on-device runtime libraries. This works completely offline without needing an active internet connection.
3. **Parametric Photographic Adjustment:** The neural engine predicts photographic parameters (such as cubic tone curves, graduated adjustments, and vignettes) directly on your photograph's pixels. It is strictly non-generative and does not invent or hallucinate new imagery.
4. **Saving & Sharing:** When you tap **Save Photo**, the rendered image is saved directly to your device's gallery (`Pictures/AIGrading`). When you tap **Share**, the image is handed over to your device's native Android share dialog. No media is shared unless you explicitly initiate the action.

---

## 3. Device Permissions

PhotoGulo requests only the minimum permissions necessary to function:

- **Photo Access / Media Reading:** Requested through Android's system photo picker to permit you to choose photos you wish to enhance.
- **Storage / Media Writing (`WRITE_EXTERNAL_STORAGE` on Android 9 and below, `MediaStore` on Android 10+):** Used exclusively to save edited photographs to your device's photo library upon your explicit request.

The Application does not require or use background location, contacts, microphone, or camera hardware access.

---

## 4. Third-Party Services and Analytics

- **No Third-Party Analytics:** We do not use Google Analytics, Firebase Analytics, Flurry, or any other analytics tools.
- **No Advertising Networks:** We do not display advertisements or integrate ad networks (such as Google AdMob, Unity, or AppLovin).
- **No Cloud APIs:** All image processing runs using embedded on-device libraries. No external computer vision or cloud grading APIs are used.

---

## 5. User Ownership & Intellectual Property

- You retain **100% exclusive ownership, copyright, and all intellectual property rights** to your original and color-graded photographs.
- PhotoGulo claims no copyright, license, royalty, or ownership interest in any photos processed or exported with the Application.
- You are free to use your exported photographs for both personal and commercial projects without restriction or attribution.

---

## 6. Data Retention and Deletion

Because PhotoGulo does not collect, receive, or store any of your data on servers or databases:

- We hold no user data to retain, inspect, or delete.
- When you close the Application or select a different photograph, any temporary image buffers in memory are automatically cleared.
- Any photos saved to your device gallery remain under your full control, and you can delete them at any time using your preferred gallery or file manager app.

---

## 7. Children's Privacy

The Application does not collect any personal information from any user, including children under the age of 13 (or under 16 in applicable jurisdictions). PhotoGulo complies fully with the Children's Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).

---

## 8. Security

Because all processing occurs locally within Android's sandboxed application environment:

- Your photos never travel over the internet, protecting them against interception, man-in-the-middle attacks, and remote server data breaches.
- We recommend keeping your Android operating system updated to maintain the highest level of on-device security.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect operational, legal, or regulatory changes. Any modifications will be posted to this page with an updated "Last Updated" date. If significant changes occur, we will provide additional notice through an updated release of the Application.

---

## 10. Contact Us

If you have any questions, feedback, or inquiries regarding this Privacy Policy or the Application's privacy practices, please contact us:

- **Email:** [pbseudocoder@gmail.com](mailto:pbseudocoder@gmail.com)
- **Application Support:** PhotoGulo Developer Support Team
