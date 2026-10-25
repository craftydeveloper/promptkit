# Data model

## Proposed fields

Templates need a title, prompt text, category, variables, and usage notes.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.