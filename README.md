# AllerFree Terms of Agreement and Privacy Policy
## Terms of Agreement
### 1. Introduction
Welcome to AllerFree, a mobile application designed to assist users in identifying potential allergens in food products through barcode scanning and to provide air quality information based on geolocation. By downloading, installing, or using AllerFree, you agree to be bound by these Terms of Agreement ("Terms"). If you do not agree with these Terms, please do not use the application.

### 2. Purpose and Functionality
AllerFree is a supplementary network-dependent tool intended to help users make informed decisions about food consumption and environmental exposure. The application offers the following key features:

Barcode Scanning: Scans product barcodes to retrieve and analyze ingredient lists from external cloud data sources, flagging potential target matching allergens such as dairy, eggs, fish, shellfish, tree nuts, peanuts, gluten, soybeans, and sesame.

Air Quality Monitoring: Provides real-time air quality index (AQI) data based on the user’s location, offering general recommendations for individuals with respiratory sensitivities.

Allergy Profile: Allows users to input, save, and manage their allergy profiles locally on their device via client-side storage architectures.

Scan History: Stores a historical tracking log of scanned barcodes and matching results locally on the device.

### 3. Limitations of Service & Connectivity Requirements
AllerFree is a supplementary tool and not a substitute for professional medical advice, diagnosis, or treatment. Please note the following systemic limitations:

Network Requirement: AllerFree relies completely on active data networks to execute lookups, string-tokenization matching, and API telemetry. An active internet or cellular data connection is strictly required; offline analysis mode is currently unavailable.

Accuracy: The accuracy of ingredient and allergen information depends entirely on external public data repositories (including the Open Food Facts API and AirNow API), which may contain errors, omissions, or outdated data structures. AllerFree does not guarantee the completeness or accuracy of third-party data payloads.

Allergen Detection: The application may not identify all possible allergens, especially rare or highly personalized sensitivities, or those not explicitly listed in public ingredient fields.

No Medical Advice: AllerFree does not diagnose allergies, assess the severity of allergic reactions, or provide medical evaluations. Users should consult qualified healthcare professionals for personalized allergy management.

### 4. User Responsibilities
By using AllerFree, you agree to:

Verify ingredient and allergen information independently (e.g., by cross-checking physical product labels) before consuming any food product.

Grant necessary client-side permissions (camera access for barcode scanning, location access for air quality telemetry) for the application to function.

Use the application responsibly and understand its boundaries as a non-medical, network-connected asset.

### 5. Intellectual Property
AllerFree, including its underlying implementation code, design layouts, and custom assets, is the intellectual property of Matisse Devin Delane Coleman and is licensed for personal, non-commercial use only. You may not reproduce, distribute, modify, or create derivative works of the application without explicit permission, except as permitted under the open-source license provided within the official GitHub repository.

### 6. Third-Party Services
AllerFree relies on third-party APIs and services to provide its functionality, including:

Open Food Facts API for product specifications.

AirNow API for location-bound air quality telemetry.

These external assets are subject to their own respective terms of use and privacy policies. The developer is not responsible for the availability, infrastructure uptime, or policies of these third-party services.

### 7. Disclaimer of Warranties
AllerFree is provided "as is" without warranties of any kind, express or implied, including but not limited to warranties of merchantability, fitness for a particular purpose, or non-infringement. The developer does not warrant that the application will be completely error-free, uninterrupted, or free from data transmission discrepancies.

### 8. Limitation of Liability
To the fullest extent permitted by law, Matisse Devin Delane Coleman shall not be liable for any direct, indirect, incidental, special, consequential, or punitive damages arising from or related to the use of the application. This includes, but is not limited to, damages resulting from allergic reactions, health complications, or reliance on inaccurate data models. Users assume total responsibility for choices executed based on the application’s information.

### 9. Governing Law
These Terms shall be governed by and construed in accordance with the laws of the State of Louisiana, United States, without regard to its conflict of law principles.

### 10. Contact Information
For questions, feedback, or developer support regarding AllerFree, please contact us at: Superscorex7@gmail.com.

## Privacy Policy
1. Introduction
At AllerFree, we are committed to protecting your privacy and ensuring transparency in how we handle client-side parameters. This Privacy Policy explains what information we process, how it is routed, and your rights regarding your data. By using AllerFree, you consent to the practices described in this policy.

### 2. Information We Process
Local Data Storage
AllerFree is designed to keep your personal footprint contained directly on your machine. The following parameters are initialized and held strictly on your device using UserDefaults local storage:

User Profile & Allergy Matrix: Names (optional) and targeted allergen lists entered directly within the Profile View.

Local Scan History: Records of scanned barcode strings, including timestamps and cross-reference evaluation results.

App State Configuration: User preferences such as custom layout accent selections.

Device Hardware Permissions
Camera Access: Utilized natively to parse frames for barcode strings. Camera data is processed completely on-device and is never streamed or stored externally.

Location Data: Utilized safely to fetch localized air quality metrics based on your general coordinate boundary. Location lookups occur exclusively when the Air Quality View is actively active and are not logged or stored.

Network Data Transmissions
Because an integrated local offline engine is not available in the current deployment phase, the application transmits unidentifiable payload tokens to external entities to complete requests:

API Inquiries: When a barcode is scanned or location coordinates are refreshed, the app transmits the raw barcode digits or coordinate floats to verified public APIs (e.g., Open Food Facts, AirNow). These requests do not contain any personally identifiable information, account credentials, or user profiling data.

### 3. Data Storage and Security
Local Sandboxing: All personal parameters (allergy selections, name configurations, history charts) are maintained within the app's internal sandbox. This information is never transmitted to or shared with any servers or external platforms controlled by the developer.

Security Practices: We adhere strictly to Apple’s core security guidelines for iOS development to protect data inside local device storage. However, no data layer on an internet-connected device is completely impenetrable; security depends heavily on your own device access controls.

### 4. Data Sharing & Third-Party Actions
AllerFree does not track, monetize, sell, or trade your personal interactions. Data transmission is strictly confined to functional requests:

Third-Party APIs: Barcode lookups and environment checks interact with Open Food Facts and AirNow nodes. Their handling of raw string requests is governed independently by their respective developer privacy policies.

Direct Support Channels: If you choose to initiate a support request via the built-in email link, your email address and any contextual logs you choose to provide will be transmitted securely to Superscorex7@gmail.com for debugging and response purposes.

### 5. Your Rights and Management Choices
Absolute Deletion: Because all personal data structures exist solely within your local on-device sandbox, you retain complete authority over them. You can wipe your history directly within the application settings, or permanently delete all associated configuration data by uninstalling AllerFree from your iOS device.

Permission Management: You can explicitly grant or revoke system camera and location access flags at any time through the native iOS Settings application.

### 6. Changes to This Privacy Policy
The developer reserves the right to update this policy to reflect ongoing architecture additions or framework modifications. Updated policies will be published directly within the application metadata or the associated GitHub distribution files. Continued use of the application following an update indicates explicit acceptance of the active policy parameters.

Last Updated: May 19, 2026
