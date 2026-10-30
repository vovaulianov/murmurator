# Мурмуратор

Завантаж фото — нейромережа обтравить об’єкт, і зграя з тисяч птахів-стрілок збереться в його силует.
Налаштування щільності, деталізації, розміру птахів, потоків і тла; експорт у SVG (вставляється у Figma векторами) та PNG.

Відкрити: https://vovaulianov.github.io/murmurator/ · галерея: https://vovaulianov.github.io/murmurator/#galereya

Фото обробляються локально в браузері й нікуди не надсилаються.

## Сторонні компоненти
- U²-Net (u2netp), Xuebin Qin et al. — Apache License 2.0; ONNX-версія: huggingface.co/BritishWerewolf/U-2-Netp
- onnxruntime-web 1.17.3, Microsoft — MIT License (завантажується з cdn.jsdelivr.net; WASM-модуль лежить у `model/`)
