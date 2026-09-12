# Privacy Policy for AstroScan: Birth Chart & HUD

**Last updated: September 12, 2026**

This Privacy Policy governs the data privacy practices of **AstroScan: Birth Chart & HUD** (hereinafter referred to as "the Application"), a mobile application developed for Android devices. 

Our core philosophy is absolute user privacy. The Application is designed to function **100% offline**. All astronomical calculations, numerological matrix generation, and image scanning processes are executed strictly on your local device. We do not own, maintain, or use any remote servers to collect or store your personal data.

---

## 1. Information Collection and Use

### Personal Data (Birth Details)
To generate your natal chart, relationship compatibility scoring, and Pythagoras numerology matrix, the Application requires you to input:
* Name or Alias
* Date and Time of birth
* Gender
* City of birth (to extract geographic coordinates and time zone data)

**Local Processing Only:** This data is saved exclusively within a secured, local SQLite database on your physical device. It is never transmitted over the internet, never shared with third parties, and never uploaded to any external servers.

### Camera Access and Image Processing
The Application requests permission to access your device's camera to enable the Optical Palmistry Scanner module.
* **On-Device Computation:** The camera viewfinder frames and captured images are processed instantaneously in the device's volatile memory (RAM) using advanced programmatic image processing algorithms to detect major palm lines.
* **No Image Storage:** The Application does not save, store, or transmit your photos or biometric palm matrices. Once the scanning pipeline finishes generating the local text report, the temporary image buffer is immediately flushed and permanently destroyed.

### Location Data
The Application contains a built-in offline database of global cities to map birth locations to geographic coordinates (latitude and longitude). The Application does not track your physical real-time GPS location.

---

## 2. Third-Party Services and Network Traffic

The Application does not contain any third-party analytics SDKs, advertising networks, or user tracking tools. 

### Global City Map Sync
The Application may occasionally access official open-source repositories (such as GeoNames) to initially download or synchronize the offline city database. This network operation does not transmit any identifiable personal telemetry or user birth details.

---

## 3. Data Retention and Deletion

Since all data remains stored solely within the Application's local storage sandbox on your device, you have absolute control over it:
* You can modify or delete any user profile directly inside the application's interface at any time.
* Uninstalling the Application from your device will automatically destroy all locally stored profiles, databases, and user inputs permanently.

---

## 4. Children’s Privacy

The Application does not knowingly collect or solicit any data from children under the age of 13. Since all inputs remain strictly offline on the user's physical device, we do not possess any means to review, collect, or manage this data remotely. If a parent or guardian becomes aware that their child has entered information locally, they can clear it instantly by deleting the profile or uninstalling the app.

---

## 5. Compliance with Global Privacy Laws (GDPR & CCPA)

Because the Application does not transfer data to any external entities or process personal data on servers, it inherently satisfies the privacy-by-design standards required by the General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA). Your rights to data access, modification, and erasure are completely fulfilled by the local interface controls provided within the app.

---

## 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Any changes will be made transparently by updating this document on our official GitHub repository. You are advised to review this page periodically for any modifications.

---

## 7. Contact Us

If you have any questions or feedback regarding this offline Privacy Policy, please contact the developer via the official GitHub repository issues panel or support email provided in the Google Play Console listing.
