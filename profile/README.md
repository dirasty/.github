<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5,30&height=200&section=header&text=Dirasty&fontSize=70&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Digitizing%20Iraqi%20Curricula&descAlignY=60&descAlign=50" width="100%" alt="Dirasty banner: Digitizing Iraqi Curricula" />

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2CA5E0&center=true&vCenter=true&width=800&lines=Interactive+Lessons+for+Students;Digital+Tools+for+Teachers;AI-Powered+Summaries;Built+for+Iraq" alt="Animated text: Interactive Lessons for Students, Digital Tools for Teachers, AI-Powered Summaries, Built for Iraq" />

  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi0KgRZG0qTW7Jg0oLUKujTQ4L1dukygv5Lhb790TshK0D1UPkQYOcwjJTQna3ZqWkYkoryQ3e9k_vT6zuZqkoH39FOlQuydg1CrqzmjfX_hwm0rimzRoIrf62dCTR2BHKwZM67NmhPb2U/s0-e90-rw/Flag_of_Iraq.gif" width="200" alt="Animated flag of Iraq" />

  # Dirasty | دراستي
  ### Iraqi Educational Digitalization Platform
  <b>منصة التحول الرقمي للمناهج الدراسية العراقية</b>

  <p>
    <a href="https://t.me/dirastycommunity"><img src="https://img.shields.io/badge/Telegram-Community-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Join the Telegram community"></a>
    <img src="https://img.shields.io/badge/Language-Arabic%20%2F%20English-0052CC?style=for-the-badge" alt="Languages: Arabic and English">
    <img src="https://img.shields.io/github/stars/dirasty/.github?style=for-the-badge&logo=github&color=f5c542" alt="GitHub stars">
    <img src="https://img.shields.io/github/followers/kkkik?style=for-the-badge&logo=github&color=555555" alt="GitHub followers">
    <img src="https://img.shields.io/github/last-commit/dirasty/.github?style=for-the-badge" alt="Last commit">
    <img src="https://komarev.com/ghpvc/?username=kkkik&label=Views&color=0052CC&style=for-the-badge" alt="Profile views">
  </p>

  <p>
    <a href="#overview">Overview</a> ·
    <a href="#features">Features</a> ·
    <a href="#how-it-works">How it works</a> ·
    <a href="#architecture">Architecture</a> ·
    <a href="#security">Security</a> ·
    <a href="#stack">Stack</a> ·
    <a href="#contributing">Contributing</a> ·
    <a href="#community">Community</a> ·
    <a href="#stats">Stats</a>
  </p>

  <blockquote>
    <b>"Students are the nation's code: today's knowledge engineers, tomorrow's sovereignty."</b><br>
    <i>"الطلاب هم الشفرة الوراثية للوطن: معرفة اليوم تُهندس سيادة الغد."</i>
  </blockquote>

</div>

---

<a id="overview"></a>
## 📌 Overview / نبذة

<div align="right">

**دراستي (Dirasty)** منصة تعليمية رقمية تحوّل المناهج الدراسية العراقية النصية إلى تجربة تفاعلية، لتمكين الطلبة والمعلمين بأدوات رقمية حديثة.

</div>

**Dirasty** turns traditional, text-based Iraqi curricula into an interactive digital experience, giving students and teachers modern tools for learning and teaching.

> **Why Dirasty?** Textbooks carry the knowledge. Dirasty makes it easier to access, understand, and interact with, while staying aligned with the official curriculum.
>
> **لماذا دراستي؟** الكتاب المدرسي يحمل المعرفة، ودراستي تجعلها أسهل وصولًا وفهمًا وتفاعلًا، مع البقاء متوافقة مع المنهج الرسمي.

---

<a id="features"></a>
## ✨ Features / المميزات

<div align="center">

