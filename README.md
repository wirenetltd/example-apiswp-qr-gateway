# <div align="center">**APISWP - QR GATEWAY**</div>
## <div align="center">- **REST API AND WEBHOOK** -</div>

### 🔥 **Quick Start Guide**
#### 1️⃣ **Clone the Repository**

Clone the repository to get started with the APISWP QR Gateway project.
```bash
git clone https://github.com/wirenetltd/example-apiswp-qr-gateway.git
```

### **2️⃣ Example PHP Code**<br>
Explore the following PHP examples to send text or images using the API.
<br>

**📱 Send Text Message - PHP Example**<br>
Here is an example of how to send a simple text message using the API.
```php
$body = array(
    "api_key" => "xxxxxxxxxxxx",
    "receiver" => "6285xxx",
    "data" => array("message" => "Hello World")
);
```

**🖼️ Send Image - PHP Example**<br>
Use the following example to send an image via the API.
```php
$body = array(
    "api_key" => "b97b74f802c2802b94358267c160bbd282f5c384",
    "receiver" => "6285xxx",
    "data" => array(
        "url" => "https://i.ibb.co/QbmsBqs/code.png",
        "media_type" => "image",
        "caption" => "Hello World"
    )
);
```


💡 By:
<a href="https://github.com/wirenetltd" target="_blank">WireNet Limited</a>

✨ Features:<br>
🏅 REST API for seamless integration.<br>
🌍 Webhook Support to handle real-time updates.<br>
🔒 Secure Communication with API key validation.<br>
