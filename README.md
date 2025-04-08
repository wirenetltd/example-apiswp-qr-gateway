## <div align="center">**LAZY GATEWAY - WALIX 3.x**</div>
#### <div align="center">- **REST API AND WEBHOOK** -</div>

#### **# GIT CLONE :**
```bash
git clone https://github.com/wirenetltd/example-apiswp-qr-gateway.git
```

### **# Example Body Array PHP**
<br>

**PHP Example Send Text :**
```php
$body = array(
    "api_key" => "xxxxxxxxxxxx",
    "receiver" => "44xxxxxxxxxx",
    "data" => array("message" => "Hello World")
);
```
**PHP Example Send Image :**
```php
$body = array(
    "api_key" => "b97b74f802c2802b94358267c160bbd282f5c384",
    "receiver" => "44xxxxxxxxxx",
    "data" => array(
        "url" => "https://i.ibb.co/QbmsBqs/code.png",
        "media_type" => "image",
        "caption" => "Hello World"
    )
);
```

#### **By :**
- <a href="https://github.com/wirenetltd">**WireNet Limited** </a>
