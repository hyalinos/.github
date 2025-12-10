# Hyalinos

**A transparent type inference framework for Pharo Smalltalk**

Hyalinos integrates ecosystem of type inference tools and collaborative knowledge on elicitated types. Together, they provide seamless IDE integration for discovering, sharing, and utilizing type information during development.

## Components

Hyalinos combines two complementary components:

- **HYPHE** - A hybrid type inference framework that aggregates types from multiple sources
- **Mycelium** - A collaborative type knowledge storage system

HYPHE performs multi-source type inference by integrating:

- Existing Pharo type inference tools
- Type heuristics
- Offline tests profiling

The results are merged using diferent merging strategies (confidence-based, tiered, consensus).

Mycelium extends HYPHE by enabling community-wide type knowledge sharing:

- Stores inferred types in GitHub repositories
- Synchronizes between local and remote type storage
- Allows users to share type discoveries

Hyalinos integrates directly into the Pharo IDE, providing:

- Interface for running inference
- Choosing packages, confidence levels, merging strategies for the analysis
- Subscribing repositories to trigger analysis on changes
- Type hints for methods return types during investigation
- Visual indicators for type confidence levels

## ICPC
For ICPC artefact please go to [ICPC](https://github.com/hyalinos/icpc)


