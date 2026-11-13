# Changelog

## 1.2.1

- Inherit current Gemini and Anthropic hosting behavior. Keep Express Mode API keys and cloud credentials off tool-result and MaaS image downloads, preserving validated redirects and abort-before-network behavior. Reviewed npm delta: @ai-sdk/google-vertex 5.0.134 to 5.0.140. Validation: `node Scripts/test-packages.mjs` passed all 52 owning suites and 1731 facade tests; tooling 27/27, generation/isolation checks, standalone exports and 106 minimum/latest consumers, documentation check and 101-page build passed. Publication requires green exact-source Swift 6.3.3 CI. Paid/live verification and full-package parity are not claimed.
  Compatibility: Compatible behavior/header correction. Original public selectors are preserved. npm baselines and Swift SemVer are independent; this reviewed delta does not establish full-package or live-service parity. Required direct minimums: swift-ai-core 1.3.0 to 1.4.0, swift-ai-google 1.2.0 to 1.3.0, swift-ai-anthropic 1.3.0 to 1.4.0.
