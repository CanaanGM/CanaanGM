## Greetings and welcome ~!

I'm Kanaan, a Human existing on earth who's into computer wizardry.

this is a place where i keep experiments and fun things i work on, feel free to look around ~!  

---

### ⚔️ Things I built that have a number attached

**API quota governance, twice.** Redis with Lua scripts doing atomic per-company counting across 11+ endpoints, then torn down and rebuilt as a configurable service-category × time-period model. Progressive alerts at 70 / 85 / 95 / 100%, with Hangfire-driven deduplication so one bad afternoon doesn't page anyone four hundred times.

**Two breaking-change API migrations, zero broken integrations.** Field renames, data type changes, deprecated attributes removed, request bodies restructured — across the externally exposed surface. Every integrated insurance company survived. This is the one I'm smug about.

**Monthly credit note generation, whole vertical slice.** Migrations and stored procedures, PDF generation, Hangfire orchestration with write-back, finance reporting with transaction-level drill-down, and tests covering eligibility, aggregation, numbering, and the failure paths nobody writes tests for.

**PriceMonitor** *(@ Equiti)*. Real-time FX pricing alerts over SignalR and MassTransit/RabbitMQ — ingesting live MT4 and PXM feeds, matching configurable thresholds, fanning out to concurrent trader sessions.

**A gRPC service wrapping MetaTrader 5** *(@ Equiti)*. 10+ RPC endpoints for positions, orders, deals and trade history. Docker, Kubernetes, Helm, Azure DevOps.

**A home server that has survived me.** 15+ self-hosted services on Docker Compose, NVIDIA GPU passthrough, Tailscale, LVM, automated drive mounting. Jellyfin and Immich are the load-bearing ones.

---

### 🧰 Tools of the trade

`C#` · `ASP.NET Core` · `EF Core` · `SQL Server` · `Redis` · `Hangfire` · `RabbitMQ` · `gRPC` · `Docker` · `Kubernetes` · `Python` · `Rust` · `Astro` · `Linux`

---

### 📜 Where the actual writing lives

**[kanaan.dev](https://kanaan.dev)** is my spot ont the internet, feel free to look around


---

<sub>Currently learning: Rust, maths, and how to stop starting new repositories. Progress on the third is disputed. (⊙_⊙)？</sub>

<sub><a href="https://kanaan.dev">kanaan.dev</a> · <a href="https://www.linkedin.com/in/canaangm">LinkedIn</a> · canaand1@gmail.com</sub>
