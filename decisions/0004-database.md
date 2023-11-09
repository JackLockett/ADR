# Viewpoint - Database

## Status

Accepted.

## Context
 
Appropriate data storage is required.

## Decision

Opted for a non-relational database because of the quantity of reads outweighing the number of complex writes.

## Consequences

Complex writes will still be performed, albeit less frequently than reads. They will still occur when importing timetabling and module data.