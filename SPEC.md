# Gagarina 106 — Static Website Rebuild

## Overview
Rebuild gagarina106.ru as a static HTML/CSS/JS site, styled like ankar-group.ru but with black + orange (#FF6600) color scheme.

## Brand Info
- **Name:** Автотехцентр "ГАГАРИНА 106"
- **Location:** Калининград, ул. Ю. Гагарина, 106
- **Phone:** +7 (4012) 76 93 08
- **Email:** gagarina106@bk.ru
- **Hours:** Пн-Пт 9:00-18:00, Суббота 9:00-14:00, Воскресенье — выходной
- **Social:** VK: vk.com/gagarina_106, YouTube: UC123OrWH0w3ZylfB8EACUyg, Dzen: gagarina106_kld
- **Yandex Metrika ID:** 46619493

## Design Reference: ankar-group.ru
Structure to replicate (adapted for Gagarina 106):

1. **Header** — sticky, logo left, phone + burger menu right
2. **Hero Section** — large headline with CTA button "Записаться", subtitle about the center
3. **Services Grid** — cards with icons/images linking to service pages
4. **Advantages Section** — 4 blocks with icons (гарантия, качество, опыт, удобство)
5. **About / Director quote** — optional, can add later
6. **Video Section** — embedded YouTube videos from their channel
7. **Contact Section** — address, phone, email, Yandex Maps embed, working hours
8. **Footer** — nav links, legal info, social links

## Color Scheme
- Primary: **#FF6600** (orange)
- Secondary: **#1A1A1A** (near-black)
- Background: **#FFFFFF** (white)
- Text: **#333333**
- Accent light: **#FFF3E6** (light orange tint for backgrounds)

## Pages & URL Structure (preserve for SEO!)

### / (index.html)
Main landing page with all sections above.

### /legkovoy (legkovoy.html or legkovoy/index.html)
**Title:** Легковой автосервис | ГАГАРИНА 106
**H1:** Ремонт легковых автомобилей
**Content sections:**
- Service list (ремонт подвески, электрооборудования, кондиционеров, токарные работы, тормозные суппорты, сцепление, диагностика подвески, геометрия колес, компьютерная диагностика, сварочные работы, ремни ГРМ, системы охлаждения, рулевое управление, системы отопления, тормозная система, электропроводка, двигатели, рулевые рейки, замена масла/фильтров, тормозные колодки/диски, форсунки, развал-схождение, детали подвески, КПП, рулевые редукторы)
- Ремонт подвески (detailed section with text about suspension safety)
- Возможные проблемы подвески (list)
- Замена агрегатов (detailed text)
- Замена сцепления
- Ремонт двигателя (detailed section)
- Диагностика двигателя
- Ремонт электрики (detailed section with 5 stages)
- Ремонт рулевых реек и редукторов

### /remkomtrans (remkomtrans/index.html)
**Title:** Ремонт Коммерческого Транспорта | ГАГАРИНА 106
**H1:** РемКомТранс
**Content:** Description of commercial transport repair division, stats about workshop area, max load capacity, number of lifts.

### /kuzovnoy (kuzovnoy/index.html)
**Title:** Кузовной ремонт | ГАГАРИНА 106
**H1:** Кузовной ремонт автомобилей
**Content sections:**
- Key stats (5 покрасочных камер, 3 стапеля, 100% подбор цвета)
- Эстетическая забота (before/after concept)
- Виды работ: покраска, рихтовка на стапеле, покраска в камере
- Порядок приема на ремонт (4 steps)
- Дополнительные услуги (химчистка, выкатка вмятин, ремонт царапин, замена автостекол, антигравий)
- Цены (покраска элемента от 5000₽, полировка кузова, локальная покраска от 2500₽, выкатка вмятин от 2000₽, полировка фар от 700₽, сварка пластика от 1500₽)

### /kardani (kardani/index.html)
**Title:** Изготовление и ремонт карданных валов | ГАГАРИНА 106
**H1:** Ремонт карданных валов
**Phone for this service:** +7 (4012) 76 27 72
**Content sections:**
- Services (замена крестовин, динамическая балансировка, удлинение/укорачивание валов, замена подшипников, замена вварных вилок/шлицевых соединений/карданных труб)
- For whom (легковые, микроавтобусы, грузовые, автобусы, спецтехника, ж/д транспорт, суда, оборудование)

### /antikor (antikor/index.html)
**Title:** Антикоррозийная обработка | ГАГАРИНА 106 | Калининград
**H1:** Антикоррозийная обработка
**Phone for this service:** +7 911 477 51 06
**Telegram:** t.me/antikor106
**Content sections:**
- Why choose us (years of work, 12 lifts, multi-stage treatment, 12-month warranty, sandblasting)
- All services of anticorrosion workshop
- Изготовление и ремонт порогов и арок (от 2700 руб)
- Сварочные работы и кузовной ремонт (от 3000 руб)
- Пескоструйные работы (от 5000 руб)
- Антикоррозийная обработка кузова (detailed: factors causing corrosion, LOTOS BODY material description)

### /avtomoika (avtomoika/index.html)
**Title:** Автомоечный комплекс | ГАГАРИНА 106
**H1:** Автомойка
**Content sections:**
- Service list (бесконтактная мойка, химчистка и полировка, мойка днища на подъемнике, мойка самообслуживания, аквабластинг, автомагазин, кафе и зона ожидания)
- Преимущества (4 моечных бокса, химчистка и полировка, 2 бокса мойки самообслуживания, 2 бокса мойки на подъемнике)
- Detailed services: мойка автомобиля, химчистка, мойка днища и подвески, аквабластинг, мойка самообслуживания, полировка

### /vse-uslugi (vse-uslugi/index.html)
**Title:** Все услуги автотехцентра | ГАГАРИНА 106
Overview page linking to all service pages.

### /special (redirect or page for сварочные работы → can redirect to /legkovoy or /antikor)
### /texosmotr (texosmotr/index.html) — simple page about technical inspection

## Video Content (YouTube embeds)
Include a video section on the main page with YouTube embeds from their channel.
Channel: https://www.youtube.com/channel/UC123OrWH0w3ZylfB8EACUyg
Key videos to embed (from the current site's video section about anticorrosion work).

## SEO Requirements
1. All page URLs must match current Wix URLs exactly (use folder/index.html pattern)
2. Proper meta titles and descriptions on every page
3. H1-H6 hierarchy maintained
4. Schema.org LocalBusiness markup on index
5. Canonical URLs
6. Sitemap.xml
7. robots.txt
8. Open Graph tags
9. Yandex Metrika counter (ID: 46619493)

## Technical Requirements
- Pure HTML5, CSS3, vanilla JS (no frameworks)
- Mobile-first responsive design
- Lazy loading for images
- Smooth scroll for anchor links
- Burger menu for mobile
- CSS variables for theming
- Minified production-ready
- All fonts from Google Fonts (use Inter or similar clean sans-serif)
- SVG icons (inline or sprite) for service icons
- Yandex Maps embed for contact section

## File Structure
```
gagarina106/
├── index.html
├── legkovoy/index.html
├── remkomtrans/index.html
├── kuzovnoy/index.html
├── kardani/index.html
├── antikor/index.html
├── avtomoika/index.html
├── vse-uslugi/index.html
├── texosmotr/index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── img/
│   └── (placeholder SVGs/icons)
├── sitemap.xml
├── robots.txt
└── SPEC.md
```

## Important Notes
- Use placeholder images (colored divs or SVG placeholders) since we don't have the actual photos yet
- The design should closely follow ankar-group.ru layout/structure
- Colors: orange (#FF6600) replaces ankar's red, black (#1A1A1A) stays
- Footer: "© 2017-2026 «ГАГАРИНА 106» | Калининград"
- Include Yandex Maps iframe for the address
- Include structured data (JSON-LD) for local business
