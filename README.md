# AnyConsole

AnyConsole turns console games you own into native programs for your computer. It reads a dump you made of your own game,
recompiles the game's code ahead of time for your machine, and runs it on a native runtime that provides what the console's
operating system and graphics driver would. Every instruction the game runs is compiled code for your own CPU and GPU.

The aim is preservation: a game you bought should keep running long after the hardware it shipped on is gone, at native speed, on
the computers people actually have.

> **Status: in development.** There is no public release yet. The first one will appear here.

## Consoles

| Console | Status |
|---|---|
| Nintendo Switch and Switch 2 | in development |
| PlayStation 5 | in development |
| Xbox Series X and Series S | in development |

## How it works

1. **Intake.** You point AnyConsole at a dump of your own game. It identifies the title and version and leaves the game's files
   where they are.
2. **Recompile.** The game's CPU code is translated into native code for your machine, ahead of time. Its GPU shaders are
   translated for your graphics API: Vulkan, or Metal on a Mac.
3. **Run.** A native runtime provides what the game expects from the console: its system services, files and saves, input, audio
   and graphics.

Nothing from a game is ever distributed: everything game-derived is made on your own computer, from your own copy.

## What you need

- A game you own, dumped from your own console. AnyConsole includes no games, keys, firmware or other copyrighted console files,
  and it does not help you obtain them.
- A 64-bit Windows, macOS or Linux computer with a GPU that supports Vulkan (or Metal on a Mac).

## Community

Questions, help and news: the [AnyConsole Discord](https://discord.gg/8jmS5kJMYA).

## License

AnyConsole is licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE), with its required notices. In short:

- **Noncommercial only.** You may use, study, change and share it for any noncommercial purpose, keeping the credit line.
- **No commercial software.** No part of AnyConsole may be incorporated into commercial software, or into any product, service or
  build that is sold, charged for or monetised in any way. Selling it, charging for access or features, advertising revenue, and
  asking for or accepting donations, tips, sponsorships or crowdfunding in connection with it are all commercial use and are not
  permitted.
- **No relicensing.** AnyConsole is not available under MIT, GPL or any other terms, and nobody but its copyright holder may
  license it differently. Every copy, fork and derivative stays under the PolyForm Noncommercial License 1.0.0 with its required
  notices.

See [LICENSE](LICENSE) for the full terms.

---

AnyConsole is not affiliated with, endorsed by or sponsored by any console maker or game publisher. All trademarks belong to
their respective owners.
