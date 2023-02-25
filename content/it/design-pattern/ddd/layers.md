---
title: Слоистая архитектура
---
![Схема слоистой архитектуры](it/design-pattern/ddd/layers.png)
Идея в том, чтобы писать код так, чтобы он отражал особенности предметной области. Для этого, весь код разделяют на модули.

При этом, зависимости между этими модулями должны быть расположены строго слева направо (Domain не может зависеть от Application или User Interface)

## Слои
- [[it/design-pattern/ddd/layers/user-interface|User Interface]]
- [[it/design-pattern/ddd/layers/application|Application]]
- [[it/design-pattern/ddd/layers/domain|Domain]]
- [[it/design-pattern/ddd/layers/infrastructure|Infrastructure]]

