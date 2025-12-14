# 璇璣圖 Poster Designer

A web-based tool for styling and exporting the Xuanji Tu (璇璣圖) poem as a printable poster.

## About the Poem

The **璇璣圖** (Xuanji Tu, "Star Gauge" or "Armillary Sphere Chart") is a famous palindrome poem created by **Su Hui (蘇蕙)**, also known by her courtesy name **Su Ruolan (蘇若蘭)**, during the Former Qin Dynasty in the 4th century CE.

- **841 characters** arranged in a 29×29 grid
- Can be read in multiple directions (horizontally, vertically, diagonally, and more)
- Contains approximately **7,958 different poems** depending on reading path
- One of the most remarkable examples of constrained writing in Chinese literature

## Features

- **Live Preview**: See changes in real-time as you adjust settings
- **Color Presets**: Classic Gold, Ink & Paper, Night Sky, Minimal, Vermillion, Jade
- **Highlight Patterns**: 14 patterns to visualize different reading regions
  - Center (心), 3×3, Corners, Inner Corners, Diamond rings, Cross, Border, Diagonals, Quadrants, Side rectangles, and more
- **Multi-layer Highlights**: Stack multiple patterns with custom colors and priority ordering
- **Typography Options**: Multiple Chinese font choices, adjustable sizes and spacing
- **Export**: Download as SVG (vector) or PNG (high resolution)
- **Persistence**: Settings automatically saved to localStorage

## Usage

Open `index.html` in a web browser. No build step or server required.

```bash
# Or serve locally
python -m http.server 8000
# Then visit http://localhost:8000
```

## Poem Source

The poem text is sourced from [Wikisource (維基文庫)](https://zh.wikisource.org/zh/%E7%92%87%E7%8E%91%E5%9B%BE).

## License

This tool is provided for personal and educational use. The poem itself is in the public domain.
