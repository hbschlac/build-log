# Build Log

A running log of things I've shipped, built, and figured out. I'm a PM who builds with Claude Code — no CS degree.

Each entry is a thing that either went live, got fixed, or got learned.

---

## 2026
**Apr 01** — `interior-designer-portfolio`: Fix repair endpoint to detect /hz-* and /img-* absolute-path broken URLs
**Apr 01** — `interior-designer-portfolio`: Allow /api/admin/* through auth middleware (routes have own Bearer auth)
**Apr 01** — `interior-designer-portfolio`: Migrate image storage to Cloudflare R2 + add KV repair endpoint
**Apr 01** — `interior-designer-portfolio`: Rebuild v3 shortcuts: remove bad getimages action, loop over Shortcut Input directly
**Apr 01** — `interior-designer-portfolio`: Allow v3 shortcut files through auth middleware
**Apr 01** — `interior-designer-portfolio`: Add signed v3 iOS shortcuts (iOS 18 multi-image fix)
**Mar 31** — `interior-designer-portfolio`: Replace paginated "Show more" with infinite scroll in texture library
**Mar 31** — `interior-designer-portfolio`: Remove 16 non-texture images and add curation scripts
**Mar 31** — `interior-designer-portfolio`: Add missing files for Vercel build (useIsMobile, texture library updates)
**Mar 31** — `interior-designer-portfolio`: Trigger Vercel redeploy for shortcut-save endpoint
**Mar 31** — `interior-designer-portfolio`: Roadmap: double-click detail modal, description field, search bar, priority sort, room input fix
**Mar 31** — `interior-designer-portfolio`: Rebrand color palette to match Hannah's selected colors
**Mar 31** — `interior-designer-portfolio`: Fix upload UX: video warning, partial-batch recovery, bulk delete
**Mar 30** — `interior-designer-portfolio`: Add 443-texture library with browsing modal and Pexels images
**Mar 30** — `interior-designer-portfolio`: Add debug logging to /api/save for shortcut troubleshooting
**Mar 30** — `interior-designer-portfolio`: Include verified:true in skipped responses for shortcut compatibility
**Mar 29** — `interior-designer-portfolio`: Add MaterialSwatch type to lib/types.ts (fixes build)
**Mar 29** — `interior-designer-portfolio`: Fix spanning card click + drag-drop interaction
**Mar 29** — `interior-designer-portfolio`: Fix drag-and-drop onto months covered by spanning milestones
**Mar 29** — `interior-designer-portfolio`: Allow typing custom room names in roadmap milestone popout
**Mar 29** — `interior-designer-portfolio`: Rewrite shortcut notification logic: default to FAILED, require proof
**Mar 29** — `interior-designer-portfolio`: Wire up Materials & Textures mood board on designer brief page
**Mar 29** — `interior-designer-portfolio`: Fix login page logo missed in terracotta rebrand
**Mar 29** — `interior-designer-portfolio`: Add Vercel protection bypass header to iOS shortcut docs
**Mar 29** — `interior-designer-portfolio`: Fix roadmap milestone spanning: left/right resize, no overlap, no cap
**Mar 29** — `interior-designer-portfolio`: Add Open Graph metadata for shared image links
**Mar 29** — `interior-designer-portfolio`: Fix modal not closing due to stale closure in patchImage
**Mar 29** — `interior-designer-portfolio`: Add house emoji favicon
**Mar 29** — `interior-designer-portfolio`: Rebrand from sage green to warm terracotta/walnut palette
**Mar 29** — `interior-designer-portfolio`: Fix DesignerBriefClient build error: add missing onImageClick prop
**Mar 29** — `interior-designer-portfolio`: Bulletproof save verification: server reads back KV + checks blob before returning success
**Mar 29** — `interior-designer-portfolio`: Make G logo more dynamic with richer gradient and depth
**Mar 29** — `interior-designer-portfolio`: Make Start Here banner bold navy with terracotta designer badge
**Mar 29** — `interior-designer-portfolio`: Current Home photos page, floor plan sidebar integration, gallery UX improvements
**Mar 29** — `interior-designer-portfolio`: Feature round 4: multi-select filters, source URL, roadmap spanning, floor plan improvements
**Mar 29** — `interior-designer-portfolio`: Add milestone groups/clusters (Feature 3)
**Mar 29** — `interior-designer-portfolio`: Roadmap & Table: 9 new features
**Mar 29** — `muse-shopping`: fix: correct BrandLogo props on brands slug page
**Mar 29** — `interior-designer-portfolio`: Table: sticky headers/cols, resizable widths, Stack Rank; Roadmap: priority badge label
**Mar 29** — `libby-hold-monitor`: security: remove hardcoded Google API key from render.yaml

**Mar 29** — Overhauled GitHub profile: profile README, bio, pins, private contributions enabled, `libby-hold-monitor` made public
**Mar 29** — `muse-shopping`: Gmail API receipt parsing live — every order cross-retailer now makes next recommendation smarter
**Mar 26** — Interior design portfolio site live on Vercel with image gallery, annotation system, and priorities tracker
**Mar 24** — Built interior designer AI backend: StyleProfile KV storage + Claude Code skill for room recommendations and concept boards
**Mar** — `muse-shopping` hit 264 brands, 10 retailers, 120 API endpoints, 43 automated tests — all solo, running in production

---

*Updated as things ship.*