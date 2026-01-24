# Implementation: E-commerce Order Aggregator Service

## Overview
Build a microservice in Go that tracks order changes and generates customer-facing summaries.

## Background
Our current systems track orders and the events related to them (shipping updated etc.) but we lack human-readable sumamry for our customer support staff. We need a service that processes order events, fetches customer data, and generates meaningful summaries about order activities.

## Acceptance Criteria

### Usage
- [ ] Can ask for a summary on the command line
- [ ] Summaries for:
  - [ ] Order - when arriving, who's it shipping with, when shipped
  - [ ] Customer - all non-delivered orders

### Core Functionality
- [ ] Service processes order events
- [ ] Retrieves order event details and determines if order is new
- [ ] Fetches customer information and order relationships
- [ ] Generates human-readable order summaries
- [ ] Outputs formatted order information

### Technical Requirements
- [ ] Written in Go following TDD methodology
- [ ] Modular package architecture
- [ ] Mock external API calls for development
- [ ] Full test coverage with passing tests

## Technical Context

### Domain Concepts to Consider
- Order lifecycle events (placed, shipped, updated, etc.)
- Customer relationships with orders (single vs multiple)
- Summary generation based on different scenarios
- External service integration patterns

### Key Questions to Explore
- What makes a good order summary?
- How should external service failures be handled?

## Definition of Done
- Service runs without errors
- All tests pass consistently
- Clear separation of concerns between packages
- Mock data simulates realistic external calls
- Output is meaningful and human-readable

## Testing Strategy
- Unit tests for each package
- Integration tests for main workflow
- Edge cases handled (no customers, multiple customers, multiple orders per customer etc.)
- Mock external dependencies isolated

## Notes
Focus on discoverability through TDD rather than upfront architecture. Let the design emerge from test requirements and refactoring.
