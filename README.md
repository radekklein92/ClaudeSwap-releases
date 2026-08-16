# ClaudeSwap by RETALES

Vydané verze aplikace **ClaudeSwap by RETALES** - přepínače účtů Claude Code
pro macOS. Zdrojový kód je v samostatném privátním repozitáři, sem chodí
jen hotové buildy a kanál automatických aktualizací.

## Instalace

1. Stáhnout `.dmg` z [posledního vydání](../../releases/latest).
2. Otevřít a přetáhnout **ClaudeSwap** do Aplikací.
3. Spustit.

Aplikace je podepsaná Developer ID a notarizovaná Applem, takže se otevře
normálním dvojklikem - žádné obcházení Gatekeeperu není potřeba.

Nic dalšího instalovat nemusíš. Aplikace si nese vlastní Python i nástroj
`cswap`, takže nepotřebuje ani Homebrew, ani Command Line Tools.

## Aktualizace

Aplikace se aktualizuje sama - kontroluje nové verze při startu a pak jednou
denně, a když nějakou najde, nabídne ji. Ručně jde totéž vyvolat z menu.

## Požadavky

macOS 14 (Sonoma) nebo novější, Apple Silicon.

## Soukromí

Aplikace nikam neposílá žádná data. Limity čte z účtů, které máš přihlášené
v Claude Code na svém stroji, a všechno si drží lokálně.
