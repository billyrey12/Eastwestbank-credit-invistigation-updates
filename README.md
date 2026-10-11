# EastWest Credit Investigation Updates

Public download at awtomatikong updates para sa EastWest Credit Investigation.

## Paano gamitin

1. Buksan ang [pinakabagong release](https://github.com/billyrey12/Eastwestbank-credit-invistigation-updates/releases/latest).
2. I-download ang **EastWest-Credit-Investigation-Windows.zip**, i-extract, at buksan ang **EastWest-Credit-Investigation.exe**. Maaari ring direktang i-download ang EXE.
3. Awtomatikong bubukas ang app. Lalabas lang ang download at installation progress kapag may mas bagong stable release. Kapag offline o walang update, bubuksan ang kasalukuyang app.

Windows 10/11 na may .NET Framework 4.8. Walang kailangang GitHub login, Node o Python sa receiving PC. Buksan ang launcher kapag gagamitin ang app; hindi ito tumatakbo sa Windows startup.

Pareho ang kasalukuyang local app login. Ilagay ang workbook password sa unang protected Excel operation; sa memory lang ng kasalukuyang page session ito mananatili. Walang plaintext passwords, customer workbooks, exported reports o historical template account records sa public package.

Naka-install ang app sa `%LOCALAPPDATA%\EastWestCreditInvestigation\app`. Pareho ang app path sa bawat update para mapanatili ang browser settings sa parehong browser/profile. Walang customer data na ina-upload ang launcher.

## Para sa publisher

Mag-build at mag-test ng mas mataas na numeric version sa private working folder. Mag-publish ng stable/latest GitHub Release na may katumbas na tag, halimbawa **v1.0.1**, at tatlong assets:

- **EastWest-Credit-Investigation.exe**
- **EastWest-Credit-Investigation-Windows.zip**
- **SHA256SUMS.txt**

Gamitin ang parehong EXE filename sa bawat release. Sinusuri ang GitHub SHA-256 digest, asset size, EXE version at bawat bundled app file bago mag-install. Kapag pumalya ang installation, ibabalik ang dating app at launcher.

Ang bagong commit lamang ay hindi magti-trigger ng update; kailangan ang published stable/latest release. Huwag i-upload ang buong working folder, internal app.zip, test fixtures o bank workbooks.
