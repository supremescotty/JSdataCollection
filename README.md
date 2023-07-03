# JSdataCollection
Javascript practice and not for true implementation due to privacy protection. Mirroring how cookies collect and track data on our web applications.


Privacy and Consent: This script collects a lot of potentially sensitive information. In a real-world application, it's crucial to obtain informed consent from the user before doing this. You must also comply with relevant data protection laws, like GDPR in Europe or CCPA in California, which have specific requirements for how you must handle and store user data.

Limitations and Accuracy: This script uses several simple techniques to estimate things like internet speed and the presence of an ad-blocker. These techniques are not 100% accurate and have several limitations, so the results should be taken with a grain of salt.

Dependencies: This script depends on several external libraries and services, such as jQuery, js-cookie, and ipapi. If these services go down or change their APIs, the script could stop working.

Browser Compatibility: While the script uses fairly standard JavaScript and should work in most modern browsers, there may be differences or incompatibilities between different browsers, especially older ones, that could affect how the script works.

Potential for Abuse: Be careful with scripts like this, as they can easily be abused for malicious purposes. Always use these tools responsibly and ethically.


NOTE: For userAgreementPrompt section
In this code, the consent form is hidden by default and only shown if the user hasn't already given their consent. When the user clicks one of the buttons, their choice is stored in a cookie and the form is hidden. If the user chooses to decline all cookies, they are redirected to the homepage. After that, if they try to access any other page, they are redirected back to the homepage. This is a basic implementation.
