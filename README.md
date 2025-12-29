# Event Marketplace

Event Marketplace to platforma umożliwiająca organizację, zarządzanie oraz udział w wydarzeniach. Projekt symuluje realny system marketplace, w którym organizatorzy publikują wydarzenia. Administratorzy moderują treści, a uczestnicy zapisują się na eventy i otrzymują powiadomienia. 
- `Celem projektu jest zaprezentowanie pełnego procesu projektowania aplikacji fullstackowej - od logiki biznesowej i bezpieczeństwa, po architekturę, CI/CD i integrację frontend-backend`.

System składa się z backendu opartego o `.NET Web API` oraz frontendu zbudowanego w `Next.js`.
Projekt w aktywnym rozwoju. Podstawowe funkcjonalności (Panel organizatora) są zaimplementowane, kolejne moduły są dodawane iteracyjnie. Trwają prace nad panelem administratora.

---

## Repositories

- 🔧 Backend: https://github.com/Event-Marketplace/EventMarketplace-BE
- 🌐 Frontend: https://github.com/Event-Marketplace/EventMarketplace-FE

---

## Architecture

- Frontend (Next.js)
- Backend (.NET Web API)
- PostgreSQL
- Autoryzacja JWT + Refresh Token
- Docker + CI/CD

---

## Features

- Rejestracja i logowanie użytkowników
- Autoryzacja oparta o JWT (Access Token + Refresh Token)
- Automatyczne odświeżanie access tokena
- Zarządzanie wydarzeniami po stronie Organizatora (CRUD)
- Lista wydarzeń Organizatora
- Publiczna strona główna z listą aktywnych wydarzeń
- Rozdzielenie aplikacji na panele:
  - Organizer
  - Administrator
  - Participant
- Obsługa wielu ról – możliwość wyboru kontekstu użytkownika
