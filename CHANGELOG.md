# Changelog

## 1.3.0

- Gemini metadata is written under `googleVertex` and `vertex` instead of `google`, thought signatures are read from those keys first, `http(s)` and `gs://` URLs pass through, provider references throw and an explicit `baseURL` is kept for tuned endpoints. Vertex shares Google's request builder.
  Compatibility: Applications reading Vertex Gemini metadata under `google` must read `googleVertex` (or `vertex`), as upstream. Otherwise source-compatible.