| Area / المجال | 🎓 Students / الطلبة | 👨‍🏫 Teachers / المعلمون |
| :---: | :--- | :--- |
| 📚 **Content / المحتوى** | Structured guides aligned with official textbooks<br>ملازم منظمة متوافقة مع الكتب الرسمية | Upload summaries and booklets<br>رفع الملخصات والملازم |
| 🤖 **AI / الذكاء الاصطناعي** | Smart summaries of lessons and complex topics<br>تلخيص ذكي للدروس والمواضيع المعقدة | — |
| 🌐 **Identity / الهوية** | — | Request a dedicated subdomain<br>طلب نطاق فرعي خاص بالمعلم |
| 👥 **Management / الإدارة** | — | Manage student groups and content<br>إدارة مجموعات الطلاب والمحتوى |

</div>

---

<a id="how-it-works"></a>
## 🔄 How it works / كيف يعمل

<div align="center">

| Step / الخطوة | 🎓 Students / الطلبة | 👨‍🏫 Teachers / المعلمون |
| :---: | :--- | :--- |
| **1** | Open the guide that matches your textbook<br>افتح الملزمة المتوافقة مع كتابك | Upload your summaries and booklets<br>ارفع ملخصاتك وملازمك |
| **2** | Study the interactive lesson content<br>ادرس المحتوى التفاعلي للدرس | Organize students into groups and manage content<br>نظّم الطلبة في مجموعات وأدر المحتوى |
| **3** | Use AI summaries to review complex topics<br>استخدم الملخصات الذكية لمراجعة المواضيع المعقدة | Request a dedicated subdomain for your space<br>اطلب نطاقًا فرعيًا خاصًا بمساحتك |

</div>

---

<a id="architecture"></a>
## 🧩 Architecture / البنية

```mermaid
flowchart LR
    S["🎓 Students"] --> FE["Frontend<br/>HTML · CSS · JavaScript"]
    T["👨‍🏫 Teachers"] --> FE
    FE -->|requests| BE["Python backend"]
    BE --> AI["AI summarization engine"]
    BE --> DB[("Encrypted database")]
    T -. "request a subdomain" .-> SD["Dynamic subdomain routing"]
    SD --> FE

    classDef people fill:#2CA5E0,color:#ffffff,stroke:#2CA5E0
    classDef store fill:#0052CC,color:#ffffff,stroke:#0052CC
    class S,T people
    class DB store
```

**Request flow.** The frontend sends requests to the Python backend, which calls the AI summarization engine for summaries and reads from and writes to the encrypted database. Teachers can also request a dedicated subdomain, served through dynamic subdomain routing.

<div align="right">

**مسار الطلب:** ترسل الواجهة طلباتها إلى الخادم المكتوب بلغة Python، الذي يستعين بمحرك تلخيص الذكاء الاصطناعي، ويقرأ البيانات من قاعدة البيانات المشفّرة ويكتب فيها. ويمكن للمعلمين كذلك طلب نطاق فرعي خاص بهم، يُوجَّه عبر نظام التوجيه الديناميكي للنطاقات الفرعية.

</div>

---

<a id="security"></a>
## 🛡️ Security / الأمان

<div align="right">

- 🔐 **المصادقة:** تسجيل حسابات آمن ودخول محمي للطلبة والمعلمين.
- 🗄️ **البيانات:** قاعدة بيانات مشفّرة، ومسارات الاتصال بها غير مكشوفة.
- 📣 **الإبلاغ المسؤول:** إذا اكتشفت ثغرة أمنية، فيُرجى إبلاغ المشرفين بشكل خاص، وعدم فتح Issue عام أو نشرها في قناة المجتمع.

</div>

- 🔐 **Authentication:** Secure sign-up and login for students and teachers.
- 🗄️ **Data:** Encrypted database with protected connection paths.
- 📣 **Responsible disclosure:** If you find a security vulnerability, report it privately to the maintainers. Please do not open a public issue or post it in the community channel.

---

<a id="stack"></a>
## 🛠️ Stack / التقنيات

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,python,sqlite,git,github,vscode,telegram,linux" alt="Technology icons: HTML, CSS, JavaScript, Python, SQLite, Git, GitHub, VS Code, Telegram, Linux" />

