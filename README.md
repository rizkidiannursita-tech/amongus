# Among Us – English Club (Fixed-4)

Perubahan utama:
- Payload menyertakan `imp` (daftar hash impostor) → Player tidak menghitung ulang, 100% sinkron dengan Admin.
- Player terkunci jika ada `payload` atau `?mode=player`.
- Peringatan di Admin jika jumlah pemain < jumlah impostor.

Build: `vite build` → `dist/`
Deploy: Vercel (Install OFF, Build `vite build`, Output `dist`).
