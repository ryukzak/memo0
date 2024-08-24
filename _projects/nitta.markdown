---
layout: page
title: NITTA
description: Tool for Hard Real-Time CGRA Application Specific Processors
category: Research pet projects
---

We develop the tool for generating and programming specialized non-von Neumann processors for cyclic execution of control and signal/data processing algorithms. These processors are based on the original Not Instruction Transport Triggered Architecture (NITTA). That allows us to:

- Provide high speed and parallel execution of irregular algorithms (where GPU is not applicable) in hard real-time (clock accuracy).
- Make the processor reconfigurable for different application domains.
- Provide a high-level language for application developers and fast compilation.

Our users can resolve the following tasks:

- Development of embedded and cyber-physical systems.
- Hardware and software testing and rapid prototyping (HIL and PIL).
- Development of programmable accelerators and coprocessors.

Key technologies: Haskell, Verilog, TypeScript, React, GitHub.

Today, the project focus on the following goals:

- developing the hardware accelerator for system dynamics and its integration into the cloud platform of our friends: [sdCloud project](https://sdcloud.io).

You can start meeting with the project by reading recent publications and viewing presentations:
- [Paper: 2021, Synthesis Method for CGRA Processors based on Imitation Model](https://www.researchgate.net/publication/350871215_Synthesis_Method_for_CGRA_Processors_based_on_Imitation_Model)
- [Report: 2021, Open Dais: Software Verification on the ASIP CAD Example or How to Trust Your Team and Yourself](https://ryukzak.github.io/2021/04/29/software-verification-on-CAD-example.html)
- [Report: 2021, NITTA: principles of work](https://ryukzak.github.io/2021/02/03/nitta-internals.html) in Russian
- [Report: 2019, LCPS Workshop: NITTA - Design Application Specific Processors](https://disk.yandex.ru/i/nllkSLEIzmf7GA) in Russian.

You can start to contribute by simple tasks, for example:

- Update all web-UI dependencies (Yarn, Typescript, React).
- Add TARGET_PATH command-line argument (Haskell).
- Fix minor bugs.

After diving into the project, you can connect to solving more complex problems:

- Machine learning usage to make decisions in the synthesis process (Python, Haskell, ML).
- Add support for more complex hardware organisation with multiple networks inside the processor (Verilog, Haskell).
- Automatisation of synthesis process testing by property-based approach (Haskell, Verilog).
- Automatisation of UI testing (Typescript).
- Development of visualization tools for a multi-level computing process (Typescript, React).
- Development of control software for the integration of a specialized processor into other information systems (Rust, Verilog, Haskell).

For details and more actual information look at issues and projects on GitHub: [GitHub](https://github.com/ryukzak/nitta)

To participate in the project, you need to contact me: <https://t.me/aleksandr_penskoi> or <aleksandr.penskoi@gmail.com>.

---

Мы создаем инструментарий для генерации и программирования специализированных не фон -- Неймановских процессоров, предназначенных для циклического исполнения алгоритмов управления и обработки сигналов/данных. Они строятся на оригинальной архитектуре NITTA (Not Instruction Transport Triggered Architecture). Это позволяет:

- обеспечить высокую скорость и уровень параллелизма для нерегулярных алгоритмов (где не используют GPU) и жесткое реальное время (с точностью до такта);
- сделать процессор реконфигурируемым под разные прикладные области;
- предоставить язык высокого уровня для прикладных разработчиков и быструю компиляцию.

Построенные при помощи нашего инструмента вычислители могут использоваться для:

- разработки встроенных и киберфизических систем;
- программно-аппаратного тестирования и быстрого прототипирования (HIL и PIL);
- разработки программируемых ускорителей и сопроцессоров.

В настоящий момент перед проектом стоят следующие цели:

- разработка аппаратного ускорителя для системной динамики и его интеграция в облачную платформу наших друзей из [sdCloud project](https://sdcloud.io).

Знакомство с проектом можно начать с чтения последних публикацией по проекту и просмотра выступлений:
- [Функциональный уход за Research Pet Project: NITTA, CGRA, Haskell, верификация и тестирование]({{ sire.url }}/2024/07/11/nitta-verification.markdown)
- [Paper: 2021, Synthesis Method for CGRA Processors based on Imitation Model](https://www.researchgate.net/publication/350871215_Synthesis_Method_for_CGRA_Processors_based_on_Imitation_Model)
- [Report: 2021, Open Dais: Software Verification on the ASIP CAD Example or How to Trust Your Team and Yourself]({{ sire.url }}/2021/04/29/software-verification-on-CAD-example.html)
- [2021, NITTA: принципы работы](https://ryukzak.github.io/2021/02/03/nitta-internals.html);
- [2019, Семинар ЛКФС: NITTA Система проектирования спец. вычислителей](https://disk.yandex.ru/i/nllkSLEIzmf7GA).

Участие в проекте можно начать с простых задач, к примеру (после открытия исходного кода здесь будет ссылка на GitHub с реальными тикетами):

- Обновление зависимостей пользовательского интерфейса (Yarn, Typescript, React).
- Добавление ключа TARGET_PATH к интерфейсу командной строки (Haskell).
- Исправление небольших ошибок.

После погружения в проект можно подключиться к решению более сложных задач:

- Применение машинного обучения для синтеза специализированных вычислителей (Python, Haskell, ML).
- Поддержка более сложной организации аппаратуры с несколькими сетями внутри процессора (Verilog, Haskell).
- Автоматизация тестирования процесса синтеза при помощи свойств-ориентированного тестирования (Haskell, Verilog).
- Автоматизация тестирования веб интерфейсов (Typescript, React).
- Разработка пользовательских интефейсов для отладки и профилирования программного и аппаратногообеспечения  специализированных вычислителей (Typescript, React).
- Разработка системы управления для интеграции процессоров в информационные системы (Rust, Verilog, Haskell).
- Реализация поддержки арифметики с плавающей точки для специализированных вычислителей (Haskell, Verilog)

Для участия в проекте вам необходимо связаться со мной: <https://t.me/aleksandr_penskoi> или <aleksandr.penskoi@gmail.com>.

Дипломы связанные с проектом:

1. [Разработка и исследование архитектурных стилей проектирования уровневой организации Встроенных систем. Пенской А.В. 2016]({{ site.url }}/assets/pdf/thesises/2016-diss-penskoi-thesis.pdf), [autoref]({{ site.url }}/assets/pdf/thesises/2016-diss-penskoi-autoref.pdf)
1. Разработка системы управления аппаратным вычислителем, Оспенников Л.В., бак., 2018, [text]({{ site.url }}/assets/pdf/thesises/2018-ospennikov-bac-nitta-control.pdf), [slides]({{ site.url }}/assets/pdf/thesises/2018-ospennikov-bac-nitta-control-slides.pdf)
1. Механизмы ввода-вывода реконфигурируемой вычислительной платформы реального времени, Емельянов Д.В., маг., 2019, [text]({{ site.url }}/assets/pdf/thesises/2019-emelianov-master-nitta-spi.pdf)
1. Автоматизация построения моделей вычислительных блоков для системы проектирования специалиированных вычислителей, Ницер  К.А., бак., 2019, [text]({{ site.url }}/assets/pdf/thesises/2019-nitcer-bac-auto-pu-model-gen.pdf)
1. Разработка высокоскоростного интерфейса аппаратного ускорителя для системной динамики, Чижиков И.В., маг., 2020, [text]({{ site.url }}/assets/pdf/thesises/2020-chizikov-master-nitta-pci-express.pdf)
1. Оптимизация синтеза в САПР специализированных вычислителей с помощью машинного обучения, Бураков И.А., бак., 2021, [text]({{ site.url }}/assets/pdf/thesises/2021-burakov-bac-nitta-ml.pdf)
1. Верификация системы автоматического проектирования специализированных процессоров, Костючик А.Г., маг., 2021, [text]({{ site.url }}/assets/pdf/thesises/2021-kostychick-mag-nitta-test-dsl.pdf)
1. Разработка механизмов синтеза в системе автоматического проектирования специализированных вычислителей, Прохоров Д.А., бак., 2021, [text]({{ site.url }}/assets/pdf/thesises/2021-prohorov-bac-group-binding.pdf)
1. Инструментальные средства крупногранулярных реконфигурируемых вычислителей для системной динамики, Гогиян А.Г., маг., 2022, [text]({{ site.url }}/assets/pdf/thesises/2022-gogiyan-mag-xmile.pdf)
1. Механизмы автоматизированного синтеза микроархитектуры крупногранулярных реконфигурируемых вычислителей, Закусило В.А., маг., 2022, [text]({{ site.url }}/assets/pdf/thesises/2022-zakusilo-mag-microachitecure-generation.pdf)
1. Совершенствование метода синтеза на основе машинного обучения в САПР
специализированных вычислителей, Бураков И.А., маг., 2023, [text]({{ site.url }}/assets/pdf/thesises/2023-burakov-nitta-ml.pdf)
