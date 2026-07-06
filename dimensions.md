# Dimensions

All values in millimeters unless noted otherwise. Current canonical files use the loose finger-clearance revision.

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

**Files:** `outer_camera_shell_cut.svg`, `outer_camera_shell_preview.svg`

| Dimension | Value |
|-----------|-------|
| External width | 110.0 |
| External height | 70.0 |
| External depth | 45.0 |
| Opening | Right side open |

### Panels

| Panel | Face size (W × H) | Notes |
|-------|-------------------|-------|
| Top | 110.0 × 45.0 | 2 finger features per connected edge |
| Bottom | 110.0 × 45.0 | 2 finger features per connected edge |
| Front | 110.0 × 70.0 | 2 finger features per connected edge |
| Back | 110.0 × 70.0 | 2 finger features per connected edge |
| Left end | 45.0 × 70.0 | Right side omitted (open face) |

### Finger joint sizing (outer shell)

| Edge length | Nominal feature width | Male tab (loose) | Female notch (loose) |
|-------------|----------------------|------------------|----------------------|
| 110 mm (width edges) | 22.00 | 21.70 | 22.30 |
| 70 mm (height edges) | 14.00 | 13.70 | 14.30 |
| 45 mm (depth edges) | 9.00 | 8.70 | 9.30 |

### Cut sheet layout

| Property | Value |
|----------|-------|
| Sheet size | 368.175 × 184.175 |

---

## Inner drawer

**Files:** `inner_drawer_cut.svg`, `inner_drawer_preview.svg`

| Dimension | Value |
|-----------|-------|
| External length (L) | 106.325 |
| External height (H) | 63.15 |
| External depth (D) | 38.15 |
| Open face removed | Largest L × H face (front) |
| Open face area | 6714.424 mm² |

### Panels

| Panel | Face size | Notes |
|-------|-----------|-------|
| Back wall | 106.325 × 63.15 (L × H) | Opposite the open face |
| Top cap | 106.325 × 38.15 (L × D) | Open front edge is smooth |
| Bottom floor | 106.325 × 38.15 (L × D) | Open front edge is smooth |
| Left end | 38.15 × 63.15 (D × H) | Open front edge is smooth |
| Right pull end | 38.15 × 63.15 (D × H) | Open front edge is smooth |

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
| Sheet size | 249.800 × 206.625 |

---

## File map

| File | Purpose |
|------|---------|
| `outer_camera_shell.svg` | Outer shell — final Illustrator export |
| `inner_drawer.svg` | Inner drawer — final Illustrator export |
| `archive/` | Superseded earlier iterations (including loose-clearance cut/preview pairs) |
