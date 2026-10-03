# Tiếng Vitalia (Vitalische)

> **Website tài liệu:** [justlimorina.github.io/vitalian-language](https://justlimorina.github.io/vitalian-language/)

## Chạy website local

```sh
npm install
npm run dev
```

Astro lấy nội dung trực tiếp từ `docs/` và `samples/`. Mỗi lần push lên nhánh `main`, GitHub Actions sẽ build và deploy website. Để bật deploy lần đầu, vào **Settings → Pages** của repository và chọn **GitHub Actions** làm build and deployment source.

```sh
npm run build
npm run preview
```

---

Ngôn ngữ xây dựng (Conlang) cho quốc gia giả tưởng **Vitalia**, lấy cảm hứng từ **tiếng Anh trung đại (Middle English)** và phát triển thành hệ thống riêng về chính tả, ngữ âm và ngữ pháp.

---

## 🌟 Tổng Quan Ngôn Ngữ
- **Tên tiếng Việt**: Tiếng Vitalia
- **Tên tiếng Anh**: Vitalian language
- **Nội danh (Endonym)**: *Vitalische* /viˈtaː.li.ʃə/
- **Phả hệ nội bộ**: 
  - **Tiếng Vitalia Cổ (*Eald-Vitalisc*)**: Ngôn ngữ mẹ (tổ tiên chung thế kỷ 8–11), hòa kết cao độ (4 cách, 3 giống, Ablaut 7 lớp, 85–90% Germanic).
  - **Tiếng Silicania (*Silicanische*)**: Nhánh di cư phương Nam, bảo lưu tính chất cổ phong sâu sắc (~60–70% đặc trưng cổ: tính từ yếu *-e*, phân từ *-ende*, đối lập *ye/you*, phân biệt *th/dd*, tiếp nhận Cyrillic Aratilia).
  - **Tiếng Vitalia hiện đại chuẩn (*Standard Vitalische*)**: Dạng văn học chuẩn hóa thế kỷ 13–15, tinh giản động từ mạnh, chuẩn hóa quá khứ yếu *-ede*, tiếp nhận ~30% từ vựng Romance triều đình.
  - **Phương ngữ Limorina (*Limoriniene*)**: Dạng đô thị hiện đại của vùng thủ đô, cách tân ngữ âm (`Â/â`, `ui`), tính từ bất biến, gộp đại từ *jous*, tiếp nhận phụ tố du mục *-lith*.
- **Nền tảng**: Middle English (thế kỷ 12–15) và Old English (cho tầng cổ), với các quy tắc âm vị và hình thái được điều chỉnh thành hệ thống riêng của Vitalia.
- **Cấu trúc từ vựng cốt lõi**: ~70% Gốc Germanic – ~30% Gốc Latinh/Romance (riêng tầng Cổ đạt 85–90% Germanic).
- **Trật tự từ**: SVO cơ bản, hỗ trợ linh hoạt quy tắc đảo ngữ V2 khi thành phần trạng ngữ đứng đầu câu (tầng Cổ có thêm SOV trong mệnh đề phụ thuộc).

---

## 📚 Mục Lục Tài Liệu

1. [**Hệ thống Ngữ âm & Chính tả (Phonology & Orthography)**](docs/standard/phonology.md)
   - Quy tắc nguyên âm đôi, nguyên âm dài (`ie`, `ou`, gấp đôi chữ cái).
   - Âm schwa (`y` và `-e`).
   - Phân biệt `ch` (/tʃ/ ở đầu, /x/ ở giữa/cuối) và `-tch` (/tʃ/ ở cuối).
   - Âm `sch` (/ʃ/) và phát âm tổ hợp phụ âm cổ (`kn-`, `gn-`).

2. [**Ngữ Pháp Tiếng Vitalia (Grammar)**](docs/standard/grammar.md)
   - Hệ thống chia động từ: Thì hiện tại (`-e`, `-es`), thì quá khứ yếu (`-ede`), quá khứ phân từ (`ge-` / `geh-`).
   - Danh động từ & phân từ hiện tại (`-inde`).
   - Trợ động từ (*haven*, *ben*, *schal*, *wille*).
   - Danh từ, mạo từ, bảng đại từ nhân xưng và quy tắc đảo ngữ V2.

3. [**Từ Vựng & Quy Tắc Cấu Tạo Từ (Lexicon)**](docs/standard/lexicon.md)
   - Phân bổ 70% Germanic và 30% Latinh.
   - Các phụ tố cấu tạo từ (*-ische*, *-litche*, *-hede*, *-dom*).

4. **Bảng 100 Từ Swadesh Cốt Lõi (Swadesh Lists)**
   - [**Tiếng Vitalia Cổ**](docs/words_list/old_vitalian/swadesh_100_old_vitalian.md): 100 từ vựng thời sơ kỳ với ký tự cổ Thorn (Þ), Eth (Ð), Ash (Æ) và Wynn (ƿ).
   - [**Tiếng Vitalia Chuẩn**](docs/words_list/standard/swadesh_100.md): 100 từ vựng căn bản nhất kèm phiên âm IPA và đối chiếu từ nguyên.
   - [**Phương Ngữ Limorina**](docs/words_list/limorinian/swadesh_100_limorina.md): 100 từ vựng theo chính tả và ngữ âm đặc thù vùng thủ đô Limorina.
   - [**Tiếng / Phương Ngữ Silicania**](docs/words_list/silicanian/swadesh_100_silicania.md): 100 từ vựng cổ phong theo chuẩn Aratilia đối chiếu Latinh và Cổ tự Kirin.

5. [**Văn Bản Mẫu & Hội Thoại (Sample Texts)**](samples/sample_texts.md)
   - Bản tuyên ngôn vương quốc và đoạn hội thoại đời thường có phiên âm IPA và dịch nghĩa.

6. **Các Phương Ngữ Khu Vực & Dạng Cổ (Dialects & Historical Forms)**
   - [**Tiếng Vitalia Cổ (*Eald-Vitalisc*)**](docs/dialects_and_old_forms/old_vitalian/readme.md): Ngôn ngữ mẹ chung (thế kỷ 8–11), bảo tồn 4 biến cách, 3 giống và 7 lớp Ablaut nguyên thủy.
   - [**Phương Ngữ Silicania**](docs/dialects_and_old_forms/silicanian/readme.md): Phương ngữ bảo lưu hệ thống biến đuôi tính từ yếu cổ (*-e*), phân biệt *th/dd* và cổ tự Kirin Aratilia.
   - [**Phương Ngữ Limorina**](docs/dialects_and_old_forms/limorinian/readme.md): Dạng đô thị hiện đại phát triển từ tiếng Vitalia chuẩn cổ với tính từ bất biến và ký tự `Â/â`.
