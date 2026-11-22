# Changelog

## 1.4.0

- Add Gemini Live transcription VAD controls and correct single-turn completion. Re-export the Vertex Interactions MCP server tool with telemetry redaction. Reviewed npm: @ai-sdk/google-vertex 5.0.141 to 5.0.144. Offline validation passed: node Scripts/test-packages.mjs (56 packages, 3672 owning tests and 1760 compatibility tests), generation, tooling, isolation, and version selection. See Docs/Archive/WeeklyUpstreamAudit20261122.md for retained gaps. Paid provider calls were skipped.
  Compatibility: Additive transcription options and tool API. Requires SwiftAIGoogle 1.5.0 for shared tool and telemetry behavior. Requires SwiftAIOpenAICompatible 1.4.0 for the public image model conformance introduced in Core 1.6.0.
