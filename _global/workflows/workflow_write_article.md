# Workflow: Write a Complete Article

## Trigger
User akan meminta: *"Tolong tulis artikel untuk [SITE_ID] dengan topik [X]"*

## Step-by-Step Execution

### Step 1: Load Context
- Baca `_sites/[SITE_ID]/_site_identity.md` (WAJIB).
- Baca `_sites/[SITE_ID]/_editorial_policies.md`.
- Baca `_sites/[SITE_ID]/topic_clusters/topic_clusters.md` (untuk cek apakah topik ini sudah ada cluster-nya).

### Step 2: Research & Brief
- Ikuti `keyword_research_workflow.md` untuk menentukan keyword utama.
- Buat Content Brief mengikuti `content_brief_template.md`.

### Step 3: Writing Draft
- Tulis draft berdasarkan `writing_templates.md`.
- **PERHATIAN:** JANGAN TERJEMAHKAN! Tulis langsung dalam bahasa site (EN/ID) dengan gaya bahasa yang natural.

### Step 4: Humanization
- Baca ulang draft.
- Terapkan `de_ai_ification_techniques.md` (hapus kata-kata klise AI).
- Periksa dengan `human_editing_checklist.md`.

### Step 5: Visual Preparation
- Siapkan saran gambar/visual sesuai `visual_standards.md`.
- (Opsional) Jika AI bisa generate gambar, hasilkan sesuai spesifikasi.

### INTERNAL LINK OTOMATIS (WAJIB)
- Setiap artikel WAJIB menyisipkan **1 (satu) tautan internal** ke kategori utama website yang bersangkutan.
- Tautan harus disisipkan secara **natural dan kontekstual** di dalam tubuh paragraf, BUKAN hanya ditempel di akhir artikel tanpa konteks.
- Gunakan anchor text yang bervariasi, tidak harus selalu nama kategori mentah.

#### Daftar Kategori Utama per Site
| Site ID | Kategori Utama | URL Target |
|---|---|---|
| **KITIRAN** | AI untuk Bisnis UMKM | `https://kitiranmedia.com/category/ai-untuk-bisnis-umkm/` |
| **CIPTA** | Social Media Strategy | `https://ciptavisual.com/category/social-media-strategy/` |
| **IDENUSA** | AI untuk Kreator | `https://idenusa.com/category/ai-untuk-kreator/` |
| **DEPOTOPIC** | Technology Trends | `https://depotopic.com/category/technology/` |

#### Cara Penyisipan yang Benar (CONTOH)
Jika menulis artikel tentang "Cara Edit Video Cepat" untuk KITIRAN:
> "Selain mengedit video, UMKM juga perlu strategi konten yang matang. **Kami sudah membahas berbagai trik pemasaran digital di kategori [AI untuk Bisnis UMKM](https://kitiranmedia.com/category/ai-untuk-bisnis-umkm/)** yang bisa kamu terapkan langsung."

#### LARANGAN Internal Link
- ❌ Jangan menyisipkan lebih dari 1 link kategori dalam satu artikel.
- ❌ Jangan menulis link sebagai full URL mentah tanpa anchor text (misal: `https://...`).
- ❌ Jangan memaksa link jika benar-benar tidak ada celah konteks (walaupun seharusnya selalu ada celah karena topiknya masih satu niche).

### Step 6: Final Output
- Gabungkan semua hasil (teks + saran visual).
- Simpan dalam format Markdown.
- Sertakan checklist `pre_publish_checklist.md` di akhir untuk memastikan user bisa langsung publish.

### Step 7: Versioning
- Simpan file dengan format `YYYY-MM-DD-topik_v1.md` di folder `_sites/[SITE_ID]/articles/` (buat folder jika belum ada).

## Rules of Engagement
- Jika user tidak menyebut Site ID, TANYAKAN: *"Untuk website mana artikel ini?"* (CIPTA, IDENUSA, KITIRAN, DEPOTOPIC).
- Jangan pernah menggabungkan 2 site dalam 1 artikel.
