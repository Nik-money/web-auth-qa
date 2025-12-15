# Наборы тестовых данных

## Набор 1: Валидные данные для регистрации (позитивное тестирование)
### Пользователь A (стандартные данные)
- **Title:** Mr
- **First name:** John
- **Surname:** Smith
- **Phone:** +441234567890
- **Date of Birth:** 1985-06-15
- **Licence Type:** Full
- **Licence Period:** 3 years
- **Occupation:** Academic
- **Address Street:** 123 Main Street
- **City:** London
- **County:** Greater London
- **Post code:** SW1A 1AA
- **Email:** john.smith@example.com
- **Password:** SecurePass123!
- **Confirm password:** SecurePass123!

### Пользователь B (минимальные данные)
- **Title:** Ms
- **First name:** Ann
- **Surname:** Brown
- **Phone:** +440987654321
- **Date of Birth:** 1990-01-01
- **Licence Type:** Provisional
- **Licence Period:** 1 years
- **Occupation:** [выбрать первое в списке]
- **Address Street:** Test St
- **City:** Test City
- **County:** Test County
- **Post code:** TE1 1ST
- **Email:** minimal@test.com
- **Password:** Min1!
- **Confirm password:** Min1!

## Набор 2: Невалидные данные (негативное тестирование)
### Невалидные Emails:
- `without-at.com`
- `user@domain`
- `user@.com`
- `@domain.com`
- `user name@domain.com`
- `user@domain..com`
- `user@-domain.com`
- `user@domain.c`
- `user@domain.123`

### Невалидные пароли:
- `short` (менее 6 символов)
- `nouppercase123!` (без заглавных букв)
- `NOLOWERCASE123!` (без строчных букв)
- `NoNumbers!` (без цифр)
- `NoSpecial123` (без спецсимволов)
- `          ` (только пробелы)
- пустая строка

### Невалидные телефоны:
- `abc123`
- `12-34-56`
- `+`
- `123`
- `12345678901234567890` (слишком длинный)
