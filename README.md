# Sensor Plot Generation

This project generates synthetic temperature readings for two sensors and creates a set of publication-quality plots saved to an image file.

## Installation

1. Activate the `ece105` conda environment:

```bash
conda activate ece105
```

2. Install dependencies:

```bash
conda install numpy matplotlib
```

If you prefer `mamba`, use:

```bash
mamba install numpy matplotlib
```

## Usage

Run the script from the project directory:

```bash
python generate_plots.py
```

## Example output

The script produces a single image file named `sensor_analysis.png` containing three plots:

- A scatter plot showing Sensor A and Sensor B temperature readings over time.
- An overlaid histogram comparing the temperature distributions of both sensors, with vertical dashed lines marking each sensor mean.
- A side-by-side box plot comparing the distribution of Sensor A and Sensor B readings, with a horizontal dashed line at the overall mean.

## AI tools used and disclosure

Placeholder: describe any AI assistance used here.
