# Panasonic Warehouse Air Conditioner

Monorepo yang berisi tiga aplikasi terpisah:

| Folder      | Stack                         | Keterangan        |
|-------------|-------------------------------|-------------------|
| `frontend/` | React + Vite + TypeScript     | Aplikasi web      |
| `backend/`  | ASP.NET Core Web API (.NET 9) | REST API          |
| `mobile/`   | Flutter (Dart)                | Aplikasi mobile   |

```
Panasonic Warehouse Air Conditioner/
├── frontend/   # React + Vite (TS)
├── backend/    # .NET solution (PanasonicWarehouseAC.sln)
│   └── src/PanasonicWarehouseAC.Api/
└── mobile/     # Flutter app
```

## Menjalankan

### Backend
```bash
cd backend
dotnet run --project src/PanasonicWarehouseAC.Api
# http://localhost:5293  (https://localhost:7176 dengan profil https)
```

### Frontend
```bash
cd frontend
npm install
npm run dev
# http://localhost:5173
```

### Mobile
```bash
cd mobile
flutter pub get
flutter run
```

## Prasyarat
- Node.js 20+ dan npm
- .NET SDK 9
- Flutter SDK 3.29+
