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

You can start meeting with the project by reading [recent publications](https://ryukzak.github.io/publications/) and viewing presentations:
- [Paper: 2021, Synthesis Method for CGRA Processors based on Imitation Model](https://www.researchgate.net/publication/350871215_Synthesis_Method_for_CGRA_Processors_based_on_Imitation_Model)
- [Report: 2021, Open Dais: Software Verification on the ASIP CAD Example or How to Trust Your Team and Yourself](https://ryukzak.github.io/news/2021-04-29-software-verification-on-CAD-example/)
- [Report: 2021, NITTA: principles of work](https://ryukzak.github.io/news/2021-02-03-nitta-internals/) in Russian
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

Знакомство с проектом можно начать с чтения [последних статей](https://ryukzak.github.io/publications/) по проекту и просмотра выступлений:
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
