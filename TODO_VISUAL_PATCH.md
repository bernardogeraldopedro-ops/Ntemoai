Using style.css to implement visual-only updates in index.html:
- Loading skeleton (6 shimmer cards)
- Page fade transitions (via CSS)
- Card hover effects (zoom, bottom gradient overlay, glow)
- Masonry/pinterest style via CSS grid-auto-rows + span classes using `style="--card-span:..."` already added to cards and skeleton
- Back-to-top floating button + show-after-scroll + smooth scroll (JS required by project logic constraints)

Patch currently depends on existing `index.html` changes for span classes.

Status: skeleton markup updated + gallery cards updated with span classes.

