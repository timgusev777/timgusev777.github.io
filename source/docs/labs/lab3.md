# Лабораторная работа №3

## Тема: Автоматическое развертывание статического сайта

## Цель работы
Реализовать сценарии автоматического развертывания статического сайта на движке MkDocs с использованием SourceCraft и GitHub Actions.

## Структура проекта
timgusev777.github.io/
├── .github/workflows/
│		└── ci.yml	
── .sourcecraft/
│   ├── ci.yaml
│   └── sites.yaml
├── source/
│   ├── mkdocs.yml
│   └── docs/
│       ├── ...
│       └── labs/
│           ├── ...
├── requirements.txt
├── README.md 
└── docs/

## Выполненные действия

1. **Настройка SourceCraft**:
Создана публичная организация
Создан репозиторий `site` на платформе SourceCraft
Добавлен remote `sourcecraft` для работы с SourceCraft
Сгенерирован токен с правами Maintainer на год

2. **Настройка GitHub**:
Создан workflow для сборки проекта
Настроена автоматическая сборка MkDocs и публикация на GitHub Pages
В Settings → Pages источник установлен "GitHub Actions"
Автоматически настраивается через workflow


## Ссылки на результаты

1. **SourceCraft сайт**: https://timgusev777.sourcecraft.site/site
2. **SourceCraft репозиторий**: https://sourcecraft.dev/timgusev777/site
3. **GitHub сайт**: https://timgusev777.github.io
4. **GitHub репозиторий**: https://github.com/timgusev777/timgusev777.github.io

## Вывод
Настроена автоматизация развёртывания статического сайта на MkDocs через две платформы: GitHub и SourceCraft
Получен практический опыт работы с Personal Access Tokens, настройки прав доступа и интеграции систем контроля версий с платформами хостинга
Достигнута полная автоматизация: при пуше в ветку main сайт автоматически собирается и публикуется на GitHub Pages и SourceCraft Sites