# FUMCanalysis

FUMCanalysis is a modular analysis toolkit designed for fast, flexible, and visually engaging data analysis workflows.

## Logo


![FUMCanalysis Logo](fumcanalysis-logo.svg)

## Features

### Modular Analysis

```svg
<svg width="350" height="80" viewBox="0 0 350 80" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="15" y="30" width="60" height="30" rx="8" fill="#81D4FA">
    <animate attributeName="fill" values="#81D4FA;#B2DFDB;#81D4FA" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="95" y="30" width="60" height="30" rx="8" fill="#A5D6A7">
    <animate attributeName="fill" values="#A5D6A7;#FFF176;#A5D6A7" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="175" y="30" width="60" height="30" rx="8" fill="#FFD54F">
    <animate attributeName="fill" values="#FFD54F;#CE93D8;#FFD54F" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="255" y="30" width="60" height="30" rx="8" fill="#FF8A65">
    <animate attributeName="fill" values="#FF8A65;#B2DFDB;#FF8A65" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="45" y="27" font-family="Verdana" font-size="12" fill="#0277BD" text-anchor="middle">Module 1</text>
  <text x="125" y="27" font-family="Verdana" font-size="12" fill="#388E3C" text-anchor="middle">Module 2</text>
  <text x="205" y="27" font-family="Verdana" font-size="12" fill="#FBC02D" text-anchor="middle">Module 3</text>
  <text x="285" y="27" font-family="Verdana" font-size="12" fill="#D84315" text-anchor="middle">Module 4</text>
  <polyline points="75,45 95,45" stroke="#616161" stroke-width="2" marker-end="url(#arrow)"/>
  <polyline points="155,45 175,45" stroke="#616161" stroke-width="2" marker-end="url(#arrow)"/>
  <polyline points="235,45 255,45" stroke="#616161" stroke-width="2" marker-end="url(#arrow)"/>
  <defs>
    <marker id="arrow" markerWidth="8" markerHeight="8" refX="5" refY="4" orient="auto">
      <polygon points="0 0, 8 4, 0 8" fill="#616161"/>
    </marker>
  </defs>
</svg>
```

### Live Data Visualization

```svg
<svg width="350" height="80" viewBox="0 0 350 80" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="30" y="60" width="30" height="10" fill="#26A69A">
    <animate attributeName="height" values="10;40;10" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="60;30;60" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="80" y="50" width="30" height="20" fill="#FFA726">
    <animate attributeName="height" values="20;50;20" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="50;0;50" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="130" y="40" width="30" height="30" fill="#AB47BC">
    <animate attributeName="height" values="30;60;30" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="40;10;40" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="180" y="65" width="30" height="5" fill="#26A69A">
    <animate attributeName="height" values="5;30;5" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="65;40;65" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="230" y="55" width="30" height="15" fill="#FFA726">
    <animate attributeName="height" values="15;45;15" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="55;25;55" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="175" y="20" font-family="Verdana" font-size="14" fill="#00897B" text-anchor="middle">Live Data Visualization</text>
</svg>
```

### Easy Integration

```svg
<svg width="350" height="80" viewBox="0 0 350 80" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="40" y="35" width="50" height="20" rx="8" fill="#B2DFDB"/>
  <rect x="260" y="35" width="50" height="20" rx="8" fill="#FFD54F"/>
  <text x="65" y="30" font-family="Verdana" font-size="12" fill="#00897B" text-anchor="middle">Your App</text>
  <text x="285" y="30" font-family="Verdana" font-size="12" fill="#FBC02D" text-anchor="middle">FUMCanalysis</text>
  <line x1="90" y1="45" x2="260" y2="45" stroke="#616161" stroke-width="2">
    <animate attributeName="stroke-dasharray" values="0, 200;100,100;0,200" dur="2s" repeatCount="indefinite"/>
  </line>
  <circle cx="175" cy="45" r="10" fill="#26A69A">
    <animate attributeName="r" values="10;16;10" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="175" y="70" font-family="Verdana" font-size="13" fill="#616161" text-anchor="middle">Plug & Play Integration</text>
</svg>
```

## Installation

```bash
# Clone the repository
git clone https://github.com/SairajChowdhary/FUMCanalysis.git

# Install dependencies
cd FUMCanalysis
pip install -r requirements.txt
```

## Usage

```python
import fumcanalysis

# Example usage
fumcanalysis.run_analysis(data)
```

## License

MIT

---

For more information, see the source files and documentation.
