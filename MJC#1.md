# Journal Entry - [DATE]

## Overview
- **Date**: 2025-05-30
- **Topic**: Merging, Joining, and Concatenate Tables
- **Duration**: 15 min reading

## What I Learned
- Merging data with pandas
  - Inner join
  - Outer join
  - Left join
  - Right join

## Code Snippets
- ### Inner join
  ```python
  dataframe_1.merge(dataframe_2, on='keys', how='inner')
  ```
- ### Outer join
  ```python
  dataframe_1.merge(dataframe_2, on='keys', how='outer')
  ```
- ### Left join
  ```python
  dataframe_1.merge(dataframe_2, on='keys', how='left')
  ```
- ### Right join
  ```python
  dataframe_1.merge(dataframe_2, on='keys', how='right')
  ```

  
