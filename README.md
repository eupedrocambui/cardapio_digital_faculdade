# Digital Menu for University Restaurant - UNIOESTE

Digital menu developed for students and staff who attend the university restaurants at Unioeste in Foz do Iguaçu.

**Access the Project:** https://cardapio-digital-unioeste.vercel.app

## Objective
The goal was to **create a digital menu** for Unioeste's university restaurants, including the Jardim Universitário (JU) campus
and CECE (Centro de Engenharias e Ciências Exatas), aiming to offer a more **practical way to view the meals made available to the community.**

## Identified Problem
Before the project was implemented, **access to information was limited**: at CECE, students would only find out the meal of the day by going
to the university restaurant or through informal exchange of information among students, while at the Jardim Universitário campus, the menu was published exclusively through Instagram, making it difficult for those who did not use
the social network or did not have access for another reason.

## Academic Context
The project was developed for the **"Introduction to Computer Science"** course, being built over the first and second semesters of the degree.

The course was taught by professors **Antonio Marcos Massao Hachisuca** and **Juan Carlos Sotuyo**, who actively contributed with guidance, suggestions, and ideas that helped improve the project, both in technical and conceptual aspects.

## Technologies Used
- HTML
- CSS
- JavaScript

Throughout the development of the project, several fundamental web development concepts were applied, such as:

- Responsiveness and adaptation to different screen sizes
- Dynamic creation and modification of page elements
- Application of the MVC (Model–View–Controller) architectural pattern in parts of the project
- Event handling (clicks, page load, etc.)
- Use of requests for dynamic content loading
- Application flow control with JavaScript
- User interactivity
- Initial web development best practices

## Main Features
- **Menu Display:**

Display of the restaurants' daily menu, allowing users to quickly and easily view the available meals.

- **Rating System:**

Implementation of a complete rating system, in which users can rate the meal of the day and check the rating history of previous meals.

- **Contact and Feedback Page:**

A dedicated page for sending feedback, suggestions, or comments, enabling direct communication between users and those responsible for the system.

## How to Run the Project Locally
1- Clone the Project:
```bash
git clone https://github.com/pedrocambui06/cardapio-digital-unioeste.git
```

2- Access the Directory:
```bash
cd cardapio-digital-unioeste
```

3- Open the ```index.html``` file in a web browser (preferably Google Chrome).

Note: no additional dependencies need to be installed, since the project uses only HTML, CSS, and JavaScript.

## Project Structure
```
cardapio-digital-unioeste/
├── images/                                  # Images used on the site
│   ├── 1_stars.png                          # 1-star rating
│   ├── 2_stars.png                          # 2-star rating
│   ├── 3_stars.png                          # 3-star rating
│   ├── 4_stars.png                          # 4-star rating
│   ├── 5_stars.png                          # 5-star rating
│   ├── chef.png                             # Illustrative chef image
│   ├── favicon_unioeste.png                 # Site favicon
│   ├── foto_usuario.png                     # User image
│   ├── icone_comida_hero.png                # Food icon (hero section)
│   ├── icone_garcom_hero.png                # Waiter icon (hero section)
│   ├── icone_prato_hero.png                 # Dish icon (hero section)
│   ├── logo_unioeste_branca_footer.png      # UNIOESTE logo (footer)
│   ├── logo_unioeste_branca.png             # UNIOESTE logo (white version)
│   ├── logo_unioeste.png                    # UNIOESTE default logo
│   └── prato_hero.png                       # Main image (hero section)
├── scripts/                                 # JavaScript files
│   ├── avaliacoes.js                        # Rating system logic
│   ├── cardapioDigital.js                   # Menu control and display (home page)
│   ├── contato.js                           # Contact page functionality
│   ├── footer.js                            # Footer behavior and display
│   ├── header.js                            # Header behavior and display
│   └── refeicaoAvaliada.js                  # Rated meal page logic
├── styles/                                  # CSS styling files
│   ├── avaliacoes.css                       # Rating page styles
│   ├── cardapioDigital.css                  # Home page styles
│   ├── contato.css                          # Contact page styles
│   ├── footer.css                           # Footer styles
│   ├── header.css                           # Header styles
│   ├── obrigado.css                         # Thank-you page styles (contact)
│   ├── obrigadoAvaliacao.css                # Thank-you page styles (ratings)
│   └── refeicaoAvaliada.css                 # Rated meal page styles
├── README.md                                # This file
├── avaliacoes.html                          # Ratings page
├── contato.html                             # Contact page
├── footer.html                              # Footer structure
├── header.html                              # Header structure
├── index.html                               # Main page (home page)
├── obrigado.html                            # Thank-you page (contact)
├── obrigadoAvaliacao.html                   # Thank-you page (ratings)
└── refeicaoAvaliada.html                    # Rated meal page

```

---

Made by [Pedro C. Martins](https://github.com/pedrocambui06)
