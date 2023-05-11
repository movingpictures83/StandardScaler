# StandardScaler
# Language: Python
# Input: CSV (unnormalized matrix)
# Output: CSV (matrix normalized across rows)
# Tested with: PluMA 1.1, Python 3.6
# Dependency: sklearn==0.23.1, pandas==1.1.5

PluMA plugin that takes a CSV file and normalizes each row such that its values sum to 1, using the
StandardScaler (Raju et al, 2020) method.

Expected input file is the CSV file to normalize, and the output file is the same CSV file normalized.
Row and column names remain the same.
