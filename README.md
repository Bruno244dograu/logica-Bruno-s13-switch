# Switch Case em JavaScript
**Atenção:** A atividade pode ser feita sozinho ou em dupla, mas o envio deve ser feito individualmente.

### Conteúdos
1. Estrutura de Projeto
2. Manipulação de conteúdo
3. Implementação do Switch Case

## Passo 1: Estrutura do Projeto
Antes de começar a atividade, é essencial entender como funciona uma página web.

Basicamente, um site é construído a partir de três tipos de arquivos: ``HTML``, ``CSS`` e ``JavaScript``.

O ``HTML`` é a base da página, responsável por definir sua estrutura e organizar o conteúdo. Tudo isso fica dentro de um arquivo ``.html``.

O ``CSS`` entra em cena para dar estilo ao site. Com ele, você pode mudar cores, fontes, fundos e até criar animações e efeitos visuais.

Já o ``JavaScript`` é o que torna a página interativa. Ele permite criar funcionalidades dinâmicas e colocar a lógica dos nossos aplicativos web dentro de arquivos ``.js``.

## Passo 2: Manipulação de conteúdo
Para manipular uma página web com JavaScript, é importante entender como acessar a estrutura HTML. Dentro do JavaScript, conseguimos fazer isso por meio da palavra ``document``.

Com ela, podemos usar métodos para encontrar elementos específicos da página. Um dos mais usados é o ``document.getElementById('idNomeDoElemento')``, que busca um elemento pelo seu ID.

Veja um exemplo:  
```HTML
<body>
    <div id="meuElemento">
        <p>Olá meus lindos!</p>
        <p>Eu sou uma página web :D</p>
    </div>
</body>
```

```JavaScript
let meuElemento = document.getElementById('meuId');
console.log(meuElemento);
```

## Passo 3: Implementação do Switch Case
No arquivo ``script.js``, implemente a lógica do Switch Case para tratar as condições do projeto. Dê uma boa analisada no código, faça as modificações e correções necessárias e teste tudo para garantir que está funcionando corretamente.

Depois de finalizar o projeto, lembre-se de enviar o link da atividade para a plataforma AVA na Semana 13.

📌 Assunto: Lógica de Programação - 2º Bimestre 🔹 Tema da Semana 13: Comandos Condicionais - Switch

Exemplo de implementação de Switch:

```JavaScript
function exemploDeSwitch() {
    const valorSelecionado = document.getElementById('selecionador').valor;

    switch (valorSelecionado) {
        case 'opcao1':
            console.log('Opção 1 foi selecionada');
            break;
        case 'opcao2':
            console.log('Opção 1 foi selecionada');
            break;
        case 'opcao3':
            console.log('Opção 1 foi selecionada');
            break;
        default:
            console.log('Nada foi selecionado :(');
            console.log('Qualquer coisa :/');
    }
}
```