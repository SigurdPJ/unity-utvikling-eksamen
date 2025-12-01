# Forest Orbs

**Utviklet av Amalie Sanchez Ulriksen og Sigurd Jongers**

**Forest Orbs** ble utviklet som del av eksamensoppgaven i **PG2202 Unity-utvikling (Vår 2025)** ved **Høyskolen Kristiania**. Oppgaven gikk ut på å utvikle et 3D-spill i Unity med vekt på både interaktivitet og teknisk gjennomføring. Prosjektet skulle demonstrere våre ferdigheter innen spilldesign og programmering, samt forståelse for spillutviklingsprosessen.

**Spillet er deployet på Github-Pages her:** https://sigurdpj.github.io/Eksamen-unity-utvikling/


## Om spillet

Forest Orbs er et "firstperson" utforskingsspill, hvor spilleren utforsker en mystisk skog. Målet med spillet er å lyse opp 20 svevende orbs ved å lyse på dem med lommelykt. I skogen er det nysgjerrige spøkelser som jager spilleren hvis de kommer for nærme. Spillet er en vri på tradisjonelle skytespillmekanikker, uten vold.

## Hovedfunksjoner

- Førstepersons utforskning med bevegelse og lommelykt
- Samle lysende Orbs for å vinne spillet
- Åpne/lukke brev og interaktive objekter
- Dynamisk lydsystem via egen `SoundManager`
- AI-spøkelser som patruljerer og jager spilleren
- Egen startmeny med håndtegnet grafikk
- Flere scener med unike bakgrunnslyder
- Animasjoner på spøkelser og dyr


## Teknologi og systemer

- **Unity-versjon:** 6000.0.33f1
- **Programmeringsspråk:** C#
- **AI:** NavMesh + Finite State Machine (Patrol/Chase)
- **Brukergrensesnitt:** Canvas, Panels, Buttons, Text
- **Lyd:** AudioSource, SoundManager og ButtonSound

    
### Egen C#-kode

`ButtonSound.cs`, `ExitGame.cs`, `FlashLightToggle.cs`,  
`FloatingOrb.cs`, `GameWon.cs`, `GhostController.cs`,  
`MainMenu.cs`, `ReadLetter.cs`, `SelectableObject.cs`, `ShootRay.cs`


## Unity-komponenter

- Rigidbody, Collider, Mesh Renderer
- NavMeshAgent, NavMeshObstacle
- Canvas/UI-systemet
- Skybox, tåke og lyskilder
- Materialer, tags og flere scener


## Gratis assets vi har brukt

- [Little Ghost Lowpoly Free](https://assetstore.unity.com/packages/3d/characters/little-ghostlowpoly-free-271926)
- [Low Poly Pine Forest](https://assetstore.unity.com/packages/3d/environments/low-poly-pine-forest-312113)
- [Quirky Series Free Animals Pack](https://assetstore.unity.com/packages/3d/characters/animals/quirky-seriesfree-animals-pack-178235)
- [Low Poly Wooden House in the Snow](https://assetstore.unity.com/packages/3d/environments/low-poly-woodenhouse-in-the-snow-310613)
