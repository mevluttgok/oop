## Diyagram
```
         +-----------------------+
         |      HavaYoluSirketi  |
         +-----------------------+
         | - kimlik              |
         | - ucaklar: Ucak[]     |
         +-----------------------+
                    / \
                     |
                     |
            +----------------+
            |       Ucak     |
            +----------------+
            | - tip: string   |
            | - calisiyor     |
            | - onarimda      |
            +----------------+
                    / \
                     |
                     |
         +----------------------+
         |         Ucus         |
         +----------------------+
         | - kimlik             |
         | - kalkisYeri: string |
         | - varisYeri: string  |
         | - kalkisSaati       |
         | - varisSaati        |
         | - pilot: Pilot       |
         | - yardimciPilot: Pilot|
         +----------------------+
                    / \
                     |
                     |
            +---------------+
            |      Pilot    |
            +---------------+
            | - ad: string   |
            | - deneyim: int |
            +---------------+
                    / \
                     |
                     |
         +------------------+
         |     Havaalani    |
         +------------------+
         | - kimlik         |
         | - isim: string   |
         +------------------+
```