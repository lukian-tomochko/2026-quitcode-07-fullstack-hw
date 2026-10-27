# Здача WS7

## Дані

- Роль: dev
- Команда: leave-portal
- GitHub-логін: lukian-tomochko
- Ваше репо: https://github.com/lukian-tomochko/leave-portal
- SHA: e469392ba8d7d0990f96f88e5b4184d9700c8b05
- Репо вимог PM: https://github.com/mkozlovskyi-ops/course-staff-management-spec
- Прод-URL: https://leave-portal-blush.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/mkozlovskyi-ops/course-staff-management-spec · джерело: docs · знімок 2026-10-24
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/lukian-tomochko/leave-portal/pull/15
- PR «Оновлення вимог» після уточнень PM (A): /requirements-sync 2026-10-27: Вимоги актуальні
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/mkozlovskyi-ops/course-staff-management-spec/issues/16, https://github.com/mkozlovskyi-ops/course-staff-management-spec/issues/17, https://github.com/mkozlovskyi-ops/course-staff-management-spec/issues/18
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/lukian-tomochko/leave-portal/pull/3 (`add-leave-management`; PM не публікував окремого зрізу 2 для WS7, тому за зріз 2 взято вимогу 02 «рішення менеджера», план — https://github.com/lukian-tomochko/leave-portal/pull/17)
- Дизайн-система — PR (B): https://github.com/lukian-tomochko/leave-portal/pull/14
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/lukian-tomochko/leave-portal/blob/e469392ba8d7d0990f96f88e5b4184d9700c8b05/DESIGN.md · джерело: AI-чат: Claude Code (Claude Sonnet 5.5)
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/lukian-tomochko/leave-portal/actions/runs/40457548975
- Знімки «до/після» (B): https://github.com/lukian-tomochko/leave-portal/blob/e469392ba8d7d0990f96f88e5b4184d9700c8b05/docs/img/ws7-before-home-light.png, https://github.com/lukian-tomochko/leave-portal/blob/e469392ba8d7d0990f96f88e5b4184d9700c8b05/docs/img/ws7-after-home-light.png
- Зміна `impl-<зріз2>` (C): https://github.com/lukian-tomochko/leave-portal/tree/e469392ba8d7d0990f96f88e5b4184d9700c8b05/openspec/changes/archive/2026-10-27-impl-leave-decision (після злиття https://github.com/lukian-tomochko/leave-portal/pull/25)
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/lukian-tomochko/leave-portal/pull/18, https://github.com/lukian-tomochko/leave-portal/pull/19, https://github.com/lukian-tomochko/leave-portal/pull/20
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/lukian-tomochko/leave-portal/actions/runs/40163893130 (AC-DECIDE-08), https://github.com/lukian-tomochko/leave-portal/actions/runs/40164087425 (AC-DECIDE-18)
- ADR (D): https://github.com/lukian-tomochko/leave-portal/blob/e469392ba8d7d0990f96f88e5b4184d9700c8b05/docs/decisions/0004-decision-functions.md
- Архітектурне правило, крім `check:design` (D): job «Секретний ключ лише на сервері» (`check:boundary`) у `architecture.yml`; доказ, що ловить порушення, — вивід «5 порушень» в описі https://github.com/lukian-tomochko/leave-portal/pull/16
- Акаунти для PM (E): pm-employee@example.test (employee), pm-manager@example.test (manager), pm-admin@example.test (admin). Паролі — PM у чаті
- Скріни за ролями (E): —
- AC зрізу 2 (E): як у `docs/conformance.md` на SHA, усі «реалізовано»: AC-DECIDE-01, AC-DECIDE-02, AC-DECIDE-03, AC-DECIDE-04, AC-DECIDE-05, AC-DECIDE-06, AC-DECIDE-07, AC-DECIDE-08, AC-DECIDE-09, AC-DECIDE-10, AC-DECIDE-11, AC-DECIDE-12, AC-DECIDE-13, AC-DECIDE-14, AC-DECIDE-15, AC-DECIDE-16, AC-DECIDE-17, AC-DECIDE-18, AC-DECIDE-19, AC-DECIDE-20, AC-DECIDE-21, AC-DECIDE-22, AC-DECIDE-23, AC-DECIDE-24, AC-BALANCE-01, AC-BALANCE-02, AC-BALANCE-03, AC-BALANCE-04, AC-BALANCE-05, AC-BALANCE-06, AC-BALANCE-07, AC-BALANCE-08, AC-BALANCE-09, AC-BALANCE-10, AC-BALANCE-11, AC-BALANCE-12, AC-BALANCE-13, AC-BALANCE-14, AC-BALANCE-15, AC-BALANCE-16, AC-BALANCE-17, AC-BALANCE-18, AC-BALANCE-19, AC-BALANCE-20, AC-BALANCE-21, AC-BALANCE-22 (46 AC зрізу 2 і вимоги 03; разом у матриці 67 AC, усі «реалізовано», `npm run ac:coverage` — OK)
- Відхилення від PM (E): не надходило станом на 2026-10-27 (issues «Відхилення від вимог» у репо немає)

## Бонус

—
