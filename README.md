# <div align="center">**APISWP - QR GATEWAY**</div>
## <div align="center">- **REST API AND WEBHOOK** -</div>

---

### 🔥 **Quick Start Guide**

#### 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/wirenetltd/example-apiswp-qr-gateway.git
2️⃣ Example PHP Code
📱 Send Text Message - PHP Example
php
Kopyala
Düzenle
$body = array(
    "api_key" => "xxxxxxxxxxxx", // Your API key
    "receiver" => "44xxxxxxxxxx", // Recipient phone number
    "data" => array("message" => "Hello World") // The message content
);
🖼️ Send Image - PHP Example
php
Kopyala
Düzenle
$body = array(
    "api_key" => "b97b74f802c2802b94358267c160bbd282f5c384", // Your API key
    "receiver" => "44xxxxxxxxxx", // Recipient phone number
    "data" => array(
        "url" => "https://i.ibb.co/QbmsBqs/code.png", // URL of the image
        "media_type" => "image", // Media type (image)
        "caption" => "Hello World" // Caption for the image
    )
);
💡 By:
<a href="https://github.com/wirenetltd" target="_blank">WireNet Limited</a>

✨ Features:
🏅 REST API for seamless integration.

🌍 Webhook Support to handle real-time updates.

🔒 Secure Communication with API key validation.

Contact & Support:
For questions or further support, visit WireNet Limited GitHub.

