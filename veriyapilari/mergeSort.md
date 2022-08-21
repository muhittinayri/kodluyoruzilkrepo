# Proje-2
### [16,21,11,8,12,22] -> Merge Sort

#### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
###### Başlangıçta dizimizi ikiye bölüyoruz. Bölünen dizileri tekrar bölüyoruz. Tek eleman kalana kadar İşleme devam ediyoruz.

|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|-----------------------------------------------  |- |- |- |- |- |- |- |- |- |- |- |- |
|Diziyi ikiye bölerek yeniden yazıyoruz           |  |  |  |16|21|11|8 |12|22|  |  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Sol ve sağdaki dizileri tekrar ikiye böluyoruz.  |  |  |16|21|11|  |  |8 |12|22|  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Tek eleman kalana kadar bir kez daha bölüyoruz.  |  |16|21|  |11|  |  |8 |  |12|22|  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                 |16|  |21|  |11|  |  |8 |  |12|  |22|

|1. Adım |16|21|11|8|12|22|
|2. Adım |16|21|11|  |8|12|22|
|3. Adım |16|21|  ||11|  ||8|-|12|22|
|4. Adım |16|21|  |11|  |8|-|12|22|