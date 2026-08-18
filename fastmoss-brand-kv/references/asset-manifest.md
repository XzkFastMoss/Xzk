# Asset manifest

All paths are relative to the skill root. Inspect an asset before use and preserve its aspect ratio.

| Asset | Purpose | Recommended use |
|---|---|---|
| `assets/fastmoss-logo.svg` | Exact FastMoss brand logo | Required brand anchor; use unchanged |
| `assets/hero-kv-four.webp` | Transparent/glass anniversary `4` | Fourth-anniversary and member-month hero; crop boldly |
| `assets/kv-ribbon.webp` | Rose-purple campaign ribbon | Motion, energy, transitions, celebratory depth |
| `assets/kv-globe.webp` | Global data visual | Global reach, market coverage, data intelligence |
| `assets/kv-data.webp` | Data-oriented campaign visual | Data proof, analytics, business intelligence |
| `assets/kv-ai.webp` | AI-oriented campaign visual | MCP/CLI/Agent and AI workflow campaigns |
| `assets/ai-agent-screenshot.png` | FastMoss Agent interface | Product demo crop; keep important UI legible |
| `assets/hero-slide-1.webp` | Supplied product/brand scene | Supporting campaign or feature visual |
| `assets/hero-slide-3.webp` | Supplied product/brand scene | Supporting campaign or feature visual |
| `assets/hero-slide-5.webp` | Supplied product/brand scene | Supporting campaign or feature visual |

## Selection rules

- Use one hero asset and no more than two secondary supplied assets in a static KV.
- Pair `hero-kv-four.webp` with anniversary/member-month messaging only.
- Pair `kv-ai.webp` or the Agent screenshot with MCP/CLI/Agent messaging.
- Pair `kv-data.webp` or `kv-globe.webp` with product positioning and data proof.
- Use `kv-ribbon.webp` as a supporting motion or edge element, not as the only product meaning.
- If an asset cannot be clearly connected to the message, omit it.

## Compositing rules

- Never rasterize or regenerate the logo when SVG placement is possible.
- Do not stretch any WebP or screenshot to fill a mismatched aspect ratio. Crop with intent.
- Maintain a clean edge or mask around transparent hero assets.
- Add glows using brand colors at restrained opacity; avoid changing the source asset's hue beyond the brand palette.
- Screenshots may be cropped, masked into a rounded panel, and enlarged. Do not edit UI labels into claims the product does not make.
