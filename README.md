# HitCheck

A full-stack web app where users check whether points on the plane hit a composite area and keep a
history of their attempts. This repository ties the parts together as git submodules.

<img src="https://github.com/foliageh/itmo-web-lab4/assets/46216950/7900419f-3e09-47db-b441-61c95821d755" alt="HitCheck main page" width="800"><br>
<img src="https://github.com/foliageh/itmo-web-lab4/assets/46216950/2bd81da9-3928-4270-bc42-c5a75a252ee5" alt="HitCheck login page" width="800">

| Part | Stack |
|---|---|
| [hitcheck-web](https://github.com/foliageh/hitcheck-web) | Angular 17, TypeScript, RxJS, PrimeNG |
| [hitcheck-api](https://github.com/foliageh/hitcheck-api) | Spring Boot 3, Spring Security 6, JWT, JPA, PostgreSQL |
| [hitcheck-api-jakarta](https://github.com/foliageh/hitcheck-api-jakarta) | Jakarta EE 10, JAX-RS, EJB, WildFly Elytron with JWT, PostgreSQL |

Both backends expose the same API, so the frontend runs on either of them.

```bash
git clone --recurse-submodules https://github.com/foliageh/hitcheck
```

---
Built as coursework for the Web Programming course at ITMO University, 2023–2024.
