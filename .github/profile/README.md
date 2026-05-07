<div align="center">

```
██╗    ██╗██╗  ██╗██╗   ██╗    ███╗   ██╗ ██████╗ ████████╗
██║    ██║██║  ██║╚██╗ ██╔╝    ████╗  ██║██╔═══██╗╚══██╔══╝
██║ █╗ ██║███████║ ╚████╔╝     ██╔██╗ ██║██║   ██║   ██║   
██║███╗██║██╔══██║  ╚██╔╝      ██║╚██╗██║██║   ██║   ██║   
╚███╔███╔╝██║  ██║   ██║       ██║ ╚████║╚██████╔╝   ██║   
 ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝       ╚═╝  ╚═══╝ ╚═════╝    ╚═╝   
```

**Берём чужой код. Чиним. Улучшаем. Потому что — почему бы и нет.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/orgs/WhyNotLab/repositories?language=python)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://github.com/orgs/WhyNotLab/repositories?language=kotlin)
[![Forks](https://img.shields.io/badge/подход-fork_%26_improve-22c55e?style=flat-square)](#)
[![License](https://img.shields.io/badge/всё-open--source-f59e0b?style=flat-square)](#)

</div>

---

## Чем занимаемся

Два направления, одна философия — берём то, что работает, и делаем лучше.

### 🛡️ Сеть и цензура

> *Знать, что именно сломано — важнее, чем знать, что что-то не работает.*

**[rkn-block-checker](https://github.com/WhyNotLab/rkn-block-checker)** — диагностика блокировок РКН/ТСПУ по слоям:

```
DNS → TCP → TLS → HTTP
 ↓      ↓     ↓     ↓
подмена  RST  DPI  заглушка
```

Не просто «сайт не открывается», а точный ответ **где** оборвалась цепочка и **кто** виноват — провайдер, DPI или сам сервер. С DoH-сравнением, русскими пояснениями и поддержкой wire-format резолвинга.

---

### 📖 Манга без ограничений

> *Читать можно везде. Синхронизировать — тоже.*

Форки экосистемы [KotatsuApp](https://github.com/KotatsuApp) — Android-ридера с открытым кодом:

| Репозиторий | Что это |
|---|---|
| **[Kotatsu](https://github.com/WhyNotLab/Kotatsu)** | Сам ридер — офлайн-хранилище, метки, история |
| **[kotatsu-syncserver](https://github.com/WhyNotLab/kotatsu-syncserver)** | Self-hosted сервер синхронизации прогресса |
| **[kotatsu-parsers](https://github.com/WhyNotLab/kotatsu-parsers)** | Парсеры источников манги (Kotlin/JVM + Android) |

---

## Философия

```python
while True:
    problem = find_something_that_annoys_you()
    solution = fork_and_fix(problem)
    if solution.is_better:
        ship_it()         # потому что — почему бы и нет
```

Никаких грандиозных планов. Просто берём инструменты, которые почти работают как надо, и доводим до ума.

---

<div align="center">

**[→ Все репозитории](https://github.com/orgs/WhyNotLab/repositories)**

</div>
