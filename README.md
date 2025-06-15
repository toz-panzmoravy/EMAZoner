# CHANGELOG #v0.5

## Vylepšení od vytvoření README (CZ)

- Přidány alerty na BUY a SELL signály (možnost nastavit upozornění v TradingView)
- Do tabulky přidána síla trendu (číselně v % i slovně: silný/střední/slabý/žádný)
- Do tabulky přidány základní statistiky: počet BUY/SELL signálů a průměrná délka trendu
- Pozadí grafu je nyní vybarveno pro celou zónu trvání trendu (nejen aktuální svíčku)
- Všechny značky (BUY, SELL, PEAK, END, NEUTRAL) mají čárkovanou svislou čáru ke knotu svíčky pro rychlou orientaci
- Všechny značky jsou vždy mimo tělo svíčky (nikdy uvnitř), díky offsetu
- Opraveno umístění NEUTRAL a END značek, aby byly vždy čitelné a nepřekrývaly svíčku

## Improvements since README creation (EN)

- Added alerts for BUY and SELL signals (can set up TradingView notifications)
- Added trend strength to the table (numeric % and text: strong/medium/weak/none)
- Added basic statistics to the table: number of BUY/SELL signals and average trend length
- Chart background is now colored for the entire trend zone (not just the current bar)
- All labels (BUY, SELL, PEAK, END, NEUTRAL) have a dotted vertical line to the candle wick for quick orientation
- All labels are always outside the candle body (never inside), thanks to offset
- Fixed NEUTRAL and END label placement so they are always readable and never overlap the candle 

---------

## Česká verze

Tento TradingView indikátor slouží k vizuální analýze trendů na základě dvou klouzavých průměrů EMA.

### Funkce
- Detekce a vizuální označení začátku a konce trendu (BUY, SELL, END, NEUTRAL) s unikátním ID
- Značka PEAK (vrchol trendu) pouze jednou za trend
- Všechny značky jsou odsazeny od svíček, aby byly čitelné
- V pravém horním rohu je tabulka s aktuálním trendem na více timeframe (aktuální, M15, M30, H1), stavem PEAK značek a typem offsetu
- Plně kompatibilní s různými timeframe a barvami pozadí

### Použití
Vložte kód do Pine Editoru na TradingView a přidejte na graf.

---

## English Version

This TradingView indicator provides visual trend analysis based on two EMA moving averages.

### Features
- Detects and visually marks the start and end of trends (BUY, SELL, END, NEUTRAL) with unique IDs
- PEAK (trend top) label appears only once per trend
- All labels are offset from candles for clarity
- Top-right table shows current trend for multiple timeframes (current, M15, M30, H1), PEAK label status, and offset type
- Fully compatible with various timeframes and both dark/light backgrounds

### Usage
Paste the code into the Pine Editor on TradingView and add it to your chart. 
