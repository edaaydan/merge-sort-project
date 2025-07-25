# merge-sort-project
Patika.dev Merge Sort Project
# Merge Sort Projesi

## 🔢 Adımlar

Verilen dizi:  
`[16, 21, 11, 8, 12, 22]`

**1. Böl:**  
`[16, 21, 11]` ve `[8, 12, 22]`

**2. Daha da böl:**  
`[16]`, `[21, 11] → [21]`, `[11]`  
`[8]`, `[12, 22] → [12]`, `[22]`

**3. Küçükleri sırala ve birleştir:**  
`[21] + [11] → [11, 21]`  
`[12] + [22] → [12, 22]`

**4. Ortalara gel:**  
`[16] + [11, 21] → [11, 16, 21]`  
`[8] + [12, 22] → [8, 12, 22]`

**5. Son birleşim:**  
`[11, 16, 21] + [8, 12, 22] → [8, 11, 12, 16, 21, 22]`

---

## ⏱ Big-O Gösterimi

- **En iyi:** O(n log n)  
- **Ortalama:** O(n log n)  
- **En kötü:** O(n log n)

---

## 📌 Kod Kullanımı

Python'da çalıştırmak için `merge_sort.py` dosyasını çalıştırabilirsin.
