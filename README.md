<div align="center">

# Camilo Ibañez

**Full-stack developer.** Java and Spring Boot on the back, React on the front.

Colombia · [camilopastrana41@gmail.com](mailto:camilopastrana41@gmail.com) · [readmarginalia.net](https://readmarginalia.net)

</div>

<br>

I build full-stack web applications and ensure they run smoothly in production. I care deeply about the details you can’t see in a screenshot: robust security, clean architecture, automated testing, and seamless database management.

<br>

## Featured work

### Marginalia

A literary publishing platform for Spanish-language writing, live at [readmarginalia.net](https://readmarginalia.net). Readers get a public site built around careful reading; writers get a role-gated panel with a rich-text editor, a draft/publish workflow, and moderation. Designed, built, deployed, and operated by me.

<table>
  <tr>
    <td width="190" valign="top">
      <a href="https://github.com/IbanezCamilo/marginalia-api"><b>marginalia-api</b></a>
      <br><sub>Java 21 · Spring Boot 3.5 · PostgreSQL</sub>
    </td>
    <td valign="top">
      REST API covering the full post lifecycle: accounts, publishing, moderation queue, and admin management over a five-level role hierarchy. Stateless auth with short-lived JWTs in HttpOnly cookies and refresh-token rotation, per-IP rate limiting, email verification, account lockout, and OWASP HTML sanitization. Flyway migrations, 59 test classes, CI on every push.
    </td>
  </tr>
  <tr>
    <td width="190" valign="top">
      <a href="https://github.com/IbanezCamilo/marginalia-web"><b>marginalia-web</b></a>
      <br><sub>React 19 · Vite · Tailwind CSS 4</sub>
    </td>
    <td valign="top">
      Public reading site plus the authoring and admin panel. Feature-based architecture with a consistent service/hook data layer, a TipTap editor persisting ProseMirror JSON, optimistic status updates, and light/dark themes designed with equal intention. Tested with Vitest and Testing Library.
    </td>
  </tr>
</table>

## Stack

<table>
  <tr>
    <td width="190"><b>Backend</b></td>
    <td>Java 21, Spring Boot 3, Spring Security, PostgreSQL, JPA/Hibernate, Flyway</td>
  </tr>
  <tr>
    <td width="190"><b>Frontend</b></td>
    <td>React 19, Vite, Tailwind CSS 4, React Router 7, TipTap</td>
  </tr>
  <tr>
    <td width="190"><b>Operations</b></td>
    <td>Docker, GitHub Actions, Cloudflare R2, JUnit, Vitest</td>
  </tr>
</table>

<br>

<div align="center">
  <sub>Ship it, then improve it · <a href="mailto:camilopastrana41@gmail.com">camilopastrana41@gmail.com</a></sub>
</div>
