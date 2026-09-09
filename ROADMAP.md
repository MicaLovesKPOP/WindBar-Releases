# WindBar Public Roadmap

This roadmap describes the current direction toward WindBar 1.0. It is a planning document, not a promise of dates or immutable version numbers.

## Release contract

WindBar 1.0 is intended to be a stable, native-feeling Windows 11 x64 taskbar replacement that keeps Explorer available as a safe fallback.

The v1 target includes all four taskbar edges, modular layout, normal application/taskbar workflows, Start and Search access, a usable notification area, Settings, auto-hide, safe recovery, signed installation, and one optional official Media Player plugin.

## Milestones

### 0.7 — Settings Foundation Freeze
Finish the current Settings foundation, then stop nonessential pixel-level parity work unless it fixes usability or release quality.

### 0.71 — Architecture Lock
Document the customization model, v1 release boundaries, and plugin ownership rules in the private development repository.

### 0.72 — Customization Resolver Foundation
Introduce a backwards-compatible customization resolution model capable of separating Design Language, Visual Theme, Color Scheme, Taskbar Style, Start Style, Layout Profile, and behavior defaults.

### 0.75 — Four-Edge Engine
Finish placement ownership, four-edge auto-hide, Apps layout/overflow, collision-free zone placement, and orientation transitions.

### 0.8 — Daily Driver
Harden tray/notification-area behavior, application identity, Start/Search reliability, settings persistence, single-instance behavior, and shell recovery.

### 0.82 — Official Media Player Plugin
Move WindBar's optional media experience behind the first official plugin boundary and harden its lifecycle and failure isolation.

### 0.85 — Platform Resilience
Address DPI/runtime scaling, multi-monitor safety, Explorer lifecycle, sleep/wake, fullscreen, resolution changes, and performance.

### 0.87 — Accessibility & Interaction Baseline
Keyboard navigation, visible focus, screen-reader/high-contrast sanity, text scaling, and other release-blocking interaction issues.

### 0.9 — Release Engineering & Closed Alpha
Signed installer, upgrade/uninstall paths, diagnostics, crash recovery, and structured testing with a small group of testers.

### 0.95 — Public Beta
Signed public beta, documented compatibility/known issues, public issue tracking, and a simple public website/download flow.

### 0.99 — Release Candidate
Feature freeze and formal acceptance testing across placement, scaling, monitors, shell recovery, installation, accessibility, and the Media Player plugin.

### 1.0 — Public Release
Stable Windows 11 x64 release meeting the v1 contract above.

## Explicitly post-v1 unless promoted later

- Independent WindBar taskbars per monitor
- Window thumbnails/previews and jump lists
- Public arbitrary third-party plugin loading
- Plugin marketplace/in-app community browser
- Complete Windows 7, Vista, XP, Longhorn, or other historical experiences
- Localization
- ARM64-native release
- Enterprise deployment/management

## Community content

WindBar will favor a curated model: community creations live externally, while only content deliberately reviewed and adopted by the WindBar project appears as integrated/official WindBar content.

Creator information will live in [WindBar-Contributions](https://github.com/MicaLovesKPOP/WindBar-Contributions).
