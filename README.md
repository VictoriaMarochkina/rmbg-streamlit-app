# Streamlit-приложение: Удаление фона с изображений

Веб-приложение на **Streamlit**, которое использует модель [BRIA RMBG-1.4](https://huggingface.co/briaai/RMBG-1.4) для автоматического удаления фона с фотографий.

## Возможности
- Загрузка изображения (JPG, JPEG, PNG)
- Автоматическое удаление фона с помощью модели **RMBG-1.4**
- Отображение маски сегментации и результата
- Возможность скачать готовое изображение без фона

## Используемые технологии
- [Streamlit](https://streamlit.io/)
- [Transformers](https://huggingface.co/docs/transformers)
- [PyTorch](https://pytorch.org/)
- [scikit-image](https://scikit-image.org/)
- [Pillow](https://python-pillow.org/)

## Запуск локально
```bash
    pip install -r requirements.txt
    streamlit run app.py
```