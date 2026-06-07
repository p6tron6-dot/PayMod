PayMod - Fabric Pay Command Mod
================================

INSTALLATIE & BUILD:

1. Download en unzip PayModFabric.zip
2. Open command prompt/terminal in de PayModFabric folder
3. Zorg dat je Java 21+ hebt geïnstalleerd
4. Run: gradlew build (op Windows) OF ./gradlew build (op Mac/Linux)
5. De JAR file wordt gemaakt in: build/libs/paymod-1.0.0.jar

6. Place paymod-1.0.0.jar in je Minecraft mods folder
   - %APPDATA%/.minecraft/mods (Windows)
   - ~/Library/Application Support/minecraft/mods (Mac)
   - ~/.minecraft/mods (Linux)

7. Start je Minecraft launcher met Fabric 1.21.1

GEBRUIK:

/pay <spelernaam>

Voorbeeld:
/pay Steve
/pay Alex

Dit registreert dat die speler heeft "betaald". De betaalde status wordt opgeslagen in het RAM (niet persistent).

FEATURES:
- ✓ Simpel /pay commando
- ✓ Bericht naar speler als ze betaald zijn
- ✓ Console logging
- ✓ Controleer of speler al betaald heeft (duplicate check)
- ✓ Werkt op multiplayer servers

VERDERE AANPASSINGEN:

Wil je dat de betaalde status persistent is (opgeslagen blijft)?
- Dit kan met NBT data opslag, vraag me dan!

Wil je dat spelers met bepaalde commands/items niet meer kunnen gebruiken als ze niet betaald hebben?
- Ik kan permission checks toevoegen!
