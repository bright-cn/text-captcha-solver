# 文本型 CAPTCHA 解决方案  

[![Promo](https://github.com/bright-cn/LinkedIn-Scraper/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner.png)](https://www.bright.cn/products/web-unlocker/captcha-solver/text-captcha)

借助 Bright Data 的高级 CAPTCHA 解决方案，轻松绕过文本型 CAPTCHA。通过机器学习算法、[自动化 IP 轮换](https://www.bright.cn/solutions/rotating-proxies)以及强大的代理基础设施，确保对目标站点的访问持续稳定，无缝进行。  

Bright Data 的 CAPTCHA Solver 是 [**抓取浏览器**](https://www.bright.cn/products/scraping-browser) 和 [**网络解锁器 API**](https://www.bright.cn/products/web-unlocker) 的内置功能，为处理各种复杂的 CAPTCHA 挑战提供完整的解决方案。  

## 功能  
- **快速解决 CAPTCHA**：自动、高准确度与高速地解决文本型 CAPTCHA。  
- **IP 轮换**：通过自动重试和动态 IP 调整，避免被封禁。  
- **浏览器指纹模拟**：模拟真实用户行为，以[绕过高级反爬取检测](https://www.bright.cn/blog/web-data/anti-scraping-techniques)。  
- **JavaScript 渲染**：处理大量使用 JavaScript 的站点上的动态内容。  
- **全球地理覆盖**：精准定位，解锁来自全球各地的内容。  
- **无缝集成**：可与 Puppeteer、Playwright、Selenium 等工具轻松搭配使用。  
- **事件监控**：跟踪 CAPTCHA 解决事件，如检测、成功或失败。  

## 为什么选择文本型 CAPTCHA 解决方案  

### **全球 20,000+ 客户的信赖**  
Bright Data 的 CAPTCHA Solver 因其无与伦比的可靠性和高性能，受到开发者、企业和组织的信赖。  

### **由高级代理网络驱动**  
拥有超过 1 亿个 IP 和高级定向功能的代理基础设施，确保流畅且不中断的 CAPTCHA 解决过程。  

### **AI 驱动的 CAPTCHA 解决**  
此 CAPTCHA Solver 利用先进的 AI 逻辑来自动检测、分析并解决 CAPTCHA。它能够处理重试、指纹模拟以及请求头设置，绕过高等级的反机器人措施。  

### **为开发者而打造**  
- 可与 Puppeteer、Playwright 和 Selenium 无缝集成。  
- CAPTCHA 解决行为可自定义配置。  
- 支持自动重试和动态 IP 调整，保证爬取不中断。  

> **专业提示 💡**  
>> 已经有自己的 CAPTCHA 解决方案？可结合我们针对 [Puppeteer](https://www.bright.cn/integration/puppeteer)、[Playwright](https://www.bright.cn/integration/playwright) 和 [Selenium](https://www.bright.cn/integration/selenium) 的代理，进一步减少 CAPTCHA 难度。  

## 工作原理  

Bright Data 的 CAPTCHA Solver 集成在 **Scraping Browser** 和 **Web Unlocker** 中，让 CAPTCHA 解决变得轻而易举。  

### **自动化 CAPTCHA 解决**  
CAPTCHA Solver 会实时自动检测并解决 CAPTCHA。只需启用此功能，检测到 CAPTCHA 后会自动完成解决流程。  

#### 示例工作流程：  
1. **检测 CAPTCHA**：识别 CAPTCHA 类型（如 PerimeterX）。  
2. **破解 CAPTCHA**：通过基于 AI 的逻辑解决该 CAPTCHA。  
3. **失败重试**：如果解决失败，系统会自动切换新 IP 并重试。  
4. **返回结果**：成功后，系统将为目标站点提供无缝访问。  

## 支持的 CAPTCHA 类型  

Bright Data 的 CAPTCHA Solver 支持多种 CAPTCHA 类型，包括：  

- [**DataDome**](https://www.bright.cn/products/web-unlocker/captcha-solver/datadome)
- [**reCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/recaptcha)
- [**Click Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/click-captcha)
- [**Cloudflare**](https://www.bright.cnm/products/web-unlocker/captcha-solver/Cloudflare)
- [**PerimeterX**](https://www.bright.cn/products/web-unlocker/captcha-solver/perimeterx)
- [**SimpleCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/simplecaptcha)
- [**FunCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/funcaptcha)
- [**Cloudflare Turnstile**](https://www.bright.cn/products/web-unlocker/captcha-solver/cloudflare-turnstile)
- [**AWS WAF Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/aws-waf-captcha)
- [**GeeTest CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/geetest-captcha)
- [**KeyCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/keycaptcha)
- [**Puzzle CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/puzzle-captcha)
- [**Yandex CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)
- [**Image CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/image-captcha)
- [**Text CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/text-captcha)

## 高级自定义  

[Bright Data 的 CAPTCHA Solver](https://github.com/bright-cn/Captcha-solver) 提供高级配置选项，以便在特定场景下对解决逻辑进行微调。

### **针对文本型挑战的自定义选项**  
```javascript
// 为不同的 CAPTCHA 类型定义默认选项
function getCaptchaOptions(captchaType, customOptions = {}) {
  const defaultOptions = {
    timeout: 30000, // 等待 CAPTCHA 解决的最长时间（毫秒）
    check_timeout: 500, // 检查 CAPTCHA 状态的时间间隔（毫秒）
    wait_networkidle: { timeout: 1000 }, // 等待网络空闲 1 秒
    debug: false // 调试模式（默认关闭）
  };

  // 定义各类 CAPTCHA 的选择器
  const captchaSelectors = {
    DataDome: { selector: '#datadome-captcha', success_selector: '#captcha-success' },
    reCAPTCHA: { selector: '.g-recaptcha', success_selector: '.recaptcha-success' },
    ClickCaptcha: { selector: '.click-captcha', success_selector: '.captcha-passed' },
    hCaptcha: { selector: '.h-captcha', success_selector: '.hcaptcha-success' },
    PerimeterX: { selector: '#px-captcha', success_selector: '#px-success' },
    SimpleCaptcha: { selector: '.simple-captcha', success_selector: '.captcha-done' },
    FunCaptcha: { selector: '.funcaptcha', success_selector: '.funcaptcha-success' },
    CloudflareTurnstile: { selector: '.cf-turnstile', success_selector: '.cf-success' },
    AWSWAF: { selector: '#aws-waf-captcha', success_selector: '#aws-waf-success' },
    GeeTest: { selector: '.geetest-captcha', success_selector: '.geetest-success' },
    KeyCAPTCHA: { selector: '#keycaptcha', success_selector: '#keycaptcha-success' },
    PuzzleCAPTCHA: { selector: '.puzzle-captcha', success_selector: '.puzzle-solved' },
    YandexCAPTCHA: { selector: '#yandex-captcha', success_selector: '#yandex-success' },
    ImageCAPTCHA: { selector: '.image-captcha', success_selector: '.image-captcha-success' },
    TextCAPTCHA: { selector: '.text-captcha', success_selector: '.text-captcha-success' }
  };

  // 获取对应 CAPTCHA 类型的选择器
  const selectedOptions = captchaSelectors[captchaType] || {};

  // 将默认选项、该 CAPTCHA 的选择器以及自定义选项合并
  return { ...defaultOptions, ...selectedOptions, ...customOptions };
}

// 针对不同 CAPTCHA 类型的示例用法
const ddOptions = getCaptchaOptions('DataDome', { timeout: 40000, debug: true });
const recaptchaOptions = getCaptchaOptions('reCAPTCHA', { debug: true });
const hcaptchaOptions = getCaptchaOptions('hCaptcha');

console.log(ddOptions);
console.log(recaptchaOptions);
console.log(hcaptchaOptions);

// 示例错误处理
try {
  if (!document.querySelector(ddOptions.selector)) {
    throw new Error(`未能使用选择器 ${ddOptions.selector} 找到 CAPTCHA 元素`);
  }

  // 此处添加你的 CAPTCHA 解决逻辑
  solveCaptcha(ddOptions);
} catch (error) {
  console.error('解决 CAPTCHA 失败:', error.message);
}
```

## **事件监控**  
跟踪 CAPTCHA 解决事件，以满足高级用例需求：  
- `Captcha.detected`：检测到 CAPTCHA 并开始解决。  
- `Captcha.solveFinished`：成功解决 CAPTCHA。  
- `Captcha.solveFailed`：CAPTCHA 解决失败。  

## **定价**

| **方案**             | **价格（每 1K 结果）** | **月度费用**          | **描述**                                             |  
|----------------------|------------------------|-----------------------|------------------------------------------------------|  
| **按使用付费**       | $1.50                 | 无需承诺              | 适合零散的爬取需求。                                 |  
| **成长版（Growth）** | $1.27                 | $499                 | 专为需要扩展的团队所设计。                           |  
| **企业版（Business）** | $1.12                 | $999                 | 适用于大规模爬取业务。                               |  
| **高级版（Premium）**  | $1.05                 | $1,999               | 提供高级功能与优先支持服务。                          |  
| **定制版（Enterprise）** | 自定义报价          | 请联系我们           | 面向顶级业务需求量身定制。                           |  

🚀 **特别优惠**：首次充值可获得最高 **$500** 的同等金额赠送！  

## **开发者对文本型 CAPTCHA 解决方案的喜爱之处**  
- **易于集成**：可与 Puppeteer、Playwright、Selenium 无缝对接。  
- **先进的 AI 逻辑**：自动处理重试、CAPTCHA 识别、指纹模拟、IP 轮换及高级请求头。  
- **内置浏览器**：无需额外管理 JavaScript 渲染的外部浏览器。  
- **实时洞察**：通过实时仪表板监控网络性能。  
- **无与伦比的支持**：7 × 24 小时全球客户支持，且新功能不断上线。  

## **常见问题**  

### **文本型 CAPTCHA 解决方案如何运行？**  
该方案使用先进的 AI 逻辑自动检测并解决文本型 CAPTCHA。  

### **能同时处理多个 CAPTCHA 吗？**  
可以，系统可扩展以同时应对多种类型的 CAPTCHA，确保访问不中断。  

### **如果解决 CAPTCHA 失败怎么办？**  
系统会自动进行重试。如果问题依旧存在，可随时联系我们 7×24 小时的支持团队进行排查。  

---

## **告别文本型 CAPTCHA 的烦恼**  
立即开始免费试用，亲身体验 [Bright Data 的文本型 CAPTCHA 解决方案](https://www.bright.cn/products/web-unlocker/captcha-solver/text-captcha)！  
