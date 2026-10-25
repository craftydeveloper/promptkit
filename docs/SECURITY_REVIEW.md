# Security review

## Product risks

Prompts can produce unsupported claims. Keep provenance and require human review.

## Baseline

Treat imported text as untrusted, bound input sizes, avoid unsafe HTML insertion, keep credentials out of client code, and verify external links. This checklist is not a security certification.