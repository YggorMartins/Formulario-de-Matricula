Este projeto, é um formulário de matrícula online para uma escola de educação infantil. O projeto foi desenvolvido durante o curso "FULLSTACK" da Rocketseat, com a orientação do professor Mayk Brito, e foca na criação de formulários e no uso de CSS com a sintaxe de nesting.

### Funcionalidades do Formulário:

O formulário é composto por várias seções para coletar diferentes tipos de informações:

* **Informações da criança**: Inclui campos para o nome completo, data de nascimento, sexo e informações médicas.
* **Endereço residencial**: Esta seção coleta o CEP, rua, número, cidade e estado.
* **Informações do responsável**: Campos para o nome, telefone e e-mail do responsável legal.
* **Opções de matrícula**: Onde é possível selecionar o turno de estudo (manhã ou tarde) e o esporte em que a criança será matriculada.

### Pontos de Aprendizagem:

O desenvolvimento deste projeto permitiu a aplicação de diversas técnicas e conceitos importantes para a criação de formulários web, com um foco especial no design e na usabilidade.

#### Estrutura HTML
* **Semântica**: O HTML foi estruturado com tags como `<form>`, `<fieldset>`, `<legend>`, `<label>` e `<input>`, garantindo uma organização clara e semântica do conteúdo.
* **Acessibilidade**: A utilização de atributos como `for` e `id` associou rótulos (labels) a seus respectivos campos de entrada (inputs), o que é fundamental para a acessibilidade.
* **Validação**: A inclusão de atributos como `required` e o uso de tipos de `input` (como `email` e `date`) demonstram como realizar validações básicas no lado do cliente.

#### Estilização com CSS
* **Variáveis CSS**: O uso de variáveis CSS (`--font-family`, `--text-primary`, etc.) no arquivo `global.css` permitiu uma gestão mais eficiente de cores, tipografia e outros estilos, facilitando a manutenção e a consistência visual.
* **Layout**: Foram utilizadas propriedades como `flexbox` e `grid` para a criação de layouts responsivos e flexíveis, como o layout principal da página (`#app`) e o alinhamento de campos de endereço e botões.
* **Nesting (Aninhamento) CSS**: A utilização da sintaxe de nesting (aninhamento) CSS foi um dos principais pontos de aprendizado. Isso permitiu a organização do código CSS de forma hierárquica e mais legível, agrupando estilos de elementos filhos diretamente dentro dos seletores de seus pais. Exemplos claros podem ser vistos nos arquivos `radio.css` e `checkbox.css`, onde os estados de `hover`, `focus-within` e `:has(:checked)` são aninhados dentro do seletor principal.
* **Personalização de Componentes**: Foram criados componentes reutilizáveis e estilizados de forma personalizada, como os botões (`buttons.css`), os campos de rádio (`radio.css`) e os campos de seleção de arquivo (`droparea.css`).
* **Pseudo-classes e Pseudo-elementos**: O projeto faz uso de pseudo-classes como `:hover`, `:focus-within` e `:has` para alterar a aparência de elementos com base em seu estado. Pseudo-elementos também foram usados para personalizar elementos de formulário, como o seletor de data (`::-webkit-calendar-picker-indicator`).
