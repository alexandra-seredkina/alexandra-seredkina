<div align="center">

<img src="https://raw.githubusercontent.com/alexandra-seredkina/alexandra-seredkina/main/assets/banner.jpeg" alt="Cute anime illustration: a red-haired girl with a laptop and a black cat on a cozy rooftop in a pastel neon city" height="220">

# Aleksandra Seredkina

**Application Security · Web & API Pentesting**

<a href="https://personal-site-omega-six-53.vercel.app/"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=22&amp;duration=3000&amp;pause=1000&amp;color=FF5C8A&amp;center=true&amp;vCenter=true&amp;width=680&amp;lines=Web+%26+API+pentesting;Secure+code+review+%26+threat+modeling;DevSecOps+pipelines+in+CI%2FCD;Think+like+an+attacker.+Build+like+a+defender." alt="Web and API pentesting · Secure code review and threat modeling · DevSecOps"></a>

<a href="https://personal-site-omega-six-53.vercel.app/"><img src="https://img.shields.io/badge/Website-Open-FF5C8A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
<a href="https://www.linkedin.com/in/alexandra-seredkina/"><img src="https://img.shields.io/badge/LinkedIn-Aleksandra_Seredkina-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://t.me/meownesss"><img src="https://img.shields.io/badge/Telegram-@meownesss-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
<a href="mailto:itsec.seredkina@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-8B7CFF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://tryhackme.com/p/Meowness"><img src="https://img.shields.io/badge/TryHackMe-Top_2%25-4DE1D2?style=for-the-badge&logo=tryhackme&logoColor=0d1117" alt="TryHackMe, top 2 percent"></a>

</div>

---

## 👾 About

<table>
<tr>
<td valign="middle">

**4+ years** of building production software. Now I break it so it stays unbroken.
I understand the code and the architecture, not just the exploits.

- 🕷 **Web & API pentesting**: OWASP Top 10, broken authentication and access control, JWT & OAuth, logic bugs
- 🔍 **Secure code review & threat modeling**: design reviews, secure coding practices
- 🔁 **DevSecOps**: SAST, SCA and secret detection on every merge request
- 🛡 **Hardening**: rate limiting, security headers, Nginx, SSH policies, 2FA

</td>
<td width="260" valign="middle">

<img src="https://raw.githubusercontent.com/alexandra-seredkina/alexandra-seredkina/main/assets/about.jpeg" alt="Portrait of a cute red-haired anime girl with a small glowing shield in her palm and a black cat on her shoulder" width="240">

</td>
</tr>
</table>

---

## 🛠 Projects

<table>
<tr>
<td width="240" valign="top">

<img src="https://raw.githubusercontent.com/alexandra-seredkina/alexandra-seredkina/main/assets/projects.jpeg" alt="The character next to a floating locked envelope and a glowing server rack with her black cat lying on top" width="220">

</td>
<td valign="top">

