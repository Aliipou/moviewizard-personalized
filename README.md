<div align="center">

[![React](https://img.shields.io/badge/React-18+-61DAFB?style=flat&amp;logo=react)](https://reactjs.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE)

# MovieWizard

**AI-powered personalized movie discovery with mood-based recommendations.**

</div>

## Overview

Picking a movie is harder than it should be. MovieWizard learns your taste from your ratings and adapts to your current mood to surface films you will actually enjoy — not just what is trending.

## How It Works

**Collaborative Filtering**
Finds users with similar taste profiles and surfaces films they loved that you have not seen yet.

**Mood Detection**
Asks a few lightweight questions about what you feel like watching (energy level, genre mood, runtime preference) and filters recommendations accordingly.

**Content-Based Fallback**
When collaborative data is sparse (new user), switches to content-based similarity using genre, director, cast, and thematic tags.

## Quick Start

```bash
git clone https://github.com/Aliipou/moviewizard-personalized.git
cd moviewizard-personalized
npm install
npm run dev
```

## License

MIT
