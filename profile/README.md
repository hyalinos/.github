# Hyalinos

**A transparent type inference framework for Pharo Smalltalk**

Hyalinos integrates ecosystem of type inference tools and collaborative knowledge on elicitated types. Together, they provide seamless IDE integration for discovering, sharing, and utilizing type information during development.

## Components

Hyalinos combines two complementary components:

- **HYPHE** - A hybrid type inference framework that aggregates types from multiple sources
- **Mycelium** - A collaborative type knowledge storage system

For detailed documentation, see:
- [HYPHE Documentation](https://github.com/hyalinos/hyphe)
- [Mycelium Documentation](https://github.com/hyalinos/mycelium)


### HYPHE (Hybrid Type Inference Framework)

HYPHE performs multi-source type inference by integrating:

- Existing Pharo type inference tools
- Type heuristics from code patterns
- Runtime monitoring results
- User feedback

These diverse sources are merged using a confidence-based algorithm that weighs each source's reliability, producing robust type information even for highly dynamic code.

### Mycelium (Collaborative Type Storage)

Mycelium extends HYPHE by enabling community-wide type knowledge sharing:

- Stores inferred types in GitHub repositories
- Synchronizes between local and remote type storage
- Maintains type knowledge across package versions
- Allows users to share type discoveries

## IDE Integration

Hyalinos integrates directly into the Pharo IDE, providing:

- Type information during coding
- Type hints during method investigation
- Visual indicators for type confidence levels

