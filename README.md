# Features
- **🔄 Data Integration**: Merges data from three separate datasets for comprehensive analysis.
- **📊 Data Analysis**: Calculates and highlights top-performing categories based on total scores.
- **📈 Visualization**: Generates meaningful insights through aggregated scores and trends.

## Process
- **1️⃣ Merge Tables**: 
   - Base: `Reactions Table`
   - Joined: `Content Table` (on `Content ID`) & `Reaction Types Table` (on `Reaction Type`)
- **2️⃣ Score Aggregation**: Computes total scores for each category.
- **3️⃣ Top 5 Categories**: Highlights categories with the highest scores.

## Technologies Used
- **Python**: For data processing and merging datasets.
- **Power Query**: To handle data cleaning and transformations.
- **Excel/CSV**: Input data formats.

## Usage Instructions
- **🔄 Input Files**:
  - `Content.csv`: Contains content details like type and category.
  - `Reactions.xlsx`: Tracks user reactions with timestamps.
  - `ReactionTypes.csv`: Defines reaction types and associated scores.
    
- **📂 Final Output should be**:
  - A cleaned dataset combining all three files.
  - A list of the top 5 performing categories.

## Repository Structure
- **📁 Data**:
  - `Content.csv`
  - `Reactions.xlsx`
  - `ReactionTypes.csv`
