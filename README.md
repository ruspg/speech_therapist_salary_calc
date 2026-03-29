# Калькулятор зарплаты учителя-логопеда

Веб-калькулятор для расчёта ежемесячной заработной платы учителя-логопеда (дефектолога) в московской школе. Один HTML-файл, без зависимостей — работает в любом браузере, включая мобильные.

## Возможности

- Расчёт оклада логопеда по доле ставки
- Расчёт учебной нагрузки по формуле «ученико-час» (формула 3.9) с поддержкой нескольких предметов
- Сравнение оклада по договору и по формуле
- Учёт разовых замен (по приказу или по ученико-часу)
- Компенсационные выплаты за работу с ОВЗ
- Стимулирующие выплаты и премии
- НДФЛ и прочие удержания
- Итоги: грязная/чистая зарплата, доля замен, цена часа замены «на руки»

## Запуск

Откройте `index.html` в браузере. Установка не требуется.

Или используйте GitHub Pages: включите Pages в настройках репозитория (ветка `main`, корень `/`).

## Как пользоваться

1. Заполните общие параметры (стоимость ученико-часа, учебные недели)
2. Укажите оклад логопеда и долю ставки
3. Добавьте строки учебной нагрузки (предмет, часы, коэффициенты)
4. При необходимости включите разовые замены
5. Настройте компенсации и стимулирующие
6. Результат пересчитывается автоматически

## Структура

```
index.html              — калькулятор (единый файл)
docs/requirements.md    — бизнес-требования и формулы
docs/implementation-plan.md — план доработок
```

## Лицензия

MIT

---

# Speech Therapist Salary Calculator

A web calculator for estimating the monthly salary of a speech therapist (defectologist) working at a Moscow public school. Single HTML file, no dependencies — runs in any browser, including mobile.

## Features

- Base salary calculation by position share
- Teaching load calculation using the "student-hour" formula (formula 3.9) with multiple subjects
- Contract vs. formula salary comparison
- Substitute teaching pay (by school order or student-hour rate)
- Compensation payments for working with students with disabilities
- Incentive payments and bonuses
- Income tax (NDFL) and other deductions
- Summary: gross/net salary, substitution share, net hourly substitution rate

## Usage

Open `index.html` in a browser. No installation required.

Or enable GitHub Pages in the repository settings (branch `main`, root `/`).

## How to use

1. Set general parameters (student-hour rate, teaching weeks)
2. Enter the speech therapist base salary and position share
3. Add teaching load rows (subject, hours per week, coefficients)
4. Optionally enable substitute teaching
5. Configure compensations and incentives
6. Results update automatically

## Project structure

```
index.html              — calculator (single file)
docs/requirements.md    — business requirements and formulas
docs/implementation-plan.md — implementation plan
```

## License

MIT
