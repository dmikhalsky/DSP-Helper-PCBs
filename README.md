Комбо-плата для различных DSP проектов на базе чипов AD.
На плате:
1. DC-DC 3.3в конвертер питания на базе микросхемы ADP3338 (используется в evalution board на базе ADAU1467, ультра-низкий коэффициент шума) + повышающий импульсный DC-DC  5в/12в конвертер для питания ОУ (универсальное посадочное место, например Mornsun A0512S-1WR3)
2. DC-DC LDO +12В/-12В на базе tps7A3001/tps7A4901 для малошумного питания ОУ после импульсного DC-DC
3. 2 платы ОУ на базе OPA2134 и фильтра 2-го порядка с MFB-топологией*
4. 2 платы ОУ на базе линейного драйвера DRV602/603 и фильтра 2-го порядка с MFB-топологией*
5. конвертер TOSLINK -> SPDIF на базе PLR135T

ВАЖНО: на данный момент проверены и работают части (1), (3) и (5)

В в папке Simulation находится файл для программы TINA-TI для расчета параметров фильтра и подбора номиналов

В папке "Individual PCBs" находятся схемы каждой подплаты и отдельные KiCAD-файлы. Эти KiCAD не протестированы и могут содержать ошибки.

**Рабочим является только комбо-файл в корневой папке**

