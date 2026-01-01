# Tools Reference for Backend Developers

این بخش یک **مرجع ابزارها** برای Backend Developerهاست.

هدف این پوشه:
- لیست‌کردن ابزارهای مفید و واقعی
- دسته‌بندی منطقی ابزارها
- ارجاع به توضیح هر ابزار در پوشه‌ی خودش

> اینجا ابزارها **آموزش داده نمی‌شوند**؛  
> بلکه معرفی می‌شوند تا بدانید:
> «چه ابزاری، برای چه مشکلی، در چه زمانی».

---

## 🧭 نحوه استفاده از این بخش

- هر ابزار در یک پوشه‌ی مستقل قرار دارد
- داخل هر پوشه یک `README.md` وجود دارد
- README هر ابزار شامل:
  - ابزار چیست
  - چه مشکلی را حل می‌کند
  - چه زمانی مناسب است
  - چه زمانی انتخاب بدی است

---

## 🧪 Network & Traffic Inspection

ابزارهایی برای مشاهده، تحلیل و Debug ترافیک شبکه.

- [`Kubeshark`](network/kubeshark/)
  -   https://github.com/kubeshark/kubeshark/
  - مشاهده و تحلیل ترافیک داخل Kubernetes (مشابه Wireshark)

- [`tcpdump`](network/tcpdump/)  
  ابزار کلاسیک Capture ترافیک در سطح سیستم‌عامل

- [`mitmproxy`](network/mitmproxy/)  
  Proxy تعاملی برای تحلیل HTTP/HTTPS

---

## 📊 Observability & Debugging

ابزارهایی برای دیدن وضعیت سیستم در حال اجرا.

- [`Prometheus`](observability/prometheus/)  
  جمع‌آوری و Query متریک‌ها

- [`Grafana`](observability/grafana/)  
  Visualization و Dashboard

- [`Jaeger`](observability/jaeger/)  
  Distributed Tracing

- [`Tempo`](observability/tempo/)  
  Tracing بدون Index سنگین

---

## 🚀 Performance & Load Testing

ابزارهای تحلیل عملکرد و فشار.

- [`k6`](performance/k6/)  
  Load testing مدرن و script-based

- [`wrk`](performance/wrk/)  
  تست فشار سبک و سریع HTTP

- [`hey`](performance/hey/)  
  ابزار ساده برای تست Request

---

## 🔐 Security & Analysis

ابزارهای مرتبط با امنیت و تحلیل ریسک.

- [`Trivy`](security/trivy/)  
  Vulnerability Scanner برای Container و IaC

- [`Falco`](security/falco/)  
  Runtime Security برای Kubernetes

- [`nmap`](security/nmap/)  
  Network Scanning و Discovery

---

## 🧰 Development Utilities

ابزارهای افزایش بهره‌وری توسعه.

- [`direnv`](development/direnv/)  
  مدیریت Environment Variableها

- [`httpie`](development/httpie/)  
  HTTP client خوانا و توسعه‌پسند

- [`jq`](development/jq/)  
  پردازش JSON در CLI

---

## 🧠 نکته مهم

اگر ندانید:
- چه مشکلی دارید
- در چه لایه‌ای
- و چرا

هیچ ابزاری کمک‌تان نمی‌کند.

این بخش برای **انتخاب آگاهانه ابزار** است، نه جمع‌آوری اسامی.
