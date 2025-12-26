# SATMA v1.0.0 - Software Application for Text Mining & Analysis

## 🎉 Initial Release

This is the first official release of SATMA (formerly SAMOA), a comprehensive desktop application for morphological and ontological text analysis with advanced statistical capabilities.

## ✨ Major Features

### 📊 Enhanced Ontological Analysis
- **9 Diverse Relationship Types**: Implemented sophisticated relationship detection including:
  - `is-a` (taxonomic hierarchies)
  - `part-of` (compositional relationships)
  - `causes` (causal relationships)
  - `enables` (facilitation relationships)
  - `requires` (dependency relationships)
  - `improves` (enhancement relationships)
  - `affects` (influence relationships)
  - `uses` (utilization relationships)
  - `related-to` (general associations)
- **Improved Network Visualization**: Fixed overlapping nodes with optimized spacing (k=2.5, 100 iterations) and color-coded relationship type labels

### 🔐 Comprehensive License Management System
- **4 License Types**:
  - **Trial**: 30-day full access, auto-converts to Basic on expiry
  - **Standard**: Time-limited full access, retains menus + stats after expiry
  - **Perpetual**: Unlimited full access
  - **Basic**: Menu access only (expired trial state)
- **Granular Feature Control**: 3-tier permission system
  - 6 menu items
  - 18 statistical techniques
  - 4 report formats
- **Auto-Trial Creation**: First-run automatically generates 30-day trial license

### 📈 Statistical Analysis Suite
Licensed access to 18+ statistical techniques including:
- Document-Term Matrix (DTM)
- TF-IDF Analysis
- T-Test, Chi-Square, ANOVA
- Correlation Analysis
- PCA, EFA, CFA
- And more...

## Contact
contact@codingfigs.com
kamakshaiah.m@codingfigs.com

## 📦 Installation

### System Requirements
- Windows 7/8/10/11 (64-bit)
- ~200 MB disk space
- No Python installation required

### Quick Start
1. Download `SATMA_Setup_v1.0.0.exe`
2. Run installer
3. Launch SATMA from Start Menu
4. Enjoy 30-day trial with full access

## 📝 Technical Notes

- **NLTK Data**: The application includes all required NLP data (~50 MB) for tokenization, stopword removal, lemmatization, and POS tagging
- **License Storage**: License files are stored in user's AppData directory with AES encryption
- **Admin Access**: Use admin password "SATMA2025Admin" for license management

## 🙏 Known Issues

None reported for initial release.

---

**Full Changelog**: Initial Release
