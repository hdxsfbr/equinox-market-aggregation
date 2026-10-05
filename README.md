# Equinox

Cross-venue prediction market aggregation. Gauntlet AI partner project for Peak6.

## Overview

Prediction markets trade the same real-world events on multiple venues, but each venue structures and names its markets differently. There is no shared way to detect that two markets are equivalent or to compare their prices on a normalized basis.

Equinox is a feasibility study. It tests whether equivalent markets can be identified across venues and whether routing decisions between them can be simulated intelligently.

## Questions to answer

1. Is cross-venue normalization realistically achievable?
2. What architectural tradeoffs exist?
3. How complex does smart routing get in practice?

## Scope

- Fetch live market data from two venues
- Define an internal, venue-agnostic market representation
- Identify potentially equivalent markets across venues
- Simulate a routing decision between venues
- Log the reasoning behind every routing decision

UI polish is out of scope.

## Requirements

- Routing logic is deterministic
- Routing never blocks on external calls
- API failures and inconsistent data are handled gracefully
- No hardcoded venue logic in the routing layer
- Clear separation of concerns, documented assumptions, reasonable test coverage

## Stack

- Go (Python acceptable)
- GCP or local deployment

## Deliverables

- Source code
- Technical documentation
- Deployment guide
- Test results
- Demo video
- AI usage log

## Getting started

Setup instructions will be added as the project takes shape.
