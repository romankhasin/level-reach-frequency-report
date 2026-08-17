# Level Reach & Frequency Report

Отдельный модуль Level Digital Hub для анализа дедуплицированного охвата и частоты по данным Target Ads.

## Структура отчёта

- Level Group Total
- медиаканалы: Programmatic / Smart TV / Маркетплейсы / Медийка / Target
- объекты Level Group
- внутри каждого объекта — собственный Total и разбивка по тем же каналам

Reach считается по уникальным `InteractionDeviceID` отдельно на каждом уровне. Охваты строк не суммируются.

Текущий пилотный период: июль 2026.
