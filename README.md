# POC_6

# Sistema de Gerenciamento de Assentos de Cinema 🎥
Este é um sistema interativo para gerenciar a seleção de assentos de cinema. Ele foi desenvolvido usando React e CSS Modules, e inclui funcionalidades como troca de tema, visualização de detalhes do filme, e cálculo do valor total dos assentos selecionados.

#📜 Funcionalidades

Seleção de Assentos: Escolha entre assentos disponíveis, especiais e indisponíveis.
Detalhes do Filme: Visualize informações detalhadas sobre o filme em exibição.
Tema Escuro/Claro: Alterne entre os temas para melhor experiência.
Cálculo de Preço: Exibe o valor total dos assentos selecionados.
Responsividade: Layout ajustável para diferentes tamanhos de tela.

#🖼️ Demonstração

Mapa de assentos interativo.
Informações do filme.
Legenda explicativa dos tipos de assentos.

#🚀 Instalação e Execução
*Pré-requisitos*

Node.js e npm instalados.
Ambiente configurado para React.

*Passos*
Clone o repositório:
```git clone https://github.com/usuario/repo-gerenciamento-assentos.git```
Navegue até o diretório do projeto:
```Navegue até o diretório do projeto:```
Instale as dependências:
```npm install```
Inicie o servidor de desenvolvimento:
```npm start```
#🗂️ Estrutura do Projeto
```
📂 src
├── 📂 componentes
│   ├── Assento.js
│   ├── BotaoTrocaTema.js
│   ├── DetalhesDoFilme.js
│   ├── Legenda.js
│   └── MapaDeAssentos.js
├── 📂 estilos
│   ├── Assento.module.css
│   ├── DetalhesDoFilme.module.css
│   ├── Legenda.module.css
│   ├── MapaDeAssentos.module.css
│   ├── page.module.css
│   └── globals.css
├── Page.js
└── assentos.json
```
#🛠️ Tecnologias Utilizadas
```
React: Biblioteca JavaScript para criação de interfaces.
CSS Modules: Para estilização modular e reutilizável.
JSON: Para configuração e simulação de dados.
```
#📖 Detalhes do Código
*Principais Componentes:*
Assento.js: Renderiza cada assento individualmente.
BotaoTrocaTema.js: Altera o tema da aplicação (claro/escuro).
DetalhesDoFilme.js: Exibe informações sobre o filme.
MapaDeAssentos.js: Gera o mapa interativo de assentos.
Legenda.js: Mostra a legenda explicativa dos tipos de assentos.
*Estilos:*
CSS Modules: Cada componente possui um arquivo de estilo modular para facilitar a manutenção e evitar conflitos de classes.
*Configuração de Assentos:*
assentos.json: Define os assentos disponíveis, indisponíveis e especiais.
#🧑‍💻 Como Contribuir

Faça um fork do projeto.
Crie uma nova branch para sua funcionalidade:
```git checkout -b minha-feature```
Commit suas mudanças:
```git commit -m "Adiciona nova funcionalidade```
git commit -m "Adiciona nova funcionalidade":
```git push origin minha-feature```
Abra um Pull Request.

# Desenvolvido com 💻 por Marcos Oliveira 10437530/ Wagner Araujo Marcelino Junior RA 10440125 / Pedro Henrique Araujo 10442579
