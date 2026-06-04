# Source of Truth Strategy

## Problem

Multiple systems may contain overlapping customer information.

## Decision

A single operational system should serve as the source of truth for each business domain.

## Benefits

- Reduced inconsistencies
- Improved reliability
- Simplified troubleshooting
- Better auditability

## Engineering Principle

Business actions should only be confirmed after successful execution within the designated source-of-truth system.