### 🔐 [ShadowBox](https://github.com/alexandra-seredkina/ShadowBox-Backend) — anonymous mail that cannot read your messages
Sign up with a login and a password, no phone, no name. A separate address for every site, and every message is encrypted the moment it arrives. Keys live only in the browser; the server keeps ciphertext. Built threat-model-first, with phishing labels (SPF / DKIM / DMARC) on incoming mail.
Crypto: X25519, XChaCha20-Poly1305, Argon2id (libsodium). Sessions in `__Host-` cookies, nonce-based CSP, rate limiting. Semgrep and dependency audit on every pull request.<br>
<img src="https://img.shields.io/badge/NestJS-0d1117?style=flat-square&logo=nestjs&logoColor=FF5C8A" alt="NestJS">
<img src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=FF5C8A" alt="Next.js">
<img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=FF5C8A" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=FF5C8A" alt="Docker">
<img src="https://img.shields.io/badge/Nginx-0d1117?style=flat-square&logo=nginx&logoColor=FF5C8A" alt="Nginx">
<img src="https://img.shields.io/badge/libsodium-0d1117?style=flat-square&logoColor=FF5C8A" alt="libsodium"><br>
[Backend](https://github.com/alexandra-seredkina/ShadowBox-Backend) · [Frontend](https://github.com/alexandra-seredkina/ShadowBox-Frontend)

### 🌐 [Personal site](https://personal-site-omega-six-53.vercel.app/) — built as a security exercise
Strict nonce-based CSP with `strict-dynamic`, HSTS preload, zero cookies, zero third-party scripts, a trilingual blog in MDX. CI runs Gitleaks, Semgrep, CodeQL, dependency review, and Playwright with axe for accessibility.<br>
<img src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=FF5C8A" alt="Next.js">
<img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=FF5C8A" alt="TypeScript">
<img src="https://img.shields.io/badge/Tailwind-0d1117?style=flat-square&logo=tailwindcss&logoColor=FF5C8A" alt="Tailwind CSS">
<img src="https://img.shields.io/badge/Playwright-0d1117?style=flat-square&logo=playwright&logoColor=FF5C8A" alt="Playwright">

### 🦀 [My-Own-TCP-IP](https://github.com/alexandra-seredkina/My-Own-TCP-IP) — a TCP/IP stack from scratch
A user-space TCP/IP stack in Rust (TUN/TAP, IP, ICMP, TCP), written by hand to understand how the network works under the hood. Every step is documented in the changelog.<br>
<img src="https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=FF5C8A" alt="Rust">
<img src="https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=FF5C8A" alt="Linux">

</td>
</tr>
</table>

<!-- Blog: add a link here once the posts have real content. -->

---

<table>
<tr>
<td width="50%" valign="top">

## 📊 Code

<div align="center">

<img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=alexandra-seredkina&amp;layout=compact&amp;hide_border=true&amp;langs_count=6&amp;bg_color=0d1117&amp;title_color=FF5C8A&amp;text_color=C9D1D9" alt="Top languages across public repositories">

</div>

</td>
<td width="50%" valign="top">

## ⚙️ Stack

**🔐 Application security**<br>
<img src="https://img.shields.io/badge/OWASP_Top_10-0d1117?style=flat-square&logo=owasp&logoColor=FF5C8A" alt="OWASP Top 10">
<img src="https://img.shields.io/badge/Burp_Suite-0d1117?style=flat-square&logo=burpsuite&logoColor=FF5C8A" alt="Burp Suite">
<img src="https://img.shields.io/badge/Semgrep-0d1117?style=flat-square&logo=semgrep&logoColor=FF5C8A" alt="Semgrep">
<img src="https://img.shields.io/badge/Secret_detection-0d1117?style=flat-square&logoColor=FF5C8A" alt="Secret detection">
<img src="https://img.shields.io/badge/SCA-0d1117?style=flat-square&logoColor=FF5C8A" alt="SCA">
<img src="https://img.shields.io/badge/JWT-0d1117?style=flat-square&logo=jsonwebtokens&logoColor=FF5C8A" alt="JWT">
<img src="https://img.shields.io/badge/OAuth-0d1117?style=flat-square&logoColor=FF5C8A" alt="OAuth">
<img src="https://img.shields.io/badge/Postman-0d1117?style=flat-square&logo=postman&logoColor=FF5C8A" alt="Postman">

**🗡 Offensive security**<br>
<img src="https://img.shields.io/badge/Kali_Linux-0d1117?style=flat-square&logo=kalilinux&logoColor=FF5C8A" alt="Kali Linux">
<img src="https://img.shields.io/badge/Metasploit-0d1117?style=flat-square&logo=metasploit&logoColor=FF5C8A" alt="Metasploit">
<img src="https://img.shields.io/badge/Wireshark-0d1117?style=flat-square&logo=wireshark&logoColor=FF5C8A" alt="Wireshark">
<img src="https://img.shields.io/badge/Nmap-0d1117?style=flat-square&logoColor=FF5C8A" alt="Nmap">
<img src="https://img.shields.io/badge/Active_Directory-0d1117?style=flat-square&logoColor=FF5C8A" alt="Active Directory">

**🚀 DevSecOps & infrastructure**<br>
<img src="https://img.shields.io/badge/GitLab_CI-0d1117?style=flat-square&logo=gitlab&logoColor=FF5C8A" alt="GitLab CI/CD">
<img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=FF5C8A" alt="Docker">
<img src="https://img.shields.io/badge/Nginx-0d1117?style=flat-square&logo=nginx&logoColor=FF5C8A" alt="Nginx">
<img src="https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=FF5C8A" alt="Linux">
<img src="https://img.shields.io/badge/Bash-0d1117?style=flat-square&logo=gnubash&logoColor=FF5C8A" alt="Bash">
<img src="https://img.shields.io/badge/Let's_Encrypt-0d1117?style=flat-square&logo=letsencrypt&logoColor=FF5C8A" alt="Let's Encrypt">

**💻 Software engineering**<br>
<img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=FF5C8A" alt="TypeScript">
<img src="https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=FF5C8A" alt="React">
<img src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=FF5C8A" alt="Next.js">
<img src="https://img.shields.io/badge/NestJS-0d1117?style=flat-square&logo=nestjs&logoColor=FF5C8A" alt="NestJS">
<img src="https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=FF5C8A" alt="Node.js">
<img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=FF5C8A" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=FF5C8A" alt="Python">
<img src="https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=FF5C8A" alt="Rust">

</td>
</tr>
</table>

---

## 🐾 TryHackMe

<table>
<tr>
<td valign="middle">

Hands-on practice almost every day: web exploitation, Active Directory, privilege escalation, and fresh CVE rooms.

<a href="https://tryhackme.com/p/Meowness"><img src="https://tryhackme-badges.s3.amazonaws.com/Meowness.png" alt="TryHackMe profile badge" height="120"></a>

</td>
<td width="260" valign="middle">

<img src="https://raw.githubusercontent.com/alexandra-seredkina/alexandra-seredkina/main/assets/ctfs.jpeg" alt="The character at her desk with glowing monitors, a sleeping black cat in headphones and a hologram flag with a checkmark" width="240">

</td>
</tr>
</table>

---

<div align="center">

<img src="https://raw.githubusercontent.com/alexandra-seredkina/alexandra-seredkina/main/assets/footer.jpeg" alt="Sunrise over the neon city: the character waves from a rooftop with her black cat in her lap" height="180">

*Think like an attacker. Build like a defender.*

**Let's make your app harder to break**

</div>
