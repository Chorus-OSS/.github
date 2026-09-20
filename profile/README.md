# TL;DR: Archived, Chorus has moved to [Bedrock Crustaceans](https://bedrock-crustaceans.org).

> Chorus started as a hard fork of PowerNukkitX, ported from Java to Kotlin. The original motivation was to have a Bedrock server that was safer and nicer to work on. Java was the main issue, and Kotlin could fix a lot of its problems while preserving the foundation that already existed.
> 
> Much of the inherited code was replaced with pure Kotlin versions, the most notable being the [Protocol](https://github.com/Chorus-OSS/Protocol) library and the [RakNet](https://github.com/Chorus-OSS/RakNet) networking layer, both of which were completed. Focus then moved on to converting blocks, items, and entities to be data-driven, with multiplatform support planned beyond that.
> 
> As work went on, these goals became increasingly unfeasible. The original inheritance-based architecture was so deeply rooted in the codebase that the migration meant first writing all the data-driven systems from scratch, and then going through and tediously ripping out and rebuilding all the existing implementations with those new systems. Multiplatform made it worse, since every remaining JVM-bound dependency, such as LevelDB, would have needed its own pure Kotlin reimplementation first. That would have taken far more work than a rewrite ever would, while still carrying technical debt inherited from the original Java codebase. As a single maintainer who had already poured an enormous amount of work into the port and everything since, it stopped being worth it, so the project was archived.

> [!IMPORTANT]
> Chorus now lives on in Rust, under the [Bedrock Crustaceans](https://bedrock-crustaceans.org) organization, with the same goals but a completely different design. Rust is faster, has a great ecosystem, and is vastly better overall. Contributions are welcome.
> 
> - **Bedrock Crustaceans**: https://bedrock-crustaceans.org
> - **Chorus**: https://bedrock-crustaceans.org/chorus

---

### These repositories are read-only and will receive no further updates. Please update any links, forks, or dependencies.
