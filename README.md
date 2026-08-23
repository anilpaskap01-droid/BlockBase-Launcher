# BlockBase Launcher v6 — Modpack + Sunucu Yöneticisi

Native Windows C#/.NET 8 uygulaması. npm, Node.js ve Electron kullanmaz.

## v6 yenilikleri
- Mod indirmesinde takılmayı önleyen gövde timeout'u, 3 yeniden deneme ve yüzde/MB ilerleme göstergesi.
- Modpack içindeki modları elle `.jar` ekleyerek yönetme.
- Modları tek tek aç/kapat (`.disabled`) ve kaldırma.
- **Sunucularım** bölümü.
- Vanilla / Fabric / Forge / NeoForge / Quilt sunucusu oluşturma.
- Minecraft ve loader sürüm listelerini internetten alma; loader sürümünü ister listeden seç ister elle yaz.
- Forge/NeoForge resmi installer ile `--installServer`; Fabric resmi server launcher; Quilt resmi installer akışı.
- Sunucu RAM, port, MOTD, max players, difficulty, gamemode, PVP, whitelist ayarları.
- Sunucu modlarını Modrinth/CurseForge'dan arayıp kurma; zorunlu bağımlılıkları da kurar.
- Yerel JAR ekleme, modpack'ten sunucuya mod kopyalama, mod aç/kapat/sil.
- Sunucu konsolu ve komut gönderme.
- Launcher EXE algılama ve modpack için oyun sürümü/loader hazırlama korunmuştur.

## Çalıştırma
`RUN_DEV.bat`

## EXE oluşturma
`BUILD_WINDOWS.bat`

Çıktı: `publish\BlockBase.exe`

> Sunucu kurulumu için uygun Java sürümü gerekir. Modern Minecraft/NeoForge sürümlerinde Java 21, bazı eski sürümlerde Java 17 gerekir. Minecraft EULA kabul edilmeden sunucu hazırlanmaz.