| Layer / الطبقة | Technology / التقنية |
| :---: | :--- |
| **Frontend** / الواجهة | HTML5 · CSS3 · Modern JavaScript |
| **Backend** / الخادم | Python |
| **AI** / الذكاء الاصطناعي | LLM-based summarization / تلخيص قائم على نماذج اللغة الكبيرة |
| **Infrastructure** / البنية التحتية | Dynamic subdomain routing · Encrypted database connection |

</div>

---

<a id="contributing"></a>
## 🤝 Contributing / المساهمة

<div align="right">

الاقتراحات والملاحظات وطلبات السحب مرحب بها. افتح **Issue** أو أرسل **Pull Request**.

</div>

Suggestions, bug reports, and pull requests are welcome. Open an **Issue** or send a **Pull Request**.

### Ways to help / طرق المساهمة

| Area / المجال | Ideas / أفكار |
| :--- | :--- |
| 📚 **Content / المحتوى** | Digitize summaries and booklets aligned with official textbooks<br>رقمنة ملخصات وملازم متوافقة مع الكتب الرسمية |
| 🎨 **Interface / الواجهة** | Improve clarity, accessibility, and mobile layouts<br>تحسين الوضوح وإمكانية الوصول والتصميم المتجاوب مع الهواتف |
| ⚙️ **Backend / الخادم** | Improve reliability, security, and performance<br>تحسين الموثوقية والأمان والأداء |
| 🤖 **AI / الذكاء الاصطناعي** | Improve summary quality and accuracy<br>تحسين جودة الملخصات ودقتها |
| 🌍 **Docs / التوثيق** | Keep documentation clear and bilingual<br>إبقاء التوثيق واضحًا وثنائي اللغة |

### How to contribute / خطوات المساهمة

1. Open an **Issue** to discuss larger changes first.<br>افتح **Issue** لمناقشة التغييرات الكبيرة أولًا.
2. Fork the repository and create a focused branch.<br>أنشئ Fork للمستودع، ثم فرعًا مخصصًا للتغيير.
3. Open a **Pull Request** that explains what changed and why.<br>افتح **Pull Request** يشرح ما تغيّر ولماذا.

<div align="center">

<a href="https://github.com/dirasty/.github/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=dirasty/.github" alt="Contributors graph" />
</a>

</div>

---

<a id="community"></a>

<div align="center">

### 📢 Community / المجتمع

انضم لقناتنا لمتابعة آخر التحديثات:<br>
Join our channel for the latest updates.

<a href="https://t.me/dirastycommunity">
  <img src="https://img.shields.io/badge/Telegram-@dirastycommunity-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Join @dirastycommunity on Telegram">
</a>

</div>

---

<a id="stats"></a>
## 📊 Stats / الإحصائيات

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=kkkik&show_icons=true&theme=tokyonight&hide_border=true" height="170" alt="GitHub stats card" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kkkik&layout=compact&theme=tokyonight&hide_border=true" height="170" alt="Top languages card" />

<br><br>

<img src="https://streak-stats.demolab.com/?user=kkkik&theme=tokyonight&hide_border=true" alt="Contribution streak card" />

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=kkkik&theme=darkhub&no-frame=true&column=7" alt="GitHub trophies" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=kkkik&theme=react-dark&hide_border=true&area=true" alt="Activity graph" />

<br><br>

<img src="https://api.star-history.com/svg?repos=dirasty/.github&type=Date" alt="Star history chart" />

</div>

---

<a id="acknowledgments"></a>
## 🙏 Acknowledgments / شكر وتقدير

- Flag animation from [allwavingflags.com](https://www.allwavingflags.com/2018/06/flag-of-iraq.html).
- README visuals are generated by third-party services, including shields.io, capsule-render, readme-typing-svg, skillicons.dev, and github-readme-stats.

<div align="right">

- تحريك علم العراق من موقع allwavingflags.com.
- صور هذا الملف مُولَّدة بواسطة خدمات خارجية، منها shields.io وcapsule-render وreadme-typing-svg وskillicons.dev وgithub-readme-stats.

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,5,30&height=120&section=footer" width="100%" alt="Footer banner" />

<sub><i>Dirasty · Built for the Future of Education in Iraq</i></sub><br>
<sub>دراستي · مستقبل التعليم في العراق</sub>

</div>
