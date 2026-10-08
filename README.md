# Well Construction – Certificate Digitalization System (Canvas App)

Source canvas app (format `.pa.yaml`) hasil sync dari Power Apps Studio.

- Environment: `Default-41ff26dc-250f-4b13-8981-739be8610c21`
- App ID: `2e7bdbef-139c-46a4-b57b-d20674c34c9f`
- Data source: SharePoint List `WEC STD-04 Certification`, `TLM OPSD Verification`, `CDS_Users`, `CDS_WEC`
- Flow: `FlowInAppSTD04`, `OPSDFlowInApp` (approval MSV)

## Alur kerja
1. Sync dari Studio ke `src/` lalu commit (snapshot sebelum perubahan).
2. Ubah `.pa.yaml`, push ke Studio, cek, lalu Save/Publish di Studio.
3. Commit setelah perubahan terverifikasi.

Rollback: `git checkout <commit> -- src/` lalu push ulang ke Studio.
