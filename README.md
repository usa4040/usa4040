<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Hoharu%20Iwata&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Web%20Engineer%20%C2%B7%20AI-Driven%20Development&descAlignY=58&descSize=18&animation=fadeIn" alt="Hoharu Iwata header" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/usa4040">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=620&lines=Building+web+apps+end+to+end;Cursor+builds+%E2%86%92+Codex+reviews+%E2%86%92+Playwright+verifies;Hono+%C3%97+Cloudflare+Workers+%C3%97+React;Shipping+small%2C+shipping+often" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based%20in-Japan-BC002D?style=flat-square" alt="Based in Japan" />
  <img src="https://img.shields.io/badge/Web%20Engineer-~3%20years-0EA5E9?style=flat-square" alt="Web Engineer ~3 years" />
  <img src="https://img.shields.io/badge/Focus-AI--Driven%20Dev-8B5CF6?style=flat-square" alt="Focus AI-Driven Development" />
</p>

---

## About Me

**岩田 穂治（Hoharu Iwata）** です。日本で Web エンジニアをしています（経験 約3年）。

- PHP（素の PHP + Smarty / Laravel）から TypeScript（Vue / React）まで、サーバーサイドもフロントも書きます
- MySQL・PostgreSQL・DynamoDB を扱い、kintone のカスタマイズやシェル / PHP のバッチ処理も担当
- 職場では GitHub Copilot を使った **AI 駆動開発の導入をリード**
- 個人では要件定義からデプロイまで一人で回し、リリース後も改善を続けるのが好きです

> *A Japan-based web engineer who designs, builds, and ships full-stack apps with an AI-assisted workflow.*

---

## How I Build — AI-Driven Workflow

実装は **Cursor**、コードレビューは **Codex**、品質の最後の砦は **Playwright の E2E テスト**。
AI に書かせて、別の AI に見てもらい、テストで確かめる。この流れを個人開発でも回しています。

```mermaid
flowchart LR
    A["要件・設計<br/>Requirements"] --> B["実装<br/>Cursor"]
    B --> C["コードレビュー<br/>Codex"]
    C -->|指摘を反映| B
    C --> D["E2E テスト<br/>Playwright"]
    D -->|失敗したら戻す| B
    D --> E["デプロイ<br/>Cloudflare"]
```

<p>
  <img src="https://img.shields.io/badge/Cursor-implementation-111111?style=for-the-badge&logo=cursor&logoColor=white" alt="Cursor" />
  <img src="https://img.shields.io/badge/Codex-code%20review-412991?style=for-the-badge" alt="Codex" />
  <img src="https://img.shields.io/badge/GitHub%20Copilot-team%20adoption-000000?style=for-the-badge&logo=githubcopilot&logoColor=white" alt="GitHub Copilot" />
  <img src="https://img.shields.io/badge/Playwright-E2E-2EAD33?style=for-the-badge" alt="Playwright" />
</p>

---

## Tech Stack

**Languages**

<p>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=ts,php,python,rust,bash&perline=10" alt="Languages" /></a>
</p>

**Frontend / Backend**

<p>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=react,vue,laravel&perline=10" alt="Frameworks" /></a>
  <img src="https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white" alt="Hono" height="48" />
  <img src="https://img.shields.io/badge/Smarty-F0C040?style=for-the-badge&logoColor=black" alt="Smarty" height="48" />
</p>

**Database / ORM**

<p>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=postgres,mysql,dynamodb&perline=10" alt="Databases" /></a>
  <img src="https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black" alt="Neon" height="48" />
  <img src="https://img.shields.io/badge/Drizzle%20ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black" alt="Drizzle ORM" height="48" />
</p>

**Cloud / Tools**

<p>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=cloudflare,workers,aws,git,github&perline=10" alt="Cloud and tools" /></a>
  <img src="https://img.shields.io/badge/kintone-customize-FFC107?style=for-the-badge" alt="kintone" height="48" />
</p>

---

## Featured Works

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>NAP — 人材派遣業向け業務システム</h3>
      <p>派遣業務の <b>シフト管理・勤怠・見積・請求書</b> をひとつにまとめた Web システム。要件定義から設計・実装・テスト・デプロイまで一人で担当し、現在も機能追加を継続中（副業・非公開）。</p>
      <p>
        <img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white" alt="Hono" />
        <img src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" />
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
        <img src="https://img.shields.io/badge/PostgreSQL%20(Neon)-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL on Neon" />
        <img src="https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black" alt="Drizzle" />
        <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square" alt="Playwright" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Tokyo Side Trips</h3>
      <p>訪日旅行者向けの英語トラベルガイド。鎌倉・江ノ島・箱根・横浜など、東京からの日帰り／一泊旅行を紹介しています。サイトの運営は <b>AI エージェントと一緒に回している</b> プロジェクト。</p>
      <p>
        <a href="https://tokyosidetrips.com"><img src="https://img.shields.io/badge/Visit-tokyosidetrips.com-0EA5E9?style=flat-square&logo=googlechrome&logoColor=white" alt="Visit tokyosidetrips.com" /></a>
        <img src="https://img.shields.io/badge/Run%20with-AI%20Agents-8B5CF6?style=flat-square" alt="Run with AI agents" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>pet-post</h3>
      <p>ペットの写真を毎日交換し合うアプリ。Cloudflare Workers 上で動かしています（非公開）。</p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>smart-mock</h3>
      <p>OpenAPI・TypeScript・JSON スキーマから立ち上がる、コンテキストを考慮したローカル Mock API サーバー。Rust 製。</p>
      <p>
        <a href="https://github.com/usa4040/smart-mock"><img src="https://img.shields.io/badge/Repo-smart--mock-181717?style=flat-square&logo=github&logoColor=white" alt="smart-mock repository" /></a>
        <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
      </p>
    </td>
  </tr>
</table>

---

## Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=usa4040&theme=tokyonight&hide_border=true&date_format=Y%2Fn%2Fj" alt="GitHub contribution streak" />
</p>

---

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="footer" width="100%" />
</p>
