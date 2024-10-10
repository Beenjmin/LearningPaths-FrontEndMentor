# Frontend Mentor - QR code component solution

Primeira solução criada para o desafio QR Code component fornecida pelo FrontEnd Mentor atraves do seguimento Learning Paths.
- O desafio consiste na criação de uma página estática com um conteiner de conteúdo fornecendo a imagem de QR Code e uma descrição abaixo dele. Design encontra-se abaixo.

![design page QR COde componente](./preview.jpg)

### Links
Solução do projeto encontra-se hospedada pelo Vercel pelo seguinte link abaixo:

Vercel: [https://qrcode-page.vercel.app/](https://qrcode-page.vercel.app/)

### Tecnologias utilizadas

- HTML and CSS static.

### What I learned

Foi meu primeiro projeto prático envolvendo criação de páginas a partir do zero, como um desafio pra mim. Consegui, ao todo, colocar em prática parte do conhecimento adquirido sobre FrontEnd até agora, contemplando quase todo cenário da criação da solução.
Consegui colocar em pratica alguns fundamentos de posicionamento e praticar melhor soluções envolvendo imagens, voltando para a utilização do `background-imagem` em CSS.
A solução não apresenta uso do FlexBox ou grid para manipulação de posicionamento por escolha própria, para praticar centralização de objetos de outras formas.

Meu principal desafio foi criar o conteiner principal e sua estilização e centralização, para que os elementos dentro dele ficassem da maneira certa.

```CSS:
.centerConteiner{
    background-color: hsl(0, 0%, 100%);
    border-radius: 10px; /* certo. */
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    max-width: 250px;

    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);

    padding: 15px;
}
```

### Autor:
Benjamin Marcos
Github: [https://github.com/Beenjmin](https://github.com/Beenjmin)

---