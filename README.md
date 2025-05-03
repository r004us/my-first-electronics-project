# Black Pill STM32 Trainer

Проект «Black Pill STM32 Trainer» по мотивам Phil’s Lab: плата на STM32, разработанная в KiCad 8.

## Содержание репозитория
- `UDEMY 32.kicad_pro` – главный проект KiCad  
- `UDEMY 32.kicad_sch` – схема  
- `UDEMY 32.kicad_pcb` – разводка платы  
- `UDEMY 32.kicad_prl` – настройки проекта  
- `DRC.rpt` – отчёт Design Rule Check  
- `UDEMY 32.png` – 3D-рендер платы  
- `BOM.csv` – спецификация компонентов (если добавите)  

## Как открыть
1. Установить KiCad ≥ 8.0  
2. Открыть `UDEMY 32.kicad_pro`  
3. Запустить ERC и DRC, сгенерировать Gerber  
4. Прошить STM32 при помощи STM32CubeIDE
