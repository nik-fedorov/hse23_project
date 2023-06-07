# hse23_project

Ссылка на колаб с кодом построения таблицы с evalue и heatmap: https://colab.research.google.com/drive/1h8ZM1nwdf2RZKs2eQj6CJMt_N8_kXwUG?usp=sharing

## Описание белка

Я выбрал ген **RNF168**. Он кодирует белок убиквитинлигазы E3, которая содержит домен RING finger, содержащийся в ряде функционально разных белков, вовлеченных в процесс взаимодействия между белками и ДНК. Этот белок также участвует в репарации двухцепочечного разрыва ДНК (DSB). Мутации в этом гене приводят к синдрому Риддла.

RNF168:
- ставит модификацию убиквитинизации лизинов гистона H2A
- не входит в белковые комплексы
- имеет наибольшую экспрессию в *семеннике* (TPM=45.10) и *костном мозге* (TPM=29.62)

График экспрессии RNF168:

![image](https://github.com/nik-fedorov/hse23_project/assets/87883391/638c5467-01ba-44e1-8a31-4457039a723d)

Доменная структура RNF168:

![image](https://github.com/nik-fedorov/hse23_project/assets/87883391/f8645985-09aa-4c75-86a4-561fb219234a)

Ссылки, подтверждающие связь RNF168 с модификацией гистона H2A:
- https://bmcmolbiol.biomedcentral.com/articles/10.1186/1471-2199-10-55
- https://www.nature.com/articles/s41467-020-16307-4


## Выравнивание гистонов с помощью программы MEGA

### H2A

<img width="1426" alt="H2A" src="https://github.com/nik-fedorov/hse23_project/assets/87883391/97a88cd9-e4c0-478d-9947-dfa4b578185a">

### H2B

<img width="1435" alt="H2B" src="https://github.com/nik-fedorov/hse23_project/assets/87883391/09afe64c-3195-4973-892e-4a6e0051aa73">

### H3

<img width="1419" alt="H3" src="https://github.com/nik-fedorov/hse23_project/assets/87883391/bd8286c6-3af9-43df-bc11-bcc44a61c865">

### H4

<img width="1439" alt="H4" src="https://github.com/nik-fedorov/hse23_project/assets/87883391/108958b3-c344-49a1-a7dc-2babd26f4d4f">

## Итоговые таблицы и тепловая карта

e-value:

![image](https://github.com/nik-fedorov/hse23_project/assets/87883391/9f740c02-5542-4093-8d23-2e001628f008)

$-\log(evalue)$:

![image](https://github.com/nik-fedorov/hse23_project/assets/87883391/b8fbe8df-bdef-450e-b2b7-6ba4794051dd)

Heatmap:

![image](https://github.com/nik-fedorov/hse23_project/assets/87883391/050f8840-d314-472e-aee3-6a7526ff6c65)

## Вывод

По тепловой карте видно, что белок RNF168 появился лишь у многоклеточных позвоночных. 
