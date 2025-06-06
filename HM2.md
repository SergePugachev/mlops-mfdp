# Сервис предсказания зарплаты по вакансии

---

## 1. Какую задачу решает ваш продукт?

Продукт решает задачу автоматического предсказания ожидаемой зарплаты по описанию вакансии, её названию, локации и другим признакам. Это помогает:

- Уточнить рыночную стоимость вакансии;
- Упростить и ускорить формирование вилки зарплаты;
- Согласовать ожидания между работодателем и кандидатом.

---

## 2. Кто является целевым пользователем?

**ЦА №1: HR-специалисты и рекрутеры**  
— создают вакансии и хотят быстрее формировать корректные зарплатные ожидания.

**ЦА №2: Руководители направлений / HR-аналитики**  
— используют агрегированные данные для формирования политики компенсаций.

**ЦА №3: Платформы по размещению вакансий**  
— могут интегрировать модель в интерфейс создания вакансии как рекомендательную систему.

---

## 3. Какую ценность продукт приносит ЦА?

- Сокращение времени на подбор вилки зарплаты
- Снижение количества «неадекватных» вакансий → меньше отказов со стороны кандидатов
- Повышение прозрачности и обоснованности компенсаций

**Как измерим:**
- Среднее время создания вакансии до/после внедрения
- Уровень отказов/пересмотров по зарплатным ожиданиям
- Доля вакансий, попавших в рыночную вилку (по исследованию)

---

## 4. Чем ваш продукт лучше альтернативных решений?

| Критерий              | Наш продукт             | Ручная аналитика | Средние вилки на сайтах |
|-----------------------|-------------------------|------------------|--------------------------|
| Индивидуальный прогноз| ✅ Да                   | ❌ Нет           | ❌ Нет                   |
| Актуальность          | ✅ Модель регулярно обновляется | ❌ Зависит от человека | ⚠️ Задержка в обновлении |
| Масштабируемость      | ✅ API / Batch-интерфейс | ❌ Низкая        | ✅ Частично               |
| Стоимость             | ⚖️ Умеренная            | ❌ Дорого (часы HR) | ✅ Бесплатно, но ограничено |

---

## 5. Как пользователь взаимодействует с продуктом?

- Вводит данные о вакансии в веб-интерфейсе или через API:
  - Название, описание, город, опыт, тип занятости и пр.
- Получает предсказание вилки (или конкретной зарплаты) и обоснование результата.
- При необходимости — настраивает параметры или экспортирует данные.

---

## 6. Как пользователь узнает о продукте?

- Интеграция в платформу размещения вакансий
- Через HR-сообщества (телеграм-каналы, метапы)
- Демонстрации и пилоты с компаниями (в формате HR-Tech продукта)
- LinkedIn и профессиональные статьи об аналитике компенсаций

---

## 7. Какая бизнес-модель будет у продукта?

**SaaS-модель:**
- Бесплатный тариф с ограничениями (кол-во запросов, базовая модель, ограничения на кол-во признаков)
- Платный тариф без ограничений
- Платный доступ для компаний/рекрутинговых агентств
  - API-доступ — по подписке
  - White-label решения для job-платформ

---

## 8. Продуктовое позиционирование

> **Мы, команда SalaryVision,**  
> помогаем **HR-специалистам, соискателям, аналитикам и онлайн-сервисам**  
> в ситуации **неопределённости и высокой конкуренции за кандидатов**  
> решать проблему **поиска и обоснования справедливой зарплаты**  
> с помощью **модели машинного обучения, обученной на актуальных вакансиях**  
> и получать **быстрые, персонализированные прогнозы, сокращающие время и ошибки в подборе.**

---
