# Pokémon Nuzlocke Tracker

## description

This Pokémon Nuzlocke Tracker is an application designed to assist players in managing and tracking Nuzlocke runs across the main-line Pokémon games.  
Recognizing that extended play sessions are often difficult to schedule, this tool aims to provide a convenient way to record run progress, encountered Pokémon, team compositions, and achievements.  
This project utilizes Kotlin Multiplatform Mobile (KMM) to target both Android and iOS devices from a shared codebase.

This project is **Free and Open Source**, meaning the source code is publicly available and can be used, modified, and distributed under the terms of the **GNU General Public License version 3 only** (GPLv3).

## motivation

Balancing a full-time job with Nuzlocke playthroughs can be challenging.  
Maintaining consistent progress across multiple short sessions requires a reliable tracking method.  
Previously, I relied on an app that has since been removed from app stores, and its data was lost during a phone migration.  
This project aims to recreate and enhance that functionality, providing a more robust and future-proof solution for tracking Nuzlocke runs.

### Core Features (High Priority)

1.  **Encounter Tracking:**  Record Pokémon encounters, noting whether they were caught or escaped.
2.  **Encounter Management:** Support both pre-made encounter lists (based on game data) and custom encounter lists (for variant runs or specific rulesets).
3.  **Team and Storage Management:** Dedicated pages for managing the current team composition, the PC box, and the graveyard (for fainted Pokémon).
4.  **Progress Tracking:** A screen to track badges earned and overall game completion.
5.  **Game Support:** Initially support games up to Generation 5 (including remakes).
6.  **Multiple Save Management:**  Allow users to manage multiple concurrent Nuzlocke runs.

### Secondary Features (Low Priority / Optional)

1.  **Pokémon Images:** Display images for encountered Pokémon.
2.  **Detailed Pokémon Information:**  Provide access to detailed information about each Pokémon (stats, abilities, etc.).
3.  **Move Editor:**  Allow users to edit or customize move sets (useful for challenge runs).
4.  **Damage Calculator:**  Integrate a basic damage calculator.
5.  **Extended Game Support:**  Future support for games beyond Generation 5, including the recently announced Generation 10 (and beyond as they are released).

## Technical Design (Initial Outline)

*   **Language:** Kotlin (using Kotlin Multiplatform Mobile)
*   **Platforms:** Android and iOS (initially)
*   **Development Environment:** IntelliJ IDEA with the Kotlin Multiplatform plugin.  Android Studio may be used for platform-specific Android development.
*   **Version Control:** Git, hosted on GitHub.
*   **Shared Code:** Business logic, data models, and core functionality will reside in the shared Kotlin code.
*   **Platform-Specific Code:** UI implementation and platform-specific features will be handled in separate modules for Android and iOS.
*   **Data Storage:**  A suitable local database solution will be chosen for persistence (e.g., SQLDelight).

## Future Considerations

*   **Cloud Sync:** Explore the possibility of cloud synchronization for cross-device access and backup.
*   **Community Features:**  Consider features to allow users to share custom encounter lists or rulesets.

## Project Roadmap (Initial Draft)

*   **Phase 1:** Core feature implementation (Encounter Tracking, Team Management, Progress Tracking) for Generation 3 games (as a proof of concept).
*   **Phase 2:** Expand game support to Generations 4 and 5.
*   **Phase 3:** Implement Secondary Features (Pokémon Images, Detailed Information, etc.).
