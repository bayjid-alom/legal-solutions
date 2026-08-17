
<details>
<summary>📱 Tailwind Responsive Mindset</summary>

### 🔹 Mobile-First

Tailwind CSS-এ আগে **ছোট screen-এর জন্য default class** লিখতে হয়।  
তারপর বড় screen-এর জন্য `sm:`, `md:`, `lg:` ব্যবহার করতে হয়।

### 📌 কখন কাজ করবে?

| Class | কাজ করবে |
|---|---|
| Default | সব screen |
| `sm:` | **640px+** |
| `md:` | **768px+** |
| `lg:` | **1024px+** |
| `xl:` | **1280px+** |
| `2xl:` | **1536px+** |

### 🔹 Example

```html
<div class="hidden sm:flex">
```