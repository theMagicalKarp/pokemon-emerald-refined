# Pokémon Emerald Refined (WIP)

<img align="right" src="./docs/assets/emerald.png" height="200px" alt="refined-logo">

This project represents a [decompilation] of the [Pokémon Emerald] video game,
undertaken with the intention of creating a [ROM Hack].

The primary objective of this ROM Hack is to elevate the _challenge_ and
_gameplay_ elements while retaining the nostalgic essence of the original game.

While doing so, the project aims to be meticulous in preserving the sentimental
quality of the original game, ensuring that long-time fans and newcomers alike
can appreciate the journey. By introducing minor **quality of life
improvements**, opportunity for **increased challenge**, and **combat balances**
the ROM Hack aims to strike a balance between honoring the classic gameplay and
offering new experiences. This meticulous blend ensures that players will
encounter familiar moments intertwined with fun and exciting new challenges.

## Changes Made

This project has identified specific elements that do not directly contribute to
the gameplay experience. By analyzing various components and aspects of the game
design, the project has pinpointed areas that might be superfluous or detract
from the core gaming experience.

The aim is to refine and optimize the game's design, ensuring that players
receive a fun and engaging experience.

- Display [Nature Stat Modifiers] in the Pokémon Summary
  - Frequently, it's frustrating to have to remember or look up natures to
    determine how a Pokémon's stats will be affected.
- Display [EV/IV Values] in the Pokémon Summary
  - This feature eliminates the need for tedious tools or resources,
    streamlining the gameplay experience and empowering players with essential
    information at their fingertips.
- Update Pokémon Move Viability
  - In an effort to enhance the enjoyment and viability of all Pokémon, we have
    reviewed and adjusted the Power, Accuracy, Typing, PP, and even secondary
    effects of each move. This revision ensures that a greater number of Pokémon
    can be deemed viable for various runs, offering a broader array of options
    when constructing teams.
- Display Pokémon movesets/base stats in the Pokédex
  - This enhancement eliminates the necessity of playing the game and searching
    for information on third-party data sources. It provides players with
    convenient in-game access to comprehensive details, enhancing their overall
    experience.
- Allow running indoors
  - By removing movement restrictions indoors, players can navigate environments
    swiftly, ensuring that transitions between indoor and outdoor settings are
    seamless and maintain a brisk pace.
- Increase Item Bag Size from 30 to 120
  - This increase not only allows players to carry more items but also reduces
    the frequency of having to manage and shuffle items between the bag and
    storage. Consequently, players can focus more on exploring and battling.
- Adjust Damage Calculatation for Dark/Ghost Type Moves
  - The calculation for Ghost-type moves now utilizes special stats rather than
    physical ones. Historically, Ghost Pokémon in earlier generations were
    designed around dealing special damage. This adjustment aims to enhance
    their effectiveness and overall enjoyment in battles.
  - Conversely, Dark-type moves now factor in physical stats instead of special
    ones. Given that Dark-type Pokémon typically excel as physical attackers,
    this change aligns more closely with their inherent strengths.
- 2 in 1 Bike
  - To minimize tedious backtracking, the features of the Mach Bike have been
    incorporated into the Acro Bike, resulting in the removal of the Mach Bike
    itself. To engage the speed-up feature previously associated with the Mach
    Bike, hold the "R" button while riding the Acro Bike. This seamless
    integration enhances navigation and streamlines the overall gameplay
    experience.
- Speed up Tedious Interactions
  - To streamline gameplay and minimize the time players spend on tedious
    interactions, such as healing Pokémon at the Pokécenter, this project has
    reduced both wait times and required player inputs for various activities.
- Ask for [Repel] Reuse After Expiration
  - Recognizing the inconvenience of frequent encounters in high-density
    regions, when a Repel wears off, players will now receive a prompt asking if
    they'd like to use another Repel from their bag if available. This aims to
    increase the usability and convenience of Repel items.
- Allow other options for [trade evolutions]
  - To remove the necessity of locking certain Pokémon behind requiring multiple
    games, alternative methods or conditions for trade evolutions will be
    introduced. This ensures that players have more flexibility in evolving
    their Pokémon without being constrained by game availability or trading with
    others.
- Remove Timings on Fishing
  - To help remove the tedious mini-game and streamline fishing for Pokémon, the
    project has removed specific timings, providing players with a smoother
    fishing experience.
- Update Summary and Battle UI to Display "Hidden Power" Power and Type
  - Players can now easily view the power and type of the "Hidden Power" move in
    both the Pokémon Summary and Battle UI, enhancing strategic decision-making
    during battles and team building.
- Update In-Game Trades
  - Modify/Add In-Game Trades to provide more unique Pokémon.

## What Remains Unchanged

While various features might enhance subsequent Pokémon titles, the project has
chosen to maintain the original charm of Gen 3 with the following decisions.

These decisions ensure that long-time fans can relive their cherished memories
while also introducing newer generations to the gameplay that defined this era
of Pokémon games. Additionally, we've focused on refining gameplay mechanics
that resonate with the core essence of Gen 3, such as the iconic Pokémon
abilities and the intricate balance between various types.

- No introduction of new Pokémon
- No addition of new types
- No creation of new moves
- No incorporation of new abilities
- Retention of single-use TMs
- No [Physical/Special split]

## Development Setup

For detailed setup instructions, please refer to [INSTALL.md](INSTALL.md).

## Acknowledgments

This project owes a considerable debt of gratitude to [pret] and their
community. For further information about pret and additional projects, visit
[pret.github.io].

> [!NOTE]
> Decompilation Target: [**pokeemerald.gba**](https://datomatic.no-intro.org/index.php?page=show_record&s=23&n=1961) `sha1: f3ae088181bf583e55daf962a92bb46f4f1d07b7`

[Decompilation]: https://en.wikipedia.org/wiki/Decompiler
[Pokémon Emerald]: https://en.wikipedia.org/wiki/Pok%C3%A9mon_Emerald
[ROM Hack]: https://en.wikipedia.org/wiki/ROM_hacking
[Physical/Special split]: https://bulbapedia.bulbagarden.net/wiki/Damage_category#Physical.2FSpecial_split
[pret]: https://github.com/pret
[pret.github.io]: https://pret.github.io/
[Nature Stat Modifiers]: https://bulbapedia.bulbagarden.net/wiki/Nature#List_of_Natures
[EV/IV Values]: https://www.smogon.com/ingame/guides/evs_ivs
[Repel]: https://bulbapedia.bulbagarden.net/wiki/Repel
[trade evolutions]: https://bulbapedia.bulbagarden.net/wiki/Trade#Pok.C3.A9mon_that_evolve_when_traded
