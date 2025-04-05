# Dall-E Creator

Uses prompts to call Dall-E API.

Written in Go.

For example:
```yaml
api_key: "YOUR_OPENAI_API_KEY"

items:
  - prompt: |
      A 16:9 background for a "Title Slide" in a graffiti/street art style.
      Dark, grungy concrete texture with subtle paint splatters.
      A large stenciled header area (no text in the image) near the top-center,
      bright accent strokes in neon pink or teal.
      Edgy brushstrokes or graffiti shapes in corners,
      rebellious and energetic vibe.
    output: "actorjam_title_slide_bg.png"

  - prompt: |
      A 16:9 background for a "Section Break" slide, continuing the gritty graffiti aesthetic.
      Main feature: a bold diagonal paint splash across the middle,
      where text can be placed.
      Dark concrete texture with neon pink paint drips.
      Minimal but striking, so a short phrase stands out.
    output: "actorjam_section_break_bg.png"

  - prompt: |
      A 16:9 "Title + Content" slide background in street-art style.
      Corners have painted elements: top-left and bottom-right.
      The center area is slightly clearer for text.
      Subtle hints of stenciled shapes or a faint clapperboard watermark.
      Keep the color scheme consistent: dark background, bright accent.
    output: "actorjam_title_content_bg.png"

  - prompt: |
      A 16:9 layout in graffiti style for a "Two-Column" slide.
      A vertical paint stroke dividing left and right halves,
      left side slightly brighter or faded for text,
      right side more decorative with bold neon and stencils.
      Maintain the overall dark, edgy aesthetic.
    output: "actorjam_two_column_bg.png"

  - prompt: |
      A 16:9 "Thank You" or "End" slide background for Actor Jam.
      Possibly a large clapperboard silhouette or swirl of paint crossing diagonally.
      Dark background, hot-pink or teal accent splashes,
      room in the middle to say "Thank You" or "Join Now." Rebellious, but welcoming.
    output: "actorjam_thankyou_bg.png"
```
