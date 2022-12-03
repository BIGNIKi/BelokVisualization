# Визуализация структуры белка

Использованное ПО: UCSF Chimera

Выбранная структура белка: 1BZ0

# Визуализация различными способами

## Перед применением любого нижеперечисленного способа сначала необходимо отменить старые изменения (откатиться на дефолтное состояние) отображения.
file -> fetch by id -> pdb -> 1BZ0 -> fetch

## Wireframe
1. Actions -> ribbon -> hide
2. Actions -> atoms/bonds -> show
3. Actions -> atoms/bonds -> stick
![Wireframe](/wireframe.png)

## Backbone
1. Actions -> ribbon -> hide
2. Actions -> atoms/bonds -> stick
3. Actions -> atoms/bonds -> backbone only -> chain trace
![Backbone](/backbone.png)

## Spacefill
1. Actions -> ribbon -> hide
2. Actions -> atoms/bonds -> show
3. Actions -> atoms/bonds -> sphere
![Spacefill](/spacefill.png)

## Ribbons
1. Actions -> atoms/bonds -> hide
2. Actions -> ribbon -> show
![Ribbons](/ribbons.png)

## Molecular surface
1. Actions -> atoms/bonds -> hide
2. Actions -> ribbon -> hide
3. Actions -> surface -> show
![Molecular surface](/molecularSurface.png)

# Раскраска структур

## Цветовой моделью CPK
1. Actions -> atoms/bonds -> show
2. Actions -> ribbon -> hide
3. Actions -> atoms/bonds -> sphere
4. Actions -> color -> by element
![CPK coloring](/cpkСoloring.png)

## Различными цветами по доменам (частям) белка
1. Actions -> atoms/bonds -> show
2. Actions -> ribbon -> hide
3. Actions -> atoms/bonds -> sphere
4. Actions -> color -> none
5. Select -> chain -> A; Actions -> color -> red
6. Select -> chain -> B; Actions -> color -> orange red
7. Select -> chain -> C; Actions -> color -> orange
8. Select -> chain -> D; Actions -> color -> yellow
![Domen coloring](/domenColoring.png)
