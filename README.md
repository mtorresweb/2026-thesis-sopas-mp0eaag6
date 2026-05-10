# Sopas

> **Tesis de Grado** · Ingeniería y Tecnología · 2026

## Resumen

[@octokit/request] "POST https://api.github.com/user/repos" is deprecated. It is scheduled to be removed on Fri, 10 Mar 2028 00:00:00 GMT. See https://docs.github.com/en/rest/about-the-rest-api/api-versions
⨯ Error: Transactions are not supported in HTTP mode
    at async createProject (app/actions/projects.ts:148:19)
  146 |
  147 |   // ── Prisma: save project ──────────────────────────────────────────────────
> 148 |   const project = await prisma.project.create({
      |                   ^
  149 |     data: {
  150 |       title,
  151 |       abstract, {
  clientVersion: '7.8.0',
  digest: '789667693'
}
 POST /projects/new 500 in 8.9s (next.js: 4ms, proxy.ts: 15ms, application-code: 8.9s)
  └─ ƒ createProject({}, {}) in 8668ms app/actions/projects.ts
[browser] Uncaught Error: Transactions are not supported in HTTP mode

## Autores

- Michael Torres

## Palabras clave

sopas, melas

## Licencia

CC BY 4.0

---

*Proyecto publicado en [UniHaven](https://unihaven.vercel.app) — Repositorio Académico de la Universidad Popular del Cesar.*
