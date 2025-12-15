# Учетные данные для тестирования

## Основной тестовый пользователь (использован в тестировании)
**Email:** qa_test_nikita@mail.ru  
**Password:** TestPass123!  
**Статус:** Зарегистрирован 15.12.2025  
**Примечание:** Используется для основных тестов авторизации

## Альтернативные учетные данные (для дополнительного тестирования)
**Email:** test_user_1@example.com  
**Password:** Password123$  
**Назначение:** Тестирование уникальности email

**Email:** boundary_test@test.com  
**Password:** Test!@#123  
**Назначение:** Тестирование граничных значений

## Данные для негативного тестирования
### Несуществующие пользователи:
- Email: nonexistent@test.com / Password: AnyPass123
- Email: fake_user@domain.com / Password: FakePassword456

### Неправильные форматы:
- Email: invalid-format / Password: Test123
- Email: user@ / Password: Test123
- Email: @domain.com / Password: Test123
