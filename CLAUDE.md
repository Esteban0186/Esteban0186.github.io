# CLAUDE.md - Build and Style Guide

## Build Commands
- `quarto render`: Render the entire website
- `quarto preview`: Start live preview server
- `quarto render <file>.qmd`: Render single file
- `QUARTO_PROJECT_RENDER_ALL=1 quarto render`: Run pre-render scripts and render site
- `python -m scripts.pre_create_papers_file`: Run papers generation script individually

## Python Style Guidelines
- Use 4-space indentation
- Type hints for function returns (-> dict, -> str)
- Snake_case for functions and variables, UPPER_CASE for constants
- Function docstrings with triple quotes
- F-strings for string formatting
- Use defaultdict and other specialized collections when appropriate
- Organize imports: standard library, then third-party, then local

## R Style Guidelines
- Use 2-space indentation (from RProj configuration)
- UTF-8 encoding

## Dependencies
- Python: See requirements.txt for dependencies
- Python venv recommended: `python -m venv venv && source venv/bin/activate`
- Install dependencies: `pip install -r requirements.txt`