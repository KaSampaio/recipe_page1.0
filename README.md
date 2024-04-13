# Frontend Mentor - Solução de página de receitas

Esta é uma solução para o [desafio da página de receitas no Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação através da construção de projetos realistas.

## Índice

- [Visão geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Captura de tela](#Captura-de-tela)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que aprendi](#o-que-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
  - [Recursos úteis](#useful-resources)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

**Observação: exclua esta nota e atualize o índice com base nas seções que você mantém.**

## Visão geral

### O desafio

Este desafio o ajudará a se concentrar na escrita de HTML semântico. Certifique-se de pensar em quais elementos HTML são mais apropriados para cada parte do conteúdo

### Captura de tela

![](./assets/image/Screenshot%202024-04-10%20at%2021-17-50%20Document.png)

###Links

- URL da solução: [Adicione o URL da solução aqui](https://your-solution-url.com)
- URL do site ativo: [Adicione o URL do site ativo aqui](https://your-live-site-url.com)

## Meu processo

### Construído com

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### O que eu aprendi

Neste desafio, tentei aprimorar a parte semantica do código, usando a tag "main" para organizar melhor, deixando-o mais compreensivo. Também aprimorei a criação de tabelas no HTML. 
No CSS, consegui alterar as cores dos marcadores para ficarem diferentes do texto, tive um pouco de dificuldade, porém busquei auxilio no google e consegui fazer o ajuste. 


```html
 <main class="container_recipe">
      <div class="recipe_information">
        <div class="recipe_image">
          <img
            src="./assets/image/image-omelette.jpeg"
            alt="A Simple Omelette"
          />
        </div>
        <div class="recipe_title">
          <h1>Simple Omelette Recipe</h1>
          <p>
            An easy and quick dish, perfect for any meal. This classic omelette
            combines beaten eggs cooked to perfection, optionally filled with
            your choice of cheese, vegetables, or meats.
          </p>
        </div>
      </div>
      <div class="preparation_time">
        <h3>Preparation time</h3>
        <ul>
          <li>
            <span class="bold">Total:</span>
            <span>Approximately 10 minutes</span>
          </li>
          <li><span class="bold">Preparation:</span> <span>5 minutes</span></li>
          <li><span class="bold">Cooking:</span> <span>5 minutes</span></li>
        </ul>
      </div>
      <div class="recipe">
        <h2>Ingregients</h2>
        <ul class="ingredients">
          <li><span> large eggs</span>
          </li>
          <li><span>Salt, to taste </span></li>
          <li><span>Pepper, to taste</span></li>
          <li><span>1 tablespoon of butter or oil</span></li>
          <li><span>
            Optional fillings: cheese, diced vegetables, cooked meats, herbs</span>
          </li>
        </ul>
        <hr />
        <div class="instruction_container">
          <h2>Instructions</h2>
          <ol class="Instructions">
            <li>
              <span class="bold">Beat the eggs:</span> <span>In a bowl, beat the eggs
              with a pinch of salt and pepper until they are well mixed. You can
              add tablespoon of water or milk for a fluffier texture.</span>
            </li>
            <li>
              <span class="bold">Heat the pan:</span> <span> a non-stick frying
              pan over medium heat and add butter or oil. </span>
            </li>
            <li>
              <span class="bold">Cook the omelette:</span> 
              <span>Once the butter is
              melted and bubbling, pour in the eggs. Tilt the pan to ensure the
              eggs evenly coat the surface.</span>
            </li>
            <li>
              <span class="bold">Add fillings (optional):</span> <span>When the egs
              begin to set at the edges but are still slightly runny in the
              middle, sprinkle your chosen fillings over one half of the
              omelette.</span>
            </li>
            <li>
              <span class="bold">Fold and serve:</span> <span>>As the omelette
              continues to cook, carefully lift one edge and fold it over the
              fillings. Let is cook for another minute, then slide it onto a
              plate.</span>
            </li>
            <li>
              <span class="bold">Enjoy:</span> <span>Serve hot, with additional salt
              and papper if needed. </span>
            </li>
          </ol>
        </div>
      </div>
      <hr />
      <div class="nutrition">
        <h2>Nutrition</h2>
        <p>
          The table below shows nutitional values per serving without the
          additional fillings.
        </p>

        <table>
          <tbody>
            <tr>
              <td class="coluna1">Calories</td>
              <td class="coluna2">277kcal</td>
            </tr>

            <tr>
              <td class="coluna1">Carbs</td>
              <td class="coluna2">0g</td>
            </tr>

            <tr>
              <td class="coluna1">Protein</td>
              <td class="coluna2">20g</td>
            </tr>

            <tr>
              <td class="coluna1">Fat</td>
              <td class="coluna2">22g</td>
            </tr>
          </tbody>
        </table>
      </div>
    </main>
```

```css
.preparation_time {
  padding: 10px 0 20px 30px;
  background-color: #fce8f5a4;
}

.preparation_time h3 {
  color: hsl(332, 51%, 32%);
}

.preparation_time ul li {
  color: hsl(332, 51%, 32%);
  padding: 5px 20px;
}

.preparation_time ul li span {
  color: hsl(24, 5%, 18%);
}
```

### Desenvolvimento contínuo

Acredito que preciso desenvolver melhor a semantica do meu código, e também os alinhamentos de DIV que ainda tenho uma certa dificuldade. No decorrer dos próximos desafios vou focar nesses pontos, para melhorar na prática. 🚀

### Recursos úteis

- [Alterar cor do marcador para ficar diferente do texto](https://x.gd/IzEr6) - Isso me ajudou no ajuste das cores entre o marcador e o texto.
- [HTML Semantic Elementes](https://x.gd/cI39Q) - Este é um artigo incrível que me ajudou a finalmente entender a semântica do HTML. Eu recomendo para quem ainda está aprendendo esse conceito.


## Autor

- Site - [Ka Sampaio](https://github.com/KaSampaio)
- Mentor de Frontend - [@KaSampaio](https://www.frontendmentor.io/profile/KaSampaio)


## Agradecimentos

Gostaria de agradecer ao Frontend Mentor por fornecer este projeto desafiador que me permitiu aprimorar minhas habilidades em desenvolvimento frontend. O projeto foi uma ótima oportunidade para aprender e crescer como desenvolvedor.

Além disso, agradeço a todos os tutoriais, artigos e discussões online que me ajudaram ao longo do caminho. A comunidade de desenvolvimento é uma fonte inestimável de conhecimento e apoio.