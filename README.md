# Code Snippets Organization

This directory contains VS Code code snippets organized into logical categories for easy discovery and use.

## File Structure

### Documentation & Imports
- **0-documentation.code-snippets** - Links to official documentation for various libraries
- **1-import.code-snippets** - Common import statements grouped by functionality

### Scikit-learn Snippets (sk-*)
- **2-sk-anomaly.code-snippets** - Anomaly detection and outlier detection models
- **3-sk-arguments.code-snippets** - Common arguments and parameters 
- **9-sk-data.code-snippets** - Data reading and loading utilities
- **10-sk-setup.code-snippets** - Setup and initialization
- **11-sk-preprocessing.code-snippets** - Data preprocessing and feature engineering
- **12-sk-classification.code-snippets** - Classification models and utilities
- **13-sk-regression.code-snippets** - Regression models and utilities
- **14-sk-clustering.code-snippets** - Clustering algorithms

### Plotly Express Snippets (px-*)
- **4-px-arguments.code-snippets** - Common arguments and parameters
- **5-px-figures.code-snippets** - Figure types and chart creation
- **6-px-data.code-snippets** - Data reading and loading utilities  
- **7-px-setup.code-snippets** - Setup and configuration
- **8-px-updates.code-snippets** - Figure updates and customization

## Usage

Each snippet file contains snippets with intuitive prefixes:

### Scikit-learn Prefixes
- `sk-anomaly-*` - Anomaly detection models
- `sk-args-*` - Common arguments  
- `sk-classify-*` - Classification models
- `sk-regress-*` - Regression models
- `sk-cluster-*` - Clustering models
- `sk-prep-*` - Data preprocessing
- `sk-read-*` - Data reading
- `sk-setup` - Environment setup

### Plotly Express Prefixes  
- `px-args-*` - Arguments and parameters
- `px-fig-*` - Figure creation
- `px-read-*` - Data reading
- `px-setup-*` - Setup and configuration
- `px-update-*` - Figure updates

### Import Prefixes
- `imp-*` - Import statements grouped by functionality

### Reference Prefixes
- `ref-*` - Documentation links

## Examples

Type these prefixes in VS Code to get auto-completion:

- `sk-anomaly-` - Shows all anomaly detection models
- `px-fig-scatter` - Creates a scatter plot
- `sk-classify-random-forest` - Creates a Random Forest classifier
- `imp-basic` - Imports common data science libraries
- `ref-sklearn` - Link to scikit-learn documentation

## Benefits

1. **Easy Discovery** - Logical grouping makes finding relevant snippets simple
2. **Consistent Naming** - Predictable prefix patterns
3. **Complete Workflows** - From imports to model evaluation
4. **Best Practices** - Includes proper error handling and documentation
5. **Template Variables** - Smart placeholders for customization

## File Naming Convention

Files are numbered to maintain logical order:
- 0-1: Core utilities (docs, imports)  
- 2-14: Specific libraries and functionality
- Numbers ensure proper sorting in file explorer

This organization replaces the original `sklearn.json` and `ploty.json` files with a more maintainable and discoverable structure.
