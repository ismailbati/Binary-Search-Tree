# Binary-Search-Tree

Binary Search Tree Proje sorusunun Çözümü

[patika.dev](https://app.patika.dev/ismailbati)


## Soru - 1

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız

#### Aşama - 1 Rootu belirleriz. root -> 7

#### Aşama - 2 Sonraki eleman rootumuzdan küçük olduğu için soluna yerleşir

|     |     |   7 |     |
| --- | :-: | --: | --- |
|     |  /  |     |     |
| 5   |     |     |     |

#### Aşama - 3 Diğer elemanlar da sırası ile en son işlediğimiz sayıdan küçükse soluna, büyükse sağına yerleşir

|     |     |     |     |     |     | 7   |     |     |     |     |
| --- | :-: | --: | --- | :-: | --: | --- | :-: | --: | --- | --- |
|     |     |     |     |     |   / |     | \   |     |     |     |
|     |     |     |     |  5  |     |     |     |   8 |     |     |
|     |     |     | /   |     |  \  |     |     |     | \   |     |
|     |     |   1 |     |     |     | 6   |     |     |     | 9   |
|     |  /  |     | \   |     |     |     |     |     |     |     |
| 0   |     |     |     |  3  |     |     |     |     |     |     |
|     |     |     | /   |     |  \  |     |     |     |     |     |
|     |     |   2 |     |     |     | 4   |     |     |     |     |