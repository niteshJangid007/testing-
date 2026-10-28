# AccessLab — Broken Access Control Playground

A local, browser-only educational simulation of an OWASP Broken Access Control scenario.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Choose Alice as the signed-in demo user.
4. Request Bob's profile in **Vulnerable mode**.
5. Switch to **Secure mode** and request Bob's profile again.

## What it demonstrates
- Horizontal access-control failure: user A can view user B's demo record.
- A secure authorization decision based on record ownership or an administrator role.
- Simulated HTTP 200 vs 403 outcomes and an authorization trace.

## Safety and limitations
- All names and data are fictional test values.
- This is a client-side simulation, not a real vulnerable server or a real authentication system.
- Do not use client-side JavaScript checks as production security. Real authorization must be enforced on the backend on every request.
