---
layout: page
title: NITTA
description: CAD for Hard Real-Time Application Specific Processor
img: /assets/img/nitta-logo-horizon.jpg
importance: 1
---

We develop the tool for generating and programming specialized non von Neumann processors for cyclic execution of control and signal/data processing algorithms. These processors are based on the original Not Instruction Transport Triggered Architecture (NITTA). That allows us to:

- Provide high speed and parallel execution of irregular algorithms (where GPU is not applicable) in hard real-time (clock accuracy).
- Make the processor reconfigurable for different application domains.
- Provide a high-level language for application developers and fast compilation.

Our users can resolve the following tasks:

- Development of embedded and cyber-physical systems.
- Hardware and software testing and rapid prototyping (HIL and PIL).
- Development of programmable accelerators and coprocessors.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_ReactJS_3451802.png' | relative_url }}" alt="React" title="React"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_tsx format_1333394.png' | relative_url }}" alt="TypeScript" title="TypeScript"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_lambda_827225.png' | relative_url }}" alt="Haskell" title="Haskell"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_FPGA_26403.png' | relative_url }}" alt="Verilog" title="Verilog"/>
    </div>
</div>
<div class="caption">
    React, TypeScript for User Interface; Haskell for Core; Verilog for FPGA
</div>

Currently, the project has focused on two goals:

- be published as open-source code (BSD license);
- develop the hardware accelerator for system dynamics and its integration into the cloud platform of our friends: [sdCloud project](https://sdcloud.io).

You can start meeting with the project by reading [recent publications](https://ryukzak.github.io/publications/) and by viewing presentations:
- [2021, NITTA: principles of work](https://ryukzak.github.io/news/2021-02-03-nitta-internals/) in Russian;
- [2019, LCPS Workshop: NITTA - Design Application Specific Processors](https://disk.yandex.ru/i/nllkSLEIzmf7GA) in Russian.

You can start to contribute by simple tasks, for example (after opening the source code, there will be a link to GitHub):

- Add integrity check of a scheduled computational process into tests.
- UI: add transport and instructions tables to ProcessView.
- HDL library structure in a target project.
- Add TARGET_PATH command-line argument.
- Constant folding.

After diving into the project, you can connect to solving more complex problems:
- Using machine learning to make decisions in the process of synthesizing the target system.
- Development of the XMILE language translator.
- Support for microarchitectures with multiple networks.
- Tools for verification of tools (Property-based testing, eDSL, CoSimulation).
- Development of visualization tools for a multi-level computing process.
- Development of control software for the integration of a specialized processor into other information systems.
- Optimization of the target processor synthesis process.
- Automation of building models of processor units.

To participate in the project, you need to contact me: <https://t.me/aleksandr_penskoi> or <aleksandr.penskoi@gmail.com>.


---


Мы создаем инструментарий для генерации и программирования специализированных не фон&nbsp;Неймановских процессоров, предназначенных для циклического исполнения алгоритмов управления и обработки сигналов/данных. Они строятся на оригинальной архитектуре NITTA (Not Instruction Transport Triggered Architecture). Это позволяет:

- обеспечить высокую скорость и уровень параллелизма для нерегулярных алгоритмов (где не используют GPU) и жесткое реальное время (с точностью до такта);
- сделать процессор реконфигурируемым под разные прикладные области;
- предоставить язык высокого уровня для прикладных разработчиков и быструю компиляцию.

Построенные при помощи нашего инструмента вычислители могут использоваться для:

- разработки встроенных и киберфизических систем;
- программно-аппаратного тестирования и быстрого прототипирования (HIL и PIL);
- разработки программируемых ускорителей и сопроцессоров.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_ReactJS_3451802.png' | relative_url }}" alt="React" title="React"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_tsx format_1333394.png' | relative_url }}" alt="TypeScript" title="TypeScript"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_lambda_827225.png' | relative_url }}" alt="Haskell" title="Haskell"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/noun_FPGA_26403.png' | relative_url }}" alt="Verilog" title="Verilog"/>
    </div>
</div>
<div class="caption">
    React, TypeScript для пользовательского интерфейса; Haskell для ядра САПР; Verilog для ПЛИС
</div>

В настоящий момент перед проектом стоит две ключевые цели:

- открытие исходного кода (BSD лицензия);
- разработка аппаратного ускорителя для системной динамики и его интеграция в облачную платформу наших друзей из [sdCloud project](https://sdcloud.io).

Знакомство с проектом можно начать с чтения [последних статей](https://ryukzak.github.io/publications/) по проекту и просмотра выступлений:
- [2021, NITTA: принципы работы](https://ryukzak.github.io/news/2021-02-03-nitta-internals/);
- [2019, Семинар ЛКФС: NITTA Система проектирования спец. вычислителей](https://disk.yandex.ru/i/nllkSLEIzmf7GA).

Участие в проекте можно начать с простых задач, к примеру (после открытия исходного кода здесь будет ссылка на GitHub с реальными тикетами):

- Add integrity check of a scheduled computational process into tests (Добавить проверку целостности спланированного вычислительного процесса в тесты).
- UI: add transport and instructions tables to ProcessView (Добавить на форму ProcessView пользовательского интерфейса таблицу спланированных инструкций и пересылок данных).
- HDL library structure in a target project (Сохранять структуру папок библиотеки при генерации целевой системы).
- Add TARGET_PATH command line argument (Добавить аргумент командной строки для указания папки с результатом).
- Constant floding (Свертка констант).

После погружения в проект можно подключиться к решению более сложных задач:
- Применение машинного обучения для принятия решений в процессе синтеза целевого вычислителя.
- Разработка транслятора языка XMILE.
- Поддержка микроархитектур со множественными сетями.
- Средства верификации инструментальных средств (Property-based testing, eDSL, совместная симуляция).
- Разработка средств визуализации многоуровневого вычислительного процесса.
- Разработка управляющего ПО для интеграции специализированного процессора в другие информационные системы.
- Оптимизация процесса синтеза целевого вычислителя.
- Автоматизация построения моделей вычислительных блоков.

Для участия в проекте вам необходимо связаться со мной: <https://t.me/aleksandr_penskoi> или <aleksandr.penskoi@gmail.com>. 
