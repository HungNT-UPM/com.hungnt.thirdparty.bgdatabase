# HungNT 3rd-party: BG Database

Asset gốc: [BG Database (BansheeGz)](https://assetstore.unity.com/packages/tools/integration/bg-database-data-editor-with-google-sheets-and-excel-syncing-112262)

Database NoSQL, in-memory, không cần SQL — quản lý dữ liệu game (config, level, item...) ngay trong Editor, hỗ trợ export/import Excel/OpenOffice và Google Sheets.

## Cài đặt

**manifest.json** — thêm vào mục `dependencies`:

```json
"com.hungnt.thirdparty.bgdatabase": "https://github.com/HungNT-UPM/com.hungnt.thirdparty.bgdatabase.git"
```

**Package Manager** — `Add package from git URL...`:

```
https://github.com/HungNT-UPM/com.hungnt.thirdparty.bgdatabase.git
```

## Note

- Asset đóng gói dạng DLL precompiled (giữ nguyên drop-in), namespace gốc `BansheeGz.BGDatabase`.
- Runtime: `BGDatabase.dll`. Editor: `BGDatabaseEditor.dll` + plugin Google Sheets (`BGDatabaseGoogleSheetsEditor`).
- Mở cửa sổ chỉnh sửa database: menu `Tools > BansheeGz > BGDatabase`.
- Phiên bản asset: 1.8.8 (build 2023.12.17).
