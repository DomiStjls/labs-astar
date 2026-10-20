# Источники данных MovingAI

Данные для lab04_benchmarking_astar.ipynb скачаны с https://movingai.com/benchmarks/grids.html.
Правила движения и формат сценариев: https://movingai.com/benchmarks/formats.html.
Используются диагональные шаги sqrt(2), без срезания углов.

Карты и все исходные сценарии, без изменения содержимого:
- dao/arena.map и arena.map.scen — Dragon Age: Origins;
- da2/ht_chantry.map и ht_chantry.map.scen — Dragon Age 2;
- bgmaps/AR0021SR.map и AR0021SR.map.scen — Baldur's Gate II, исходные размеры.

Точные адреса архивов, дата скачивания, размеры файлов и SHA-256: sources.json.
Ноутбук сам выбирает по 100 задач из пяти групп эталонной длины с фиксированным seed.

Атрибуция: Nathan Sturtevant / Moving AI Lab.
Sturtevant, N. (2012). Benchmarks for Grid-Based Pathfinding.
IEEE Transactions on Computational Intelligence and AI in Games, 4(2), 144–148.

Лицензия данных: Open Data Commons Attribution License (ODC-By) v1.0:
https://opendatacommons.org/licenses/by/1-0/.
