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

</details> 

<br> 












<details>
     <summary>🔗 Tailwind Animated Underline</summary>
🔹 Left-to-Right Underline

Navbar <a> tag-এ Tailwind দিয়ে animated underline তৈরি করতে:


```

<a href=""
    class="relative pb-1
    after:absolute after:left-0 after:bottom-0
    after:h-[2px] after:w-full
    after:origin-left after:scale-x-0
    after:bg-[#B68C5A]
    after:transition-transform after:duration-300
    hover:after:scale-x-100">
    Home
</a>

```

</details>



### ❔ Classes

- `relative` → Underline-এর position ঠিক রাখে।
- `after:absolute` → Underline-কে link-এর সাথে absolute করে।
- `after:left-0` → Underline বাম দিক থেকে শুরু করে।
- `after:bottom-0` → Underline link-এর নিচে রাখে।
- `after:h-[2px]` → Underline-এর thickness সেট করে।
- `after:w-full` → Underline পুরো link-এর width নেয়।
- `after:origin-left` → Animation বাম দিক থেকে শুরু করে।
- `after:scale-x-0` → শুরুতে underline লুকিয়ে রাখে।
- `hover:after:scale-x-100` → Hover করলে underline পুরোটা দেখায়।
- `after:transition-transform` → Underline-এর movement smooth করে।
- `after:duration-300` → Animation 300ms সময় নেয়।