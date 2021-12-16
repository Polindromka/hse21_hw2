# hse21_hw2
Ссылка на первый ноутбук:
```
https://colab.research.google.com/drive/1s8zAmDGTibaqXoyCxUXGuyV5fwcu_RCH?usp=sharing
```
Ссылка на второй ноутбук:
```
https://colab.research.google.com/drive/1dNfrDDYxWdmeuTCgTqyADfYOa7iX_qNe?usp=sharing
```
***Статистика:*** \
Общее кол-во предсказанных генов: 
```
!grep '>' proteins.fasta | wc -l
```
**3565** \
Кол-во генов, аннотированные с помощью сравнения с бактерией MIL-1: 
```
!wc -l proteins.with_hits_from_MIL_1.txt
```
**3281** \
Количество генов, аннотированных с помощью БД SwissProt:
```
!cut -f 1 scaffolds.hits_from_SwissProt.txt | sort | uniq | wc -l
```
**52** \
Кол-во белков остались без аннотации функции: 
```
!grep '>' proteins.without_MIL_1.fasta | wc -l
```
**284**
