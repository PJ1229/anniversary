# Dimensions

All values in millimeters unless noted otherwise. Current canonical files use the loose finger-clearance revision with **oversized cap** small sides.

## Shared build parameters

| Parameter | Value |
|-----------|-------|
| Material thickness | 3.175 |
| Assumed kerf | 0.15 |
| Finger tab depth | 3.175 (equals material thickness) |
| Finger clearance (total per mating feature) | 0.30 |
| Finger clearance (per side) | 0.15 |
| Drawer sliding clearance (per side) | 0.25 |
| Drawer sliding clearance (total per axis) | 0.50 |

## Outer camera shell

**File:** `outer_camera_shell.svg`

| Dimension | Value |
|-----------|-------|
| External width | 110.0 |
| External height | 70.0 |
| External depth | 45.0 |
| Opening | Right side open |

### Oversized cap side (left end)

| | Nominal | Actual cut body |
|---|---------|-----------------|
| Depth | 45.0 | 51.35 (depth + 2× thickness) |
| Height | 70.0 | 76.35 (height + 2× thickness) |

The small side reaches top, bottom, front, and back panels at the corners.

### Panels

| Panel | Face size (W × H) | Notes |
|-------|-------------------|-------|
| Top | 110.0 × 45.0 | 2 finger features per connected edge |
| Bottom | 110.0 × 45.0 | 2 finger features per connected edge |
| Front | 110.0 × 70.0 | 2 finger features per connected edge |
| Back | 110.0 × 70.0 | 2 finger features per connected edge |
| Left end | 45.0 × 70.0 (nominal) | Oversized cap; right side open |

### Finger joint sizing (outer shell)

| Edge length | Nominal feature width | Male tab (loose) | Female notch (loose) |
|-------------|----------------------|------------------|----------------------|
| 110 mm (width edges) | 22.00 | 21.70 | 22.30 |
| 70 mm (height edges) | 14.00 | 13.70 | 14.30 |
| 45 mm (depth edges) | 9.00 | 8.70 | 9.30 |

### Cut sheet layout

| Property | Value |
|----------|-------|
| Sheet size | 317.1 × 155.4 |

---

## Inner drawer

**File:** `inner_drawer.svg`

| Dimension | Value |
|-----------|-------|
| External length (L) | 106.325 |
| External height (H) | 63.15 |
| External depth (D) | 38.15 |
| Open face removed | Largest L × H face (front) |
| Open face area | 6714.424 mm² |

### Oversized cap sides (left & right ends)

| | Nominal | Actual cut body |
|---|---------|-----------------|
| Depth | 38.15 | 41.325 (depth + 1× thickness) |
| Height | 63.15 | 69.5 (height + 2× thickness) |

Each small side reaches the top panel, bottom panel, and back wall while leaving the largest face open.

### Panels

| Panel | Face size | Notes |
|-------|-----------|-------|
| Back wall | 106.325 × 63.15 (L × H) | Opposite the open face |
| Top cap | 106.325 × 38.15 (L × D) | Open front edge is smooth |
| Bottom floor | 106.325 × 38.15 (L × D) | Open front edge is smooth |
| Left end | 38.15 × 63.15 (nominal) | Oversized cap |
| Right pull end | 38.15 × 63.15 (nominal) | Oversized cap |

### Drawer fit inside outer shell

| | Length | Height | Depth |
|---|--------|--------|-------|
| Outer internal space | 106.825 | 63.65 | 38.65 |
| Drawer outer size | 106.325 | 63.15 | 38.15 |
| Total clearance | 0.50 | 0.50 | 0.50 |
| Clearance per side | 0.25 | 0.25 | 0.25 |

### Cut sheet layout

| Property | Value |
|----------|-------|
| Sheet size | 211.6 × 186.6 |

---

## File map

| File | Purpose |
|------|---------|
| `outer_camera_shell.svg` | Outer shell — Glowforge-ready cut (hairline red stroke) |
| `inner_drawer.svg` | Inner drawer — Glowforge-ready cut (hairline red stroke) |
| `archive/` | Superseded earlier iterations |
