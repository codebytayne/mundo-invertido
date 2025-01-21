# 🎯 Mundo Invertido

![JavaScript](https://img.shields.io/badge/JavaScript-FFFF00?style=flat&logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)


> Mais um projeto do Bootcamp front-end do zero da [DIO.me](https://web.dio.me/) em colaboração com a Ri Happy

-------
Uma jornada para quem não tem medo do desconhecido. O caminho para o Mundo Invertido é incerto, repleto de obstáculos e perigos. Porém, a recompensa é grande: salvar Hawkings e o mundo todo das garras de Vecna. Você está preparado(a)?

## 👩‍💻 O projeto

🔗 [Veja o Mundo Invertido](https://codebytayne.github.io/mundo-invertido/)

O projeto consiste em recriar o estilo css do mundo invertido a partir de um prototipo do [Figma](https://www.figma.com/design/I3Q42CcVUziRN3iMfTrbfb/Stranger-Things), fornecido pelos experts [Diogo Medeiros Mainardes](https://www.linkedin.com/in/diogomainardes/), [Michele Queiroz Ambrosio](https://www.linkedin.com/in/michele-ambrosio-a4899661/) e [Renan Johannsen de Paula](https://www.linkedin.com/in/renanjpaula/) da [DIO.me](https://web.dio.me/)

![Texto alternativo](src/images/demo/demo.gif)

## 💬 Assuntos abordados
- HTML
    - Estruturação da página 
    - Semântica
    - Acessibilidade
    - Web Scraping
    - SEO
- CSS
    - Posicionamentos
    - Pseudo-elementos
    - Pseudo-classes
    - Flexbox
    - Animações 
- JavaScript
    - Introdução ao JavaScript
    - Manipulação do DOM
    - Introdução ao Firebase
    - Integração com o Firebase

## 🎨 Variáveis do Tema CSS
```css
/*** VARIABLES & THEMES ***/

:root {
  --primary-color: #cf0f0f;
  --primary-color-contrast: #ffffff;
  --field-background-color: #000;
}

.light-theme {
  --page-background: linear-gradient(
    180deg,
    #ffffff 0%,
    #ffffff 65%,
    rgba(255, 255, 255, 0.75) 100%
  );
  --header-background-color: #e3e3e3;
  --highlight-color: #000000;
  --featured-font-family: "Archivo", sans-serif;
  --character-top-image-src: url("../images/characters/kids-on-the-bike.svg");
  --character-top-image-color: #ffffff;
  --character-bottom-image-src: url("../images/characters/inverted-world-monster.svg");
  --character-bottom-image-color: #e5e5e5;
  --background-lamp-image: url("../images/backgrounds/lamps.png");
  --footer-background-color: #b5bbbf;
}

.dark-theme {
  --page-background: linear-gradient(
    180deg,
    #050000 0%,
    #130404 65%,
    rgba(19, 1, 1, 0.75) 100%
  );
  --header-background-color: #220f0f;
  --highlight-color: #ffffff;
  --featured-font-family: "Rubik Glitch", sans-serif;
  --character-bottom-image-src: url("../images/characters/kids-on-the-bike.svg");
  --character-bottom-image-color: rgba(255, 255, 255, 0.1);
  --character-top-image-src: url("../images/characters/inverted-world-monster.svg");
  --character-top-image-color: #000;
  --background-lamp-image: url("../images/backgrounds/lamps-inverted.png");
  --footer-background-color: #000;
}
```

## 📂 Estrutura do Projeto

mundo-invertido                         
├─ src                                  
│  ├─ css                               
│  │  ├─ main.css                       
│  │  └─ styles.css                     
│  ├─ images                            
│  │  ├─ backgrounds                    
│  │  │  ├─ florest.png                 
│  │  │  ├─ lamps-inverted.png          
│  │  │  └─ lamps.png                   
│  │  ├─ banner                         
│  │  │  ├─ florest.webp                
│  │  │  └─ logo.svg                    
│  │  ├─ characters                     
│  │  │  ├─ inverted-world-monster.svg  
│  │  │  └─ kids-on-the-bike.svg        
│  │  ├─ content                        
│  │  │  ├─ inverted-world.png          
│  │  │  ├─ serie-image-01.png          
│  │  │  ├─ serie-image-02.png          
│  │  │  └─ serie-image-03.png          
│  │  ├─ demo                           
│  │  │  └─ demo.gif                    
│  │  ├─ favicon                        
│  │  │  └─ favicon.png                 
│  │  └─ footer                         
│  │     ├─ logo.svg                    
│  │     └─ tape.svg                    
│  ├─ js                                
│  │  ├─ data                           
│  │  │  ├─ config.js                   
│  │  │  ├─ firebase.js                 
│  │  │  └─ hellfire-clube.js           
│  │  └─ main.js                        
│  └─ musics                            
│     ├─ inverted-world.m4a             
│     └─ normal-world.m4a               
├─ index.html                           
└─ README.md                            
