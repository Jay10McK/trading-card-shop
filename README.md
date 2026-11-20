- I'm developing a trading card shop site where customers can register for shop events & purchase cards and other products. Staff will be able to manage inventory (with transactional checkout so the last copy of a card can never be sold twice.) & manage events.

- Development Stack: Next.js + TypeScript, ASP.NET Core API,
  PostgreSQL + EF Core, Azure, Docker + GitHub Actions, Stripe test mode

- Run Locally:
-   `docker compose up --build`
    'http://localhost:8080/health' - returns "Okay"
    'http://localhost:3000' - displays Next.js starter page
  
- Note: fictional shop and fictional cards only; Stripe test mode only, no
  real payments; no real customer data.
