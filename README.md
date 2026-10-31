# Rafael Pérez

## *"No token, no passage."*

**I build identity infrastructure in .NET.**
Shipping .NET since 2015 · Mechatronics engineer · Mexico City · **Open to .NET engineering roles**

---

## 🛡️ RufistoWard — the open-source IdentityServer4 replacement

[![OIDF conformance: Basic OP](https://img.shields.io/badge/OIDF%20conformance-Basic%20OP%20passing-brightgreen)](https://www.certification.openid.net/plan-detail.html?plan=ZyytN9FAD5ZeJ&public=true)
[![OIDF conformance: Config OP](https://img.shields.io/badge/OIDF%20conformance-Config%20OP%20passing-brightgreen)](https://www.certification.openid.net/plan-detail.html?plan=Rc7CUe5MQqD0P&public=true)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue)](https://www.gnu.org/licenses/agpl-3.0)

OAuth 2.0 / OpenID Connect identity server on **.NET 10**. Duende priced IdentityServer out of reach and IdentityServer4 went end-of-life — so I built the replacement, and every flow is free.

- **OpenID Foundation conformance suite — Basic OP and Config OP plans published and passing** (links above, verify them yourself)
- **Every OIDC / OAuth2 flow** — Authorization Code + PKCE, Client Credentials, Refresh Token, Device Code (RFC 8628), Revocation (RFC 7009), Introspection (RFC 7662), Discovery + JWKS
- **Admin UI included** — Tailwind CSS v4 + HTMX, no JavaScript framework
- **IdentityServer4 migration tooling** — built by someone who has migrated production instances
- 225 tests · Clean Architecture · PostgreSQL and SQL Server · AGPL-3.0 + commercial

**→ [github.com/RufistofelesDev/RufistoWard](https://github.com/RufistofelesDev/RufistoWard)**

---

## 🏭 Aspire.Hosting.OpcUa — a factory floor in your Aspire dashboard

[![NuGet](https://img.shields.io/nuget/v/Rufistofeles.Aspire.Hosting.OpcUa)](https://www.nuget.org/packages/Rufistofeles.Aspire.Hosting.OpcUa)

A live OPC UA server in your .NET Aspire app model. One line, no PLC required — so industrial clients can be tested in CI without a factory.

```csharp
builder.AddOpcUaPlc("plc");
```

- Wraps Microsoft's `opc-plc` simulator, image tag pinned so an upstream release can't change your test results
- Verified end to end against a running container before 1.0.0 shipped
- AGPL-3.0 + commercial

**→ [github.com/RufistofelesDev/Aspire.Hosting.OpcUa](https://github.com/RufistofelesDev/Aspire.Hosting.OpcUa)**

---

## Not a side project

I've been doing this professionally since 2015:

- **Single sign-on in production since 2019** — Azure AD and OpenID Connect across web and desktop apps. RufistoWard is that work, generalised and given away.
- **Warehouse robots, 2015–2017** — control systems for Layer Picker robots, Put-to-Light and AGVs, integrated into WMS Manhattan and SAP. Running on a real floor.
- **Enterprise integration** — SOAP and REST into SAP; Mexican CFDI v3.3 and v4 electronic invoicing, built twice at two companies.

## Where this comes from

I'm a mechatronics engineer who writes C#. That isn't two careers — it's one.

My first real system controlled the lights in my mother's house over the electrical wiring, because she has knee osteoarthritis and the switch was across the room. Every project since has been the same problem at a larger scale: **get a signal through a channel that wasn't built for it, and prove on the other side that it arrived intact.** Lights over the mains. Machines over OPC UA. Now tokens over HTTP.

---

## Stack

`.NET 10` · `C#` · `ASP.NET Core` · `OAuth 2.0 / OIDC` · `Entity Framework Core` · `Clean Architecture` · `.NET Aspire` · `PostgreSQL` · `SQL Server` · `Docker` · `OPC UA` · `Tailwind` · `HTMX`

---

**Open to .NET engineering roles.**
📫 [rafael@rufistofeles.dev](mailto:rafael@rufistofeles.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/rufistofeles) · 🌐 [rufistofeles.dev](https://rufistofeles.dev)
