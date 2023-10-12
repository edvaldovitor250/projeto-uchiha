# Projeto Uchiha

https://github.com/edvaldovitor250/Projeto-Uchiha-/assets/116117189/f332829c-81d6-48a9-8f8a-c08bab60b303

Bem-vindo ao meu novo projeto relacionado ao universo Uchiha! Este projeto tem uma estética inspirada em Naruto e os clãs Uchiha. Abaixo, você encontrará algumas das principais mudanças implementadas no código CSS:

## Destaques das Mudanças CSS

### 1. Destaque das Letras

Quando o cursor passa sobre as letras no projeto, elas mudam para a cor vermelha.

.personagem:hover h2,
.personagem:hover p {
  color: rgb(224, 9, 9);
}
2. Efeito de Botões
Os botões se movem ligeiramente para cima quando o cursor passa sobre eles.

.botao:hover {
  transform: translateY(-5px);
}

3. Animação de Troca de Botões
Quando ocorre a troca de botões, o nome do personagem e a descrição caem lentamente.

.nome-personagem {
  animation: letraCaindo 0.9s ease-in-out;
  animation-fill-mode: both;
}

.conteudo .descricao {
  animation: letraCaindo 2s ease-in-out;
  animation-fill-mode: both;
}

4. Efeito de Imagem
Ao passar o mouse sobre a descrição, a imagem fica ligeiramente mais escura.

.descricao:hover .imagem {
  opacity: 0.8;
}

5. Logo Interativa
Ao passar o cursor sobre a logo, ela dá um pequeno salto para frente.

.logo:hover {
  transform: translate3d(0, -2px, 0);
}

Fique à vontade para explorar o projeto e aproveitar a nova estética Uchiha inspirada por Naruto!
