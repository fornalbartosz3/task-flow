Stwórz plik README.md dla projektu TaskFlow.
Projekt to aplikacja do zarządzania zadaniami (todo) zbudowana w Next.js,
TypeScript, Tailwind CSS, shadcn/ui. Używa localStorage do persystencji danych.
Architektura Hexagonal (Ports & Adapters).

README ma zawierać:
- Opis projektu
- Screenshot placeholder (![screenshot](./public/screenshot.png))
- Stack: Next.js, TypeScript, Tailwind CSS, shadcn/ui
- Jak uruchomić lokalnie (npm install, npm run dev)
- Diagram architektury w Mermaid.js:
  TaskService → TaskRepository (Port) → LocalStorageAdapter
                                      → FakeAdapter (testy)
- Sekcję "Testy" z info o TDD/BDD podejściu
- Sekcję "Czego się nauczyłem"

Zapisz plik jako README.md
