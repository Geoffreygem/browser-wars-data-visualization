# The Browser Wars: Desktop Browser Market Share (2009–2026)

An animated data visualisation exploring how desktop browser market share changed worldwide between January 2009 and September 2026.

## Project Overview

This project uses Python to transform historical monthly browser-usage statistics into an animated bar chart race.

The animation explores the evolution of the browser market, including the decline of Internet Explorer, the rise of Google Chrome, the introduction of Microsoft Edge and changes in the positions of Firefox, Safari, Opera and other browsers.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and its animation module
- Pillow for browser logo processing
- FFmpeg for MP4 rendering
- JupyterLab for development
- DaVinci Resolve for final video editing

## Dataset

**Source:** [StatCounter Global Stats](https://gs.statcounter.com/browser-market-share/desktop/worldwide)

**Coverage:** January 2009 – September 2026

**Frequency:** Monthly

**Geographical coverage:** Worldwide

**Device category:** Desktop

**Metric:** Browser usage market share (%)

The data measures browser usage within StatCounter's methodology and should not be interpreted as absolute browser user counts.

## Features

- Animated browser market-share rankings
- Interpolation between monthly observations
- Browser logos and colour-coded bars
- Dynamic percentage labels
- Historical date counter
- Milestone annotations
- Full HD video export

## How to Run

1. Install the packages listed in `requirements.txt`.
2. Download the relevant StatCounter monthly CSV.
3. Put the dataset and appropriately licensed logo images in the locations expected by the notebook.
4. Open `Browser_Wars_Final.ipynb` in JupyterLab.
5. Run the cells in order.
6. Export the animation using FFmpeg.

## YouTube Documentary

The accompanying video presents the history of desktop browser competition through an animated ranking visualisation.

**YouTube video:** Link to be added after publication.

## Data and Asset Rights

Market-share data is attributed to StatCounter. Data redistribution is subject to the source's terms.

Browser logos and trademarks belong to their respective owners. Their inclusion in this project does not imply endorsement.

## Future Improvements

- Additional historical annotations
- More sophisticated smooth ranking transitions
- Interactive browser comparisons
- Mobile browser market-share visualisation
- Additional technology data visualisations
