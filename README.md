# laba10
# Лабораторная работа №10. Обработка голоса
Лабораторная работа выполнялась для записи звуков "А" и "И" мужским голосом, а также для имитации собачьего лая.
Построены спектрограммы записи названных звуков и приведен их анализ: 
- Определение примерных минимальной и максимальной частот голоса
- Поиск основного тона
- Поиск самых сильных формант

## Спектрограмма записи звука "А" по наростающей

![](res/spectrogram_A.png)

### Анализ
**Основной тон: примерно 86 Гц** 

**Форманты:** форманта **FI** находится на частоте примерно 344 Гц, **FII** на частоте примерно 602 Гц,
**FIII** на частоте 861 Гц, **FIV** 1119 Гц


**Максимальная частоста:** 1119 Гц

## Спектрограмма записи звука "И" по наростающей

![](res/spectrogram_I.png)

### Анализ
**Основной тон: примерно 86 Гц**

**Форманты:** форманта **FI** находится на частоте примерно 86 Гц, **FII** на частоте примерно 344 Гц,
**FIII** на частоте 602 Гц, **FIV** 1894 Гц


**Максимальная частоста:** 3962 Гц

## Спектрограмма записи лая

![](res/spectrogram_gav.png)
**Основной тон: примерно 86 Гц** 

**Форманты:** форманта **FI** находится на частоте примерно 86 Гц, **FII** на частоте примерно 516 Гц,
**FIII** на частоте 947 Гц, **FIV** 1378 Гц


**Максимальная частоста:** 6546 Гц

###Выводы
**При сравнении спектрограмм звуков "И" и "А" можно увидеть, что у второй значительная часть переносящих основную энергию формант сосредоточена в диапазоне 86 --- 1894 Гц. У первой же перенос энергии происходит как на низких частотах (86 --- 861) Гц, так и на высоких (см форманту FIV 2928 Гц)** 
