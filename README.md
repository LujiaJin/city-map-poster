# City Map Poster Generator

Generate beautiful, minimalist map posters for any city in the world.

<img src="posters/singapore_neon_cyberpunk_20260118_153328.png" width="250">
<img src="posters/dubai_midnight_blue_20260118_140807.png" width="250">
<img src="posters/beijing_contrast_zones_20260303_144519.png" width="250">
<img src="posters/shanghai_neon_cyberpunk_20260303_160906.png" width="250">

> **Fork** of [originalankur/maptoposter](https://github.com/originalankur/maptoposter) — extended with Chinese city themes, proxy support, viewport offset flags, and rendering quality improvements. Upstream PR: [#207](https://github.com/originalankur/maptoposter/pull/207)

## Examples

### International Cities

| Country      | City           | Theme           | Poster |
|:------------:|:--------------:|:---------------:|:------:|
| USA          | San Francisco  | sunset          | <img src="posters/san_francisco_sunset_20260118_144726.png" width="250"> |
| Spain        | Barcelona      | warm_beige      | <img src="posters/barcelona_warm_beige_20260118_140048.png" width="250"> |
| Italy        | Venice         | blueprint       | <img src="posters/venice_blueprint_20260120_224440.png" width="250"> |
| Japan        | Tokyo          | japanese_ink    | <img src="posters/tokyo_japanese_ink_20260118_142446.png" width="250"> |
| India        | Mumbai         | contrast_zones  | <img src="posters/mumbai_contrast_zones_20260118_145843.png" width="250"> |
| Morocco      | Marrakech      | terracotta      | <img src="posters/marrakech_terracotta_20260118_143253.png" width="250"> |
| Singapore    | Singapore      | neon_cyberpunk  | <img src="posters/singapore_neon_cyberpunk_20260118_153328.png" width="250"> |
| Australia    | Melbourne      | forest          | <img src="posters/melbourne_forest_20260118_153446.png" width="250"> |
| UAE          | Dubai          | midnight_blue   | <img src="posters/dubai_midnight_blue_20260118_140807.png" width="250"> |
| USA          | Seattle        | emerald         | <img src="posters/seattle_emerald_20260124_162244.png" width="250"> |

### Chinese Cities (中国城市)

| Province     | City (城市)    | Theme                 | Poster |
|:------------:|:--------------:|:---------------------:|:------:|
| 北京          | 北京 Beijing   | contrast_zones        | <img src="posters/beijing_contrast_zones_20260303_144519.png" width="250"> |
| 上海          | 上海 Shanghai  | neon_cyberpunk        | <img src="posters/shanghai_neon_cyberpunk_20260303_160906.png" width="250"> |
| 重庆          | 重庆 Chongqing | mountain_city         | <img src="posters/chongqing_mountain_city_20260303_181228.png" width="250"> |
| 天津          | 天津 Tianjin   | haihe_night           | <img src="posters/tianjin_haihe_night_20260304_165230.png" width="250"> |
| 香港          | 香港 Hong Kong | victoria_harbour      | <img src="posters/hong_kong_victoria_harbour_20260303_190756.png" width="250"> |
| 山西          | 太原 Taiyuan   | jinshan_gold          | <img src="posters/taiyuan_jinshan_gold_20260304_162922.png" width="250"> |
| 山西          | 大同 Datong    | datong_coal           | <img src="posters/datong_datong_coal_20260305_100606.png" width="250"> |
| 内蒙古        | 赤峰 Chifeng   | steppe_sky            | <img src="posters/chifeng_steppe_sky_20260305_100420.png" width="250"> |
| 内蒙古        | 呼和浩特 Hohhot| steppe_sky            | <img src="posters/hohhot_steppe_sky_20260304_163757.png" width="250"> |
| 四川          | 成都 Chengdu   | sichuan_spice         | <img src="posters/chengdu_sichuan_spice_20260303_173956.png" width="250"> |
| 四川          | 甘孜 Kangding  | gongga_glacial        | <img src="posters/kangding_gongga_glacial_20260304_133753.png" width="250"> |
| 西藏          | 拉萨 Lhasa     | tibetan_sky           | <img src="posters/lhasa_tibetan_sky_20260304_134902.png" width="250"> |
| 西藏          | 林芝 Nyingchi  | peach_spring          | <img src="posters/nyingchi_peach_spring_20260304_164213.png" width="250"> |
| 西藏          | 昌都 Chamdo    | lhasa_crimson         | <img src="posters/chamdo_lhasa_crimson_20260304_133440.png" width="250"> |
| 福建          | 福州 Fuzhou    | min_river             | <img src="posters/fuzhou_min_river_20260305_100944.png" width="250"> |
| 福建          | 厦门 Xiamen    | xiamen_sea            | <img src="posters/xiamen_xiamen_sea_20260305_101046.png" width="250"> |
| 江苏          | 无锡 Wuxi      | taihu_ink             | <img src="posters/wuxi_taihu_ink_20260304_111440.png" width="250"> |
| 广东          | 深圳 Shenzhen  | shenzhen_tech         | <img src="posters/shenzhen_shenzhen_tech_20260303_182656.png" width="250"> |
| 江苏          | 南京 Nanjing   | ming_purple           | <img src="posters/nanjing_ming_purple_20260303_182341.png" width="250"> |
| 陕西          | 西安 Xi'an     | tang_dynasty          | <img src="posters/xi'an_tang_dynasty_20260303_180247.png" width="250"> |
| 河北          | 承德 Chengde   | chengde_forest        | <img src="posters/chengde_chengde_forest_20260304_174512.png" width="250"> |
| 河北          | 秦皇岛 Qinhuangdao | qinhuangdao_coast | <img src="posters/qinhuangdao_qinhuangdao_coast_20260305_104832.png" width="250"> |
| 宁夏          | 固原 Guyuan    | loess_jin             | <img src="posters/guyuan_loess_jin_20260305_103025.png" width="250"> |
| 宁夏          | 中卫 Zhongwei  | tengger_sand          | <img src="posters/zhongwei_tengger_sand_20260305_100920.png" width="250"> |
| 宁夏          | 银川 Yinchuan  | spring_youth          | <img src="posters/yinchuan_spring_youth_20260303_152538.png" width="250"> |
| 山西          | 临汾 Linfen    | loess_jin             | <img src="posters/linfen_loess_jin_20260304_152659.png" width="250"> |
| 山西          | 运城 Yuncheng  | guandi_red            | <img src="posters/yuncheng_guandi_red_20260304_115300.png" width="250"> |
| 江西          | 庐山 Lushan    | lushan_mist           | <img src="posters/lushan_lushan_mist_20260304_151816.png" width="250"> |
| 四川          | 雅安 Yaan      | lushan_mist           | <img src="posters/yaan_lushan_mist_20260305_094304.png" width="250"> |
| 河北          | 邯郸 Handan    | zhao_bronze           | <img src="posters/handan_zhao_bronze_20260303_193728.png" width="250"> |
| 浙江          | 舟山 Putuoshan | putuo_zen             | <img src="posters/putuoshan_putuo_zen_20260303_172426.png" width="250"> |

## Installation

### With uv (Recommended)

Make sure [uv](https://docs.astral.sh/uv/) is installed. Running the script by prepending `uv run` automatically creates and manages a virtual environment.

```bash
# First run will automatically install dependencies
uv run ./create_map_poster.py --city "Paris" --country "France"

# Or sync dependencies explicitly first (using locked versions)
uv sync --locked
uv run ./create_map_poster.py --city "Paris" --country "France"
```

### With pip + venv

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Usage

### Generate Poster

If you're using `uv`:

```bash
uv run ./create_map_poster.py --city <city> --country <country> [options]
```

Otherwise (pip + venv):

```bash
python create_map_poster.py --city <city> --country <country> [options]
```

### Required Options

| Option | Short | Description |
|--------|-------|-------------|
| `--city` | `-c` | City name (used for geocoding) |
| `--country` | `-C` | Country name (used for geocoding) |

### Optional Flags

| Option | Short | Description | Default |
|--------|-------|-------------|---------|
| **OPTIONAL:** `--latitude` | `-lat` | Override latitude center point (use with --longitude) | |
| **OPTIONAL:** `--longitude` | `-long` | Override longitude center point (use with --latitude) | |
| **OPTIONAL:** `--country-label` | | Override country text displayed on poster | |
| **OPTIONAL:** `--theme` | `-t` | Theme name | terracotta |
| **OPTIONAL:** `--distance` | `-d` | Map radius in meters | 18000 |
| **OPTIONAL:** `--list-themes` | | List all available themes | |
| **OPTIONAL:** `--all-themes` | | Generate posters for all available themes | |
| **OPTIONAL:** `--width` | `-W` | Image width in inches | 12 (max: 20) |
| **OPTIONAL:** `--height` | `-H` | Image height in inches | 16 (max: 20) |
| **OPTIONAL:** `--map-x-offset` | `-mx` | Shift viewport left/right (-1.0 to +1.0) | 0.0 |
| **OPTIONAL:** `--map-y-offset` | `-my` | Shift viewport up/down (-1.0 to +1.0) | 0.0 |

### Multilingual Support - i18n

Display city and country names in your language with custom fonts from google fonts:

| Option | Short | Description |
|--------|-------|-------------|
| `--display-city` | `-dc` | Custom display name for city (e.g., "東京") |
| `--display-country` | `-dC` | Custom display name for country (e.g., "日本") |
| `--font-family` | | Google Fonts family name (e.g., "Noto Sans JP") |

**Examples:**

```bash
# Japanese
python create_map_poster.py -c "Tokyo" -C "Japan" -dc "東京" -dC "日本" --font-family "Noto Sans JP"

# Korean
python create_map_poster.py -c "Seoul" -C "South Korea" -dc "서울" -dC "대한민국" --font-family "Noto Sans KR"

# Arabic
python create_map_poster.py -c "Dubai" -C "UAE" -dc "دبي" -dC "الإمارات" --font-family "Cairo"
```

**Note**: Fonts are automatically downloaded from Google Fonts and cached locally in `fonts/cache/`.

### Resolution Guide (300 DPI)

Use these values for `-W` and `-H` to target specific resolutions:

| Target | Resolution (px) | Inches (-W / -H) |
|--------|-----------------|------------------|
| **Instagram Post** | 1080 x 1080 | 3.6 x 3.6 |
| **Mobile Wallpaper** | 1080 x 1920 | 3.6 x 6.4 |
| **HD Wallpaper** | 1920 x 1080 | 6.4 x 3.6 |
| **4K Wallpaper** | 3840 x 2160 | 12.8 x 7.2 |
| **A4 Print** | 2480 x 3508 | 8.3 x 11.7 |

### Usage Examples

#### Basic Examples

```bash
# Simple usage with default theme
python create_map_poster.py -c "Paris" -C "France"

# With custom theme and distance
python create_map_poster.py -c "New York" -C "USA" -t noir -d 12000
```

#### Multilingual Examples (Non-Latin Scripts)

Display city names in their native scripts:

```bash
# Japanese
python create_map_poster.py -c "Tokyo" -C "Japan" -dc "東京" -dC "日本" --font-family "Noto Sans JP" -t japanese_ink

# Korean
python create_map_poster.py -c "Seoul" -C "South Korea" -dc "서울" -dC "대한민국" --font-family "Noto Sans KR" -t midnight_blue

# Thai
python create_map_poster.py -c "Bangkok" -C "Thailand" -dc "กรุงเทพมหานคร" -dC "ประเทศไทย" --font-family "Noto Sans Thai" -t sunset

# Arabic
python create_map_poster.py -c "Dubai" -C "UAE" -dc "دبي" -dC "الإمارات" --font-family "Cairo" -t terracotta

# Chinese (Simplified)
python create_map_poster.py -c "Beijing" -C "China" -dc "北京" -dC "中国" --font-family "Noto Sans SC"

# Chinese city with viewport offset (shift map center)
python create_map_poster.py -c "Guyuan" -C "China" -dc "固原" -dC "宁夏" --font-family "Noto Sans SC" -t loess_jin -d 30000 -mx 0.167

# Khmer
python create_map_poster.py -c "Phnom Penh" -C "Cambodia" -dc "ភ្នំពេញ" -dC "កម្ពុជា" --font-family "Noto Sans Khmer"
```

#### Advanced Examples

```bash
# Iconic grid patterns
python create_map_poster.py -c "New York" -C "USA" -t noir -d 12000           # Manhattan grid
python create_map_poster.py -c "Barcelona" -C "Spain" -t warm_beige -d 8000   # Eixample district

# Waterfront & canals
python create_map_poster.py -c "Venice" -C "Italy" -t blueprint -d 4000       # Canal network
python create_map_poster.py -c "Amsterdam" -C "Netherlands" -t ocean -d 6000  # Concentric canals
python create_map_poster.py -c "Dubai" -C "UAE" -t midnight_blue -d 15000     # Palm & coastline

# Radial patterns
python create_map_poster.py -c "Paris" -C "France" -t pastel_dream -d 10000   # Haussmann boulevards
python create_map_poster.py -c "Moscow" -C "Russia" -t noir -d 12000          # Ring roads

# Organic old cities
python create_map_poster.py -c "Tokyo" -C "Japan" -t japanese_ink -d 15000    # Dense organic streets
python create_map_poster.py -c "Marrakech" -C "Morocco" -t terracotta -d 5000 # Medina maze
python create_map_poster.py -c "Rome" -C "Italy" -t warm_beige -d 8000        # Ancient layout

# Coastal cities
python create_map_poster.py -c "San Francisco" -C "USA" -t sunset -d 10000    # Peninsula grid
python create_map_poster.py -c "Sydney" -C "Australia" -t ocean -d 12000      # Harbor city
python create_map_poster.py -c "Mumbai" -C "India" -t contrast_zones -d 18000 # Coastal peninsula

# River cities
python create_map_poster.py -c "London" -C "UK" -t noir -d 15000              # Thames curves
python create_map_poster.py -c "Budapest" -C "Hungary" -t copper_patina -d 8000  # Danube split

# Override center coordinates
python create_map_poster.py --city "New York" --country "USA" -lat 40.776676 -long -73.971321 -t noir

# List available themes
python create_map_poster.py --list-themes

# Generate posters for every theme
python create_map_poster.py -c "Tokyo" -C "Japan" --all-themes
```

### Distance Guide

| Distance | Best for |
|----------|----------|
| 4000-6000m | Small/dense cities (Venice, Amsterdam center) |
| 8000-12000m | Medium cities, focused downtown (Paris, Barcelona) |
| 15000-20000m | Large metros, full city view (Tokyo, Mumbai) |

## Themes

### Original Themes (17)

17 built-in themes available in `themes/` directory:

| Theme | Style |
|-------|-------|
| `gradient_roads` | Smooth gradient shading |
| `contrast_zones` | High contrast urban density |
| `noir` | Pure black background, white roads |
| `midnight_blue` | Navy background with gold roads |
| `blueprint` | Architectural blueprint aesthetic |
| `neon_cyberpunk` | Dark with electric pink/cyan |
| `warm_beige` | Vintage sepia tones |
| `pastel_dream` | Soft muted pastels |
| `japanese_ink` | Minimalist ink wash style |
| `emerald`      | Lush dark green aesthetic |
| `forest` | Deep greens and sage |
| `ocean` | Blues and teals for coastal cities |
| `terracotta` | Mediterranean warmth |
| `sunset` | Warm oranges and pinks |
| `autumn` | Seasonal burnt oranges and reds |
| `copper_patina` | Oxidized copper aesthetic |
| `monochrome_blue` | Single blue color family |

### Chinese City Themes (新增中国城市主题)

30+ custom themes tailored for Chinese cities and landscapes:

| Theme | 适合城市 | Style |
|-------|---------|-------|
| `loess_jin` | 固原、临汾、晋中、朔州、大同 | Loess Plateau earthy golds |
| `datong_coal` | 大同 | Dark coal-black with gold roads |
| `steppe_sky` | 赤峰、呼和浩特 | Inner Mongolia steppe greens |
| `taihu_ink` | 无锡 | Ink-wash green for Taihu Lake area |
| `min_river` | 福州 | Deep forest ink for Min River delta |
| `xiamen_sea` | 厦门 | Bright tropical green |
| `qinhuangdao_coast` | 秦皇岛 | Bohai Sea blue (sea as background) |
| `tengger_sand` | 中卫 | Yellow-gold Tengger Desert |
| `chengde_forest` | 承德 | Dense mountain forest ink |
| `lushan_mist` | 庐山、雅安 | Misty mountain jade |
| `tibetan_sky` | 拉萨、日喀则、山南 | High-altitude sky blue |
| `lhasa_crimson` | 昌都 | Crimson palace red on dark |
| `gongga_glacial` | 甘孜 | Glacial grey-blue |
| `peach_spring` | 林芝 | Deep emerald with pearl roads |
| `jinshan_gold` | 太原 | Deep black with golden architecture |
| `haihe_night` | 天津 | Night-glow dark navy with gold |
| `guandi_red` | 运城 | Ceremonial deep red |
| `tang_dynasty` | 西安 | Imperial Tang earth tones |
| `ming_purple` | 南京 | Ming dynasty deep purple |
| `sichuan_spice` | 成都 | Sichuan spice dark brown |
| `mountain_city` | 重庆 | Dark mountain fog |
| `shenzhen_tech` | 深圳 | High-tech teal |
| `victoria_harbour` | 香港 | Deep harbour navy |
| `zhao_bronze` | 邯郸 | Ancient bronze patina |
| `putuo_zen` | 舟山普陀山 | Meditative grey-blue |
| `spring_youth` | 银川 | Fresh spring green |
| `winter_peaks` | 张家口 | Snow-white peaks |
| `grassland_blueprint` | 乌兰察布 | Blueprint on steppe |
| `loess_gobi` | 同心 | Arid gobi beige |
| `jinshan_gold` | 太原 | Deep black, gold roads |

## Output

Posters are saved to `posters/` directory with format:

```text
{city}_{theme}_{YYYYMMDD_HHMMSS}.png
```

## Adding Custom Themes

Create a JSON file in `themes/` directory:

```json
{
  "name": "My Theme",
  "description": "Description of the theme",
  "bg": "#FFFFFF",
  "text": "#000000",
  "gradient_color": "#FFFFFF",
  "water": "#C0C0C0",
  "parks": "#F0F0F0",
  "road_motorway": "#0A0A0A",
  "road_primary": "#1A1A1A",
  "road_secondary": "#2A2A2A",
  "road_tertiary": "#3A3A3A",
  "road_residential": "#4A4A4A",
  "road_default": "#3A3A3A",

  "road_width_scale": 1.5,
  "bg_patina": true,
  "bg_patina_color": "#40A880",
  "bg_top": "#1A3A6A",
  "bg_bottom": "#0A1A3A"
}
```

### Extended Theme Keys (this fork)

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| `road_width_scale` | float | `1.0` | Multiply all road stroke widths (e.g. `2.0` = double width for sparse suburban maps) |
| `bg_patina` | bool | `false` | Enable a subtle texture overlay on the background for an aged/aged-paper effect |
| `bg_patina_color` | hex string | `"#40A880"` | Tint color of the patina overlay (only used when `bg_patina` is `true`) |
| `bg_top` | hex string | — | Top color of a vertical background gradient; overrides `bg` when set |
| `bg_bottom` | hex string | — | Bottom color of the vertical background gradient; paired with `bg_top` |

## Project Structure

```text
map_poster/
├── create_map_poster.py    # Main script
├── font_management.py      # Font loading and Google Fonts integration
├── themes/                 # Theme JSON files
├── fonts/                  # Font files
│   ├── Roboto-*.ttf        # Default Roboto fonts
│   └── cache/              # Downloaded Google Fonts (auto-generated)
├── posters/                # Generated posters
└── README.md
```


## Hacker's Guide

Quick reference for contributors who want to extend or modify the script.

### Contributors Guide

- Bug fixes are welcomed
- Don't submit user interface (web/desktop)
- Don't Dockerize for now
- If you vibe code any fix please test it and see before and after version of poster
- Before embarking on a big feature please ask in Discussions/Issue if it will be merged

### Architecture Overview

```text
┌─────────────────┐     ┌──────────────┐     ┌─────────────────┐
│   CLI Parser    │────▶│  Geocoding   │────▶│  Data Fetching  │
│   (argparse)    │     │  (Nominatim) │     │    (OSMnx)      │
└─────────────────┘     └──────────────┘     └─────────────────┘
                                                     │
                        ┌──────────────┐             ▼
                        │    Output    │◀────┌─────────────────┐
                        │  (matplotlib)│     │   Rendering     │
                        └──────────────┘     │  (matplotlib)   │
                                             └─────────────────┘
```

### Key Functions

| Function | Purpose | Modify when... |
|----------|---------|----------------|
| `get_coordinates()` | City → lat/lon via Nominatim | Switching geocoding provider |
| `create_poster()` | Main rendering pipeline | Adding new map layers |
| `get_edge_colors_by_type()` | Road color by OSM highway tag | Changing road styling |
| `get_edge_widths_by_type()` | Road width by importance | Adjusting line weights |
| `create_gradient_fade()` | Top/bottom fade effect | Modifying gradient overlay |
| `load_theme()` | JSON theme → dict | Adding new theme properties |
| `is_latin_script()` | Detects script for typography | Supporting new scripts |
| `load_fonts()` | Load custom/default fonts | Changing font loading logic |

### Rendering Layers (z-order)

```text
z=11  Text labels (city, country, coords)
z=10  Gradient fades (top & bottom)
z=3   Roads (via ox.plot_graph)
z=2   Parks (green polygons)
z=1   Water (blue polygons)
z=0   Background color
```

### OSM Highway Types → Road Hierarchy

```python
# In get_edge_colors_by_type() and get_edge_widths_by_type()
motorway, motorway_link     → Thickest (1.2), darkest
trunk, primary              → Thick (1.0)
secondary                   → Medium (0.8)
tertiary                    → Thin (0.6)
residential, living_street  → Thinnest (0.4), lightest
```

### Typography & Script Detection

The script automatically detects text scripts to apply appropriate typography:

- **Latin scripts** (English, French, Spanish, etc.): Letter spacing applied for elegant "P  A  R  I  S" effect
- **Non-Latin scripts** (Japanese, Arabic, Thai, Korean, etc.): Natural spacing for "東京" (no gaps between characters)

Script detection uses Unicode ranges (U+0000-U+024F for Latin). If >80% of alphabetic characters are Latin, spacing is applied.

### Adding New Features

**New map layer (e.g., railways):**

```python
# In create_poster(), after parks fetch:
try:
    railways = ox.features_from_point(point, tags={'railway': 'rail'}, dist=dist)
except:
    railways = None

# Then plot before roads:
if railways is not None and not railways.empty:
    railways = railways.to_crs(g_proj.graph["crs"])
    railways.plot(ax=ax, color=THEME['railway'], linewidth=0.5, zorder=2.5)
```

**New theme property:**

1. Add to theme JSON: `"railway": "#FF0000"`
2. Use in code: `THEME['railway']`
3. Add fallback in `load_theme()` default dict

### Typography Positioning

All text uses `transform=ax.transAxes` (0-1 normalized coordinates):

```text
y=0.14  City name (spaced letters for Latin scripts)
y=0.125 Decorative line
y=0.10  Country name
y=0.07  Coordinates
y=0.02  Attribution (bottom-right)
```

### Useful OSMnx Patterns

```python
# Get all buildings
buildings = ox.features_from_point(point, tags={'building': True}, dist=dist)

# Get specific amenities
cafes = ox.features_from_point(point, tags={'amenity': 'cafe'}, dist=dist)

# Different network types
G = ox.graph_from_point(point, dist=dist, network_type='drive')  # roads only
G = ox.graph_from_point(point, dist=dist, network_type='bike')   # bike paths
G = ox.graph_from_point(point, dist=dist, network_type='walk')   # pedestrian
```

### Performance Tips

- Large `dist` values (>20km) = slow downloads + memory heavy
- Cache coordinates locally to avoid Nominatim rate limits
- Use `network_type='drive'` instead of `'all'` for faster renders
- Reduce `dpi` from 300 to 150 for quick previews
