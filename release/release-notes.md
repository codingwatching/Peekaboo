## 4.3.4 - 2026-09-11

**Highlights:** Restore provider-compatible MCP tools and frontmost daemon captures.

- Publish flat `click` and `paste` MCP schemas for clients that forward tools to Anthropic, while preserving runtime target, receipt, and foreground-consent validation; thanks @goutamadwant for #711 and @muellah for #708.
- Preserve the observed application identity and frontmost capture mode across exact-window capture so the daemon can validate frontmost screenshots without relaxing owner-generation or window checks. #710.
- Update SwiftLog to 1.15.1 for default logging dispatch and Swift toolchain compatibility fixes.
