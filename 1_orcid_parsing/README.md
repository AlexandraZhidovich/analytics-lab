# ORCID Publications Parser

## Описание
Парсинг данных о научных публикациях автора из открытого API ORCID.

## Задача
Извлечение данных о пубикациях автора:
- год издания.
- название работы.
- DOI.
- EID.

## Инструменты
- **Python** (requests, json, pandas)
- **Jupyter Notebook**
- **ORCID Public API**

## Файлы
- `ORCID_publications_extractor.ipynb` - Jupyter ноутбук с кодом
- `orcid_year_title_doi_eid.json` (orcid_year_title_doi_eid.csv) - результат парсинга

## Результат
- Всего уникальных публикаций (названий работ) автора: 765.
- Формат данных: JSON, CSV.
- Код работает с реальным API.

## Запуск
1. Откройте `ORCID_publications_extractor.ipynb` в Google Colab.
2. Запустите все ячейки.
3. Получите актуальные данные.
