# Driver documents list — Admin Panel checklist

## Scope
- Product: Trade Taxi
- Area: Admin Panel
- Platform: Web
- Page: Driver card → `Документы`
- Scope: only driver documents list, groups, statuses, disabled states, list stability

## Checklist
- Verify the `Документы` tab opens without errors.
- Verify groups `Основные`, `Иностранные`, `Дополнительные` are shown.
- Verify statuses `Не загружено` and `Обновлено` are used.
- Verify disabled items remain visible.
- Verify disabled items are not removed from the list.
- Verify previously uploaded disabled documents remain visible.
- Verify `Паспорт РФ` disables group `Иностранные`.
- Verify `ВНЖ/РВП` disables `Патент`, `Чек об оплате патента`, `Амина`, `КИГ` for an иностранный driver.
- Verify list remains stable after refresh and re-login.
- Verify list is recalculated after driver data changes.
