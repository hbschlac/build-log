# Build Log

A running log of things I've shipped, built, and figured out. I'm a PM who builds with Claude Code — no CS degree.

Each entry is a thing that either went live, got fixed, or got learned.

---

## 2026
**Apr 06** — `interior-designer-portfolio`: Add demo read-only login for Airtable application showcase
**Apr 06** — `interior-designer-portfolio`: chore: redeploy to pick up RESEND_API_KEY env var
**Apr 06** — `interior-designer-portfolio`: feat: admin dashboard with Account Access + Bug Reports tabs
**Apr 05** — `interior-designer-portfolio`: feat: journal note image + tag UX improvements
**Apr 05** — `interior-designer-portfolio`: fix: show error toast if notification fails + add notify logging
**Apr 05** — `interior-designer-portfolio`: fix: sticky toolbar + auto notify banner
**Apr 05** — `interior-designer-portfolio`: feat: Notes reliability + UX improvements
**Apr 05** — `interior-designer-portfolio`: Remove wrapper drag handlers that caused re-render jank during pan
**Apr 05** — `interior-designer-portfolio`: Fix photo drag-drop onto floor plan: always attach drag handlers on SVG rects
**Apr 05** — `interior-designer-portfolio`: Resolve merge conflict, keep upstream DesignerBriefClient
**Apr 05** — `interior-designer-portfolio`: feat: drag-to-reorder tiles on Digital Mood Board
**Apr 05** — `interior-designer-portfolio`: feat: Digital Mood Board + drag & drop upload
**Apr 05** — `interior-designer-portfolio`: Fix double NavBar when CurrentHomeClient is embedded in Floor Plan tab
**Apr 05** — `interior-designer-portfolio`: fix: persistent toolbar + notify button
**Apr 05** — `interior-designer-portfolio`: Add /api/bug-report route to persist bug reports to KV
**Apr 05** — `interior-designer-portfolio`: feat: manual notification banner + Giddins Interior Design FROM name
**Apr 05** — `interior-designer-portfolio`: fix: use schlacter.me as Resend FROM address for journal notifications
**Apr 05** — `interior-designer-portfolio`: fix: use giddins.family FROM address for journal notify emails
**Apr 05** — `interior-designer-portfolio`: feat: admin page for managing designer accounts
**Apr 05** — `interior-designer-portfolio`: feat: Escape key resets floor plan zoom to normal
**Apr 05** — `interior-designer-portfolio`: fix: journal mention popover and auto-list bugs
**Apr 05** — `interior-designer-portfolio`: debug: show full image URLs in floorplan migration endpoint
**Apr 05** — `interior-designer-portfolio`: fix: broaden floor plan migration to catch all non-R2 image URLs + add debug output
**Apr 05** — `interior-designer-portfolio`: fix: replace Cormorant Garamond with Poppins in BugReportButton
**Apr 05** — `interior-designer-portfolio`: Fix TypeScript type error: explicitly type journal author to exclude designer
**Apr 05** — `interior-designer-portfolio`: feat: journal editor enhancements — strikethrough, tooltips, colors, mentions, stars, attachments, guest tagging
**Apr 05** — `interior-designer-portfolio`: fix: commit missing auth.ts additions (designer accounts + share tokens)
**Apr 05** — `interior-designer-portfolio`: feat: fix floor plan image cropping + add zoom/pan controls
**Apr 05** — `interior-designer-portfolio`: restore: re-add BugReportButton component (deleted by other session)
**Apr 05** — `interior-designer-portfolio`: restore: re-apply bug-fixer types, KV key, middleware, and layout
**Apr 05** — `interior-designer-portfolio`: fix: migrate gallery upload to use Cloudflare R2 (same as rest of app)
**Apr 05** — `interior-designer-portfolio`: Remove Stack Rank column and smart rank legend from priorities table
**Apr 05** — `interior-designer-portfolio`: feat: add zoom + pan to image detail modal
**Apr 05** — `interior-designer-portfolio`: Fix tag persistence race condition on modal close
**Apr 04** — `interior-designer-portfolio`: Fix missing filterOwner state declaration in RoadmapView
**Apr 04** — `interior-designer-portfolio`: Fix data loss bugs, broken roadmap features, and journal UX overhaul
**Apr 04** — `interior-designer-portfolio`: feat: add calmar-bug-fixer skill + in-site bug report form
**Apr 03** — `interior-designer-portfolio`: Wrap useSearchParams in Suspense boundary (fix build error)
**Apr 03** — `interior-designer-portfolio`: Switch to static manifest.json with share_target support
**Apr 03** — `interior-designer-portfolio`: Add PWA share target for iOS share sheet photo upload
**Apr 03** — `interior-designer-portfolio`: Sign SavePhotos shortcut files for iOS import
**Apr 03** — `interior-designer-portfolio`: Add SavePhotos shortcut files for Hannah and Sam
**Apr 03** — `interior-designer-portfolio`: Add .shortcut files, /upload, /install to public paths
**Apr 02** — `interior-designer-portfolio`: Default to Hannah's token when no auth context available
**Apr 02** — `interior-designer-portfolio`: Rewrite install page with Copy to Clipboard approach
**Apr 02** — `interior-designer-portfolio`: Inline .scriptable content in API route (fix Vercel fs access)
**Apr 02** — `interior-designer-portfolio`: Serve .scriptable via API route with download headers
**Apr 02** — `interior-designer-portfolio`: Switch to .scriptable file import (fixes blank script on import)
**Apr 02** — `interior-designer-portfolio`: Minify Scriptable script URL — fix blank page on import
**Apr 02** — `interior-designer-portfolio`: Add Scriptable-based Share Sheet setup + mobile upload page
**Apr 02** — `interior-designer-portfolio`: Add v13 — hand-written XML, plutil binary, Form body + file field
**Apr 02** — `interior-designer-portfolio`: Add purge-broken-r2 admin endpoint to remove unrecoverable broken R2 images
**Apr 02** — `interior-designer-portfolio`: Add repair-from-source admin endpoint to re-download broken R2 images from their sourceUrl
**Apr 02** — `interior-designer-portfolio`: Add v12c/v12d — plutil round-trip (no Python plistlib)
**Apr 02** — `interior-designer-portfolio`: Add debug-urls admin endpoint for R2 URL diagnostics
**Apr 02** — `interior-designer-portfolio`: Add v12 shortcuts — surgical modification of real wflow
**Apr 02** — `interior-designer-portfolio`: restore-and-remigrate: add debug size check output
**Apr 02** — `interior-designer-portfolio`: fix: add HEAD size check to skip already-remigrated images
**Apr 01** — `interior-designer-portfolio`: restore-and-remigrate: match by blob existence, not file size
**Apr 01** — `interior-designer-portfolio`: Rebuild v11 shortcuts with correct plist structure
**Apr 01** — `interior-designer-portfolio`: fix: blob pathname timestamp regex (no hyphen in pathname format)
**Apr 01** — `interior-designer-portfolio`: restore-and-remigrate: check R2 file size to identify bad 1×1 files only
**Apr 01** — `interior-designer-portfolio`: Add restore-and-remigrate endpoint to fix 1×1 placeholder migration
**Apr 01** — `interior-designer-portfolio`: Add iOS Shortcut v11a/v11b — multipart form body approach
**Apr 01** — `interior-designer-portfolio`: migrate-blob-to-r2: fetch public URL without auth headers (plain public CDN)
**Apr 01** — `interior-designer-portfolio`: Add gallery search + cross-linking, hamburger nav, journal tags + rich text fix
**Apr 01** — `interior-designer-portfolio`: v10: POST raw image bytes instead of base64 JSON
**Apr 01** — `interior-designer-portfolio`: migrate-blob-to-r2: try private URL (strip .public) to bypass CDN suspension
**Apr 01** — `interior-designer-portfolio`: Fix migrate-blob-to-r2: use BLOB_READ_WRITE_TOKEN to bypass suspension
**Apr 01** — `interior-designer-portfolio`: Add v8 shortcut: inline WFJSONValues to fix empty body bug
**Apr 01** — `interior-designer-portfolio`: Add /api/admin/migrate-blob-to-r2 — re-upload Vercel Blob images to R2
**Apr 01** — `interior-designer-portfolio`: Add debug logging to shortcut-save: capture raw body and content-type
**Apr 01** — `interior-designer-portfolio`: chore: install jest, ts-jest, ts-node for unit testing
**Apr 01** — `interior-designer-portfolio`: feat: smart stack rank, notes editor upgrades, @mention emails, author tracking
**Apr 01** — `interior-designer-portfolio`: Add v5 shortcuts: fix JSON body + batch URL variable substitution
**Apr 01** — `interior-designer-portfolio`: Fix 404s: resolve gallery image IDs to URLs in TaskRow
**Apr 01** — `interior-designer-portfolio`: Add v4 iOS shortcuts + update middleware public paths
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