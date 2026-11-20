# Manhattan - Coffee House

A simple one-page website for a coffee shop, built with HTML and CSS for study purposes.

## 1. Goal

Present the coffee shop to visitors: who we are, where we are, and when we are open.

**Target users:** people looking for a good coffee in Barra da Tijuca, Rio de Janeiro.

## 2. Tech Stack

- HTML5 (semantic tags)
- CSS3 (custom properties, Flexbox, Grid)
- No JavaScript frameworks
- Google Maps embed (contact section)

## 3. Design Tokens

### Fonts (Google Fonts)

| Name     | Role                                      |
| -------- | ----------------------------------------- |
| Fraunces | Main title and quotes (elegant, serif)    |
| Oswald   | Section titles, menu, opening hours       |
| Lato     | Body text, paragraphs, footer             |

### Colors

| Value     | Suggested use                                        |
| --------- | ---------------------------------------------------- |
| `#c4a47c` | Section titles, highlights                           |
| `#fff`    | Text on dark backgrounds, page background            |
| `#000000` | Footer background, dark overlays                     |
| `#604829` | Header, quote boxes, contact boxes                   |
| `#666`    | Paragraph text                                       |
| `#ACACAC` | Secondary details (lines, borders, subtle text)      |

### Sizes

> To be defined. Suggested: use `rem` units and store them as CSS variables.

## 4. Page Structure

Order of the sections, from top to bottom:

1. **Header** – fixed bar with logo (left) and menu (right): *Informações*, *Contatos*, *Horários*.
2. **Hero** – full-width background image with the title "MANHATTAN - COFFEE HOUSE".
3. **Intro** – title "Experimente o melhor café da cidade!" and a centered paragraph.
4. **Banner 1** – background image with the quote "Um bom café é motivo de alegria!".
5. **About** – title "O que é o café Manhattan?" and a centered paragraph.
6. **Banner 2** – background image with the quote "A vida só começa depois do café!".
7. **Gourmet** – title "Conheça o café gourmet Manhattan?" and a centered paragraph.
8. **Contact** – title "Contatos & Endereço", Google Map, and a box with phone/WhatsApp, e-mail and address.
9. **Opening hours** – title "Horários de funcionamento" and a list of days with hours.
10. **Footer** – copyright text and credit "Desenvolvido por 'nome do aluno'".
11. **Back-to-top button** – fixed in the bottom-right corner.

## 5. Content Details

**Opening hours**

| Day     | Hours         |
| ------- | ------------- |
| Segunda | Fechado       |
| Terça   | 09:00 - 22:00 |
| Quarta  | 09:00 - 22:00 |
| Quinta  | 09:00 - 22:00 |
| Sexta   | 09:00 - 22:00 |
| Sábado  | 09:00 - 22:00 |
| Domingo | 12:00 - 22:00 |

**Contact**

- Phone & WhatsApp: (21) 99999-5555
- E-mail: contato@manhattan.com.br
- Address: Av. Ayrton Senna, 3000 - Barra da Tijuca - Rio de Janeiro

## 6. Style Notes

- The page text is in Portuguese (Brazil).
- Section titles are uppercase, in Oswald, color `#c4a47c`.
- Paragraphs are centered, in Lato, color `#666`, with a narrow width for easy reading.
- Banners use a background image with a dark overlay and a quote box in `#604829`.
- The opening hours section has a dark background with white text.

## 7. Suggested Folder Structure

```
manhattan-coffee-house/
├── index.html
├── README.md
├── css/
│   ├── variables.css
│   └── style.css
└── img/
    ├── logo.png
    ├── hero.jpg
    └── banner-1.jpg
```

## 8. Checklist

- [ ] Create `variables.css` with fonts, colors and sizes
- [ ] Build the HTML structure
- [ ] Style the header and hero
- [ ] Style the text sections and banners
- [ ] Add the map and contact box
- [ ] Style the opening hours and footer
- [ ] Make the layout responsive (mobile first)
- [ ] Test in different browsers
