# Issue 8895 — review screenshots

Captured from the actual development desktop at commit 0dad31fb, renderer http://localhost:3005 and debugging port 9335, signed into the disposable Local Admin environment.

These screenshots use a seeded local worktree-history fixture with real public PR metadata (#8933, #8926, #8924). The associations are test setup, not a claim that these PRs share a real worktree. Native input opened the menu in the workspace list and both sidebar layouts, closed it with Escape, and selected #8926. The selected PR then loaded in that workspace's real PR pane with its own repository, number, status, and GitHub URL.

GitHub discovery/pagination, association persistence, historical status refresh, unlink/archive races, and old-host fallback are verified separately by automated tests.

Screenshots contain only this disposable local environment and public GitHub PR information.
