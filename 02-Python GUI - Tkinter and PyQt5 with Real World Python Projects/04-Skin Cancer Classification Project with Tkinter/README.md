## Convolotional Neural Network (CNN)
Resimleri sınıflandırmak ve objeleri detect etmek için kullanılan özelleşmiş sinir ağlarına **CNN** denir. CNN 2 ana kısımdan oluşur.

1-Feature Extraction
2-Classification 

Dataset Columns:
- **lesion_id** = uniqie id'si (kullanmayacağız)
- **image_id** = kanser hücre resmin id'si
- **dx** = Öncelikle bu bir **target class** tır! dx: Kanser hücresinin tipidir. 7 farklı class tipi var, bunlar: nv, mel, bkl, bcc, akiec, vasc, df)
- **dx_type** = kanser hücresinin resminin nasıl elde edildiği (bu bizim için çok önemli değil)
- **age** = kanser hücresine sahip insanın yaşı
- **sex** = cinsiyeti
- **localization** = kanser hücresinin alındığı bölge(scalp, ear, face, back, trunk, chest gibi vücut bölgeleri)

