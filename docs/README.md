# WWE Draft Manager

A web-based application for conducting custom WWE brand drafts with support for multiple divisions and roster types.

## Version History

### Version 1.0 - Initial Release
**Release Date:** December 17, 2025

The first version of WWE Draft Manager provided basic draft functionality:

- **Core Features:**
  - Configure custom number of show brands (1-10)
  - Customize brand names (RAW, SmackDown, NXT, etc.)
  - Add superstars to draft pool
  - Basic solo superstar drafting
  - Random distribution across all brands
  - Re-draft functionality
  - Reset and start over option

- **Basic Functionality:**
  - Simple name input for superstars
  - Equal distribution algorithm
  - Clean visual results display

### Version 1.1 - Women's Division & Roster Type Expansion
**Release Date:** January 14, 2026

Version 1.1 introduced comprehensive roster management with gender divisions and multiple roster types:

- **New Features:**
  - **Women's Division Support**
    - Separate Men's and Women's division tracking
    - Independent drafting for each division
    - Visual distinction between divisions (👔 Men's / 👗 Women's)
  
  - **Roster Type Categories**
    - Solo Superstars (singles competitors)
    - Tag Teams (2-person teams)
    - Factions (3+ person groups)
  
  - **Enhanced Distribution**
    - Six separate categories per brand:
      - Men's Solo Superstars
      - Men's Tag Teams
      - Men's Factions
      - Women's Solo Superstars
      - Women's Tag Teams
      - Women's Factions
    - Equal distribution within each category
    - Maintains balance across all brands

- **UI Improvements:**
  - Division selector (Men's/Women's)
  - Type selector (Solo/Tag Team/Faction)
  - Enhanced draft pool display with category labels
  - Organized results view with division headers
  - Color-coded categories for easy identification

## Features

### Brand Configuration
- Set number of show brands (1-10)
- Fully customizable brand names
- Dynamic brand name input fields

### Superstar Management
- Add unlimited superstars to draft pool
- Categorize by division (Men's/Women's)
- Categorize by type (Solo/Tag Team/Faction)
- Remove individual superstars from pool
- View complete draft pool with categories

### Draft System
- Random shuffle algorithm for fair distribution
- Even distribution across all brands
- Separate shuffling for each category
- Re-draft option to generate new results
- Reset functionality to start fresh

### Results Display
- Organized by brand
- Separated by division (Men's/Women's)
- Grouped by type (Solo/Tag Team/Faction)
- Clean, color-coded presentation
- Trophy icons for brand headers

## Technical Details

- **Framework:** React 18.2.0
- **Styling:** Tailwind CSS
- **Icons:** Custom SVG components (Lucide-inspired)
- **Build:** Standalone HTML with embedded JavaScript

## Usage

1. **Configure Brands**
   - Set the number of show brands
   - Name each brand

2. **Add Superstars**
   - Enter superstar or team name
   - Select type (Solo/Tag Team/Faction)
   - Choose division (Men's/Women's)
   - Click "Add to Draft Pool"

3. **Run Draft**
   - Click "RUN DRAFT" to execute the draft
   - View results organized by brand and division

4. **Manage Results**
   - Re-Draft: Generate new random distribution
   - Start Over: Clear all data and begin fresh

## Copyright

© 2025 Bryan Teves

---

*Create your perfect WWE brand split with balanced rosters across all divisions!*