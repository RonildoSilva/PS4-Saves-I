# PS4-Saves-I

Saves de PlayStation 4 — **37 títulos**, 2,0G.

Estrutura no padrão do console: `PS4/SAVEDATA/6f5440249bc89152/<CUSA>/`.
Para restaurar, copie a pasta `PS4` para a raiz de um pendrive formatado em exFAT
e use *Configurações → Gerenciamento de dados salvos → Armazenamento USB*.

> Os saves são vinculados à conta `6f5440249bc89152`. Em outra conta exigem
> re-assinatura (Save Wizard, Apollo ou similar).

Títulos marcados com ⚠️ estão em zip dividido em volumes de 90 MB, porque o
GitHub rejeita arquivos acima de 100 MB. Para restaurar, junte os volumes antes:

```bash
zip -s 0 CUSA09209.zip --out completo.zip   # junta .z01, .z02... + .zip
unzip completo.zip -d CUSA09209
```

| | Título | CUSA | Slots | Tamanho |
|---|---|---|---:|---:|
| <img src="assets/icons/CUSA00069.jpg" width="60"> | Rayman Legends | `CUSA00069` | 1 | 10,0 MB |
| <img src="assets/icons/CUSA00081.webp" width="60"> | Pinball Arcade | `CUSA00081` | 1 | 10,0 MB |
| <img src="assets/icons/CUSA00419.webp" width="60"> | Grand Theft Auto V | `CUSA00419` | 6 | 118,0 MB |
| <img src="assets/icons/CUSA00498.webp" width="60"> | The Witness | `CUSA00498` | 1 | 3,0 MB |
| <img src="assets/icons/CUSA00504.jpg" width="60"> | Beyond: Two Souls | `CUSA00504` | 2 | 36,0 MB |
| <img src="assets/icons/CUSA00694.webp" width="60"> | Journey | `CUSA00694` | 1 | 10,0 MB |
| <img src="assets/icons/CUSA00744.webp" width="60"> | Minecraft: PlayStation®4 Edition ⚠️ zip dividido | `CUSA00744` | 3 | 267,1 MB |
| <img src="assets/icons/CUSA00967.webp" width="60"> | Mortal Kombat X | `CUSA00967` | 3 | 30,0 MB |
| <img src="assets/icons/CUSA01163.webp" width="60"> | Rocket League® | `CUSA01163` | 1 | 100,0 MB |
| <img src="assets/icons/CUSA01347.jpg" width="60"> | Assassin's Creed Chronicles: China | `CUSA01347` | 1 | 10,0 MB |
| <img src="assets/icons/CUSA01442.webp" width="60"> | Life Is Strange™ | `CUSA01442` | 4 | 40,0 MB |
| <img src="assets/icons/CUSA01623.webp" width="60"> | God of War® III Remastered | `CUSA01623` | 8 | 80,0 MB |
| <img src="assets/icons/CUSA01967.webp" width="60"> | Horizon Zero Dawn | `CUSA01967` | 13 | 63,0 MB |
| <img src="assets/icons/CUSA01975.webp" width="60"> | Plants vs Zombies GW2 | `CUSA01975` | 1 | 18,0 MB |
| <img src="assets/icons/CUSA02085.webp" width="60"> | DOOM | `CUSA02085` | 2 | 20,0 MB |
| <img src="assets/icons/CUSA02411.webp" width="60"> | Kung Fu Panda: Showdown of Legendary Legends | `CUSA02411` | 1 | 10,0 MB |
| <img src="assets/icons/CUSA02768.webp" width="60"> | Goat Simulator | `CUSA02768` | 1 | 10,0 MB |
| <img src="assets/icons/CUSA02819.webp" width="60"> | Tom Clancy's Ghost Recon® Wildlands | `CUSA02819` | 1 | 3,0 MB |
| <img src="assets/icons/CUSA02985.webp" width="60"> | LEGO® Worlds | `CUSA02985` | 6 | 145,0 MB |
| <img src="assets/icons/CUSA03349.webp" width="60"> | ABZU | `CUSA03349` | 1 | 3,2 MB |
| <img src="assets/icons/CUSA03448.webp" width="60"> | Fallout 4 | `CUSA03448` | 20 | 154,6 MB |
| <img src="assets/icons/CUSA03508.webp" width="60"> | Grand Theft Auto 3 | `CUSA03508` | 1 | 18,3 MB |
| <img src="assets/icons/CUSA04517.webp" width="60"> | F1™ 2016 | `CUSA04517` | 1 | 23,0 MB |
| <img src="assets/icons/CUSA04768.jpg" width="60"> | South Park: The Stick of Truth | `CUSA04768` | 4 | 40,1 MB |
| <img src="assets/icons/CUSA05347.webp" width="60"> | Darksiders Warmastered Edition | `CUSA05347` | 1 | 3,0 MB |
| <img src="assets/icons/CUSA05625.webp" width="60"> | Assassin's Creed® Origins | `CUSA05625` | 1 | 10,0 MB |
| <img src="assets/icons/CUSA06400.webp" width="60"> | MARVEL VS. CAPCOM: INFINITE | `CUSA06400` | 2 | 8,3 MB |
| <img src="assets/icons/CUSA07104.webp" width="60"> | RESIDENT EVIL™ CODE: Veronica X | `CUSA07104` | 1 | 18,3 MB |
| <img src="assets/icons/CUSA07820.webp" width="60"> | The Last of Us™ Part II | `CUSA07820` | 5 | 31,3 MB |
| <img src="assets/icons/CUSA09072.webp" width="60"> | DRAGON BALL FighterZ | `CUSA09072` | 2 | 62,5 MB |
| <img src="assets/icons/CUSA09209.webp" width="60"> | The Sims™ 4 ⚠️ zip dividido | `CUSA09209` | 6 | 526,1 MB |
| <img src="assets/icons/CUSA10090.webp" width="60"> | PRO EVOLUTION SOCCER 2018 LITE | `CUSA10090` | 2 | 14,4 MB |
| <img src="assets/icons/CUSA14204.webp" width="60"> | EA SPORTS™ UFC® 4 | `CUSA14204` | 4 | 72,0 MB |
| <img src="assets/icons/CUSA14655.webp" width="60"> | DRAGON BALL Z: KAKAROT | `CUSA14655` | 2 | 22,8 MB |
| <img src="assets/icons/CUSA15024.webp" width="60"> | CONTRA: ROGUE CORPS | `CUSA15024` | 1 | 3,0 MB |
| <img src="assets/icons/CUSA24659.webp" width="60"> | Yu-Gi-Oh! Master Duel | `CUSA24659` | 1 | 11,0 MB |
| <img src="assets/icons/CUSA24705.webp" width="60"> | Horizon Forbidden West | `CUSA24705` | 17 | 83,0 MB |

<sub>Gerado por `tools/build_index.sh` — não edite esta tabela à mão.</sub>
