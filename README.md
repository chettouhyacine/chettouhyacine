# Hi, I'm Yacine Chettouh 👋

**Full-stack developer I build offline-first business software for Algerian SMEs.**

Most small businesses here run on notebooks and Excel, on machines with no reliable
Internet. I build desktop tools that work with the network unplugged: local database,
local printing, local backups and no cloud bill.

---

### What I work with

`Rust` · `Tauri` · `TypeScript` · `React` · `Electron` · `Node.js` · `SQLite` ·
`Tailwind CSS` · `Vite` · `esbuild` · `Git`

### Featured projects

**[Showroom DZ](https://github.com/chettouhyacine/showroom-dz)** management app for
Algerian car showrooms: own and consigned stock, sales with installments and trade-ins,
consignment commissions, legal invoicing (PDF + Excel, French/Arabic), reports, roles and
audit log. 100 % offline, money stored in integer centimes, gap-free document numbering.

[![Showroom DZ dashboard](https://raw.githubusercontent.com/chettouhyacine/showroom-dz/main/docs/screenshots/tableau-de-bord.png)](https://github.com/chettouhyacine/showroom-dz)

**[Notaire DZ](https://github.com/chettouhyacine/notaire-dz)** practice software for an
Algerian notary office: clients, case files, encrypted document vault, hash chained audit
trail, encrypted backups. Rust core with AES-256-GCM records and an Argon2id derived key,
Tauri 2 shell, Arabic first interface with instant French switch. Per-user Windows
installer and a 13 page client guide in the repository.

[![Notaire DZ home screen](https://raw.githubusercontent.com/chettouhyacine/notaire-dz/main/docs/screenshots/home.png)](https://github.com/chettouhyacine/notaire-dz)

### How I build

- **Money and documents must be exact** integer arithmetic, no floating point, no
  numbering gaps, issued documents locked.
- **Offline first** everything works without Internet; backups are a `.zip` on a USB
  stick, not a cloud subscription.
- **Verify, don't assume** unit tests on the domain logic, end-to-end checks against the
  real services, and the app is only done when it runs on a fresh machine.

---

🌐 Portfolio: **[chettouhyacine.github.io](https://chettouhyacine.github.io/)**

📫 Reach me: **chettouhyacine2001@gmail.com**
