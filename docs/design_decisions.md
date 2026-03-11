# Design Decisions Log

## Decision 1: Google Colab as Development Environment
- **Date**: 2026-03-11
- **Context**: Need GPU for deep learning
- **Decision**: Use Google Colab for all development
- **Rationale**: Free GPU access, 25GB RAM, easy sharing with supervisor

## Decision 2: NSL-KDD as Primary Dataset
- **Date**: 2026-03-11
- **Context**: Need benchmark dataset for IDS evaluation
- **Decision**: Start with NSL-KDD (smaller), test on CICIDS2017 later
- **Rationale**: NSL-KDD is 100MB vs CICIDS2017 is 50GB - faster development
