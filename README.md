<img src="./assets/header.svg" alt="RUPAM spelled out in a GitHub contribution graph" width="100%" />

<p align="center">
  <a href="https://github.com/iamrupambiswas">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=Full-Stack+Java+Developer+%40+Bangalore;Spring+Boot+%C2%B7+Next.js+%C2%B7+AWS;Payments+that+never+double-charge;Queues+that+never+lose+a+message;Building+Sentinel+AML+in+public" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.iamrupambiswas.com"><img src="https://img.shields.io/badge/portfolio-iamrupambiswas.com-58a6ff?style=flat-square&labelColor=161b22" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/iamrupambiswas"><img src="https://img.shields.io/badge/linkedin-iamrupambiswas-58a6ff?style=flat-square&labelColor=161b22" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/iamrupambiswas"><img src="https://img.shields.io/badge/leetcode-400%2B_solved-f0883e?style=flat-square&labelColor=161b22&logo=leetcode&logoColor=f0883e" alt="LeetCode" /></a>
  <a href="mailto:rupambiswas953@gmail.com"><img src="https://img.shields.io/badge/mail-rupambiswas953%40gmail.com-3fb950?style=flat-square&labelColor=161b22&logo=gmail&logoColor=3fb950" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=iamrupambiswas&label=profile%20views&color=58a6ff&style=flat-square&labelColor=161b22" alt="Profile views" />
</p>

<br/>

```java
@Developer
public class RupamBiswas implements FullStack, OnCall {

    private final String role     = "Full-Stack Developer @ Asego Global Assistance";
    private final String location = "Bangalore, India 🇮🇳";
    private final String domain   = "travel insurance, claims & payments";

    private final List<String> daily = List.of(
        "Java 21", "Spring Boot 3", "Next.js", "React", "Redis", "ActiveMQ", "AWS");

    @Override
    public String currentlyBuilding() {
        return "Sentinel AML — real-time anti-money-laundering, built in public";
    }

    @Override
    public List<String> askMeAbout() {
        return List.of("idempotent payments", "rate limiting with Redis + Lua",
                       "event-driven microservices", "CI/CD that ships on a Friday");
    }

    @Retryable(maxAttempts = Integer.MAX_VALUE)
    public void learn() { /* 400+ DSA problems and counting */ }
}
```

## 🗺️ &nbsp;Shipped to prod

<sub>Issues I've closed at work — the open ones are next.</sub>

- [x] Scaled a partner's consumer insurance portal to **10x daily customers**
- [x] Migrated a live production portal with **zero downtime**
- [x] **Idempotent payment workflows** + reconciliation that issues a policy for every successful payment
- [x] IP-based **API rate limiting** with Redis + atomic Lua scripts, guarding public endpoints in prod
- [x] Event-driven integrations on **ActiveMQ + Spring JMS**, partner APIs secured with encryption & signed requests
- [x] Sales-analytics microservices with **AI summaries from Gemini**
- [ ] Sentinel AML · Phase 7 — analyst console with live alerts
- [ ] Kubernetes all the things

## 📌 &nbsp;Featured repositories

<p align="center">
  <a href="https://github.com/iamrupambiswas/sentinel-aml"><img src="https://github-readme-stats.vercel.app/api/pin/?username=iamrupambiswas&repo=sentinel-aml&theme=github_dark&hide_border=true&bg_color=161b22&description_lines_count=2" alt="sentinel-aml" width="49%" /></a>
  <a href="https://github.com/iamrupambiswas/Project-Management-Tool"><img src="https://github-readme-stats.vercel.app/api/pin/?username=iamrupambiswas&repo=Project-Management-Tool&theme=github_dark&hide_border=true&bg_color=161b22&description_lines_count=2" alt="Project-Management-Tool" width="49%" /></a>
  <a href="https://github.com/iamrupambiswas/Doctor-Apointment-Booking"><img src="https://github-readme-stats.vercel.app/api/pin/?username=iamrupambiswas&repo=Doctor-Apointment-Booking&theme=github_dark&hide_border=true&bg_color=161b22&description_lines_count=2" alt="Doctor-Appointment-Booking" width="49%" /></a>
  <a href="https://github.com/iamrupambiswas/Rate-Limiter-Practice"><img src="https://github-readme-stats.vercel.app/api/pin/?username=iamrupambiswas&repo=Rate-Limiter-Practice&theme=github_dark&hide_border=true&bg_color=161b22&description_lines_count=2" alt="Rate-Limiter-Practice" width="49%" /></a>
</p>

<details>
<summary><b>🔍 &nbsp;Inside Sentinel AML</b> — the side project with a commit history worth reading</summary>
<br/>

A cloud-native, event-driven AML platform that scores transactions in under a second, instead of the 48–72 hours a spreadsheet review takes.

```diff
+ p6  Keycloak auth · JWT checked at the gateway AND in every service · deny-by-default roles
+ p5  Race-free alert de-dup · live rule tuning in 45 ms over an ActiveMQ topic · DLQ replay
+ p4  Detection engine · 6 AML typologies · Redis + Lua sliding windows · ~19 ms per txn
+ p3  Hardened Spring Batch ingestion · skip listeners · crash reconciliation on boot
+ p2  AES-encrypted PII · multi-module Maven + BOM · MDC trace IDs · Flyway per service
+ p1  System design · bounded contexts · database-per-service
! p7  next → analyst console, server-side login, alerts that arrive live
```

`Java 21` `Spring Boot 3` `Spring Cloud` `Spring Batch` `ActiveMQ Artemis` `Redis` `MySQL` `Keycloak` `Next.js` `Terraform` `AWS`

</details>

## 🧰 &nbsp;Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,hibernate,kafka,redis,mysql,postgres,mongodb,graphql&theme=dark" alt="Backend" /><br/>
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,tailwind,materialui,nodejs,express&theme=dark" alt="Frontend" /><br/>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,jenkins,githubactions,gitlab,linux,grafana,prometheus&theme=dark" alt="Cloud and DevOps" /><br/>
  <img src="https://skillicons.dev/icons?i=git,maven,gradle,postman,python,bash,idea,vscode&theme=dark" alt="Tools" />
</p>

## 📊 &nbsp;git stats --me

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=iamrupambiswas&show_icons=true&theme=github_dark&hide_border=true&bg_color=161b22&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iamrupambiswas&layout=compact&theme=github_dark&hide_border=true&bg_color=161b22&langs_count=8" alt="Top languages" height="170" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=iamrupambiswas&theme=github-dark-blue&hide_border=true&background=161B22" alt="Commit streak" height="170" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=iamrupambiswas&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=3fb950&point=e6edf3&area=true&area_color=238636" alt="Contribution activity graph" width="100%" />
</p>

---

<p align="center">
  <sub>
    <code>git push origin main</code> on weekdays · <code>git push --force</code> never ·
    open to full-stack &amp; backend Java roles → <a href="mailto:rupambiswas953@gmail.com">say hi</a>
  </sub>
</p>
