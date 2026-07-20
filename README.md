# Flow Gestão e Carreira — Landing Page

Landing page institucional desenvolvida para a **Flow Gestão e Carreira**, consultoria especializada em gestão estratégica de pessoas, arquitetura organizacional, desenvolvimento de lideranças e melhoria de processos.

## Demonstração

O projeto foi construído em uma única página, com navegação fluida e layout responsivo para desktop, tablet e celular.

## Funcionalidades

- Design responsivo
- Navegação por seções
- Botões de contato via WhatsApp
- Apresentação institucional
- Área de soluções e diferenciais
- Cases demonstrativos
- Depoimentos demonstrativos
- Menu adaptado para dispositivos móveis
- Imagens otimizadas em WebP
- Estrutura pronta para GitHub Pages

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Layout responsivo com CSS Grid e Flexbox

## Estrutura do projeto

```text
flow-gestao-carreira-landing-page/
├── assets/
│   ├── logo-flow-branca.png
│   ├── debora-retrato.webp
│   ├── debora-palestra.webp
│   ├── workshop-01.webp
│   └── workshop-02.webp
├── index.html
├── .gitignore
├── LICENSE
└── README.md
```

## Como executar localmente

Você pode abrir o arquivo `index.html` diretamente no navegador.

Para trabalhar com um servidor local:

```bash
python -m http.server 5500
```

Depois, acesse:

```text
http://localhost:5500
```

Também é possível utilizar a extensão **Live Server** no Visual Studio Code.

## Configuração do WhatsApp

No final do arquivo `index.html`, localize:

```javascript
const whatsappNumber = "5511999999999";
const whatsappMessage = "Olá! Conheci a Flow pelo site e gostaria de conversar sobre um projeto.";
```

Substitua o número pelo WhatsApp real, usando:

```text
55 + DDD + número
```

Exemplo:

```javascript
const whatsappNumber = "5518999999999";
```

## Publicação no GitHub Pages

1. Acesse o repositório no GitHub.
2. Entre em **Settings**.
3. Clique em **Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main`.
6. Selecione a pasta `/root`.
7. Clique em **Save**.

O endereço ficará semelhante a:

```text
https://seuusuario.github.io/flow-gestao-carreira-landing-page/
```

## Observação importante

Os cases e depoimentos presentes nesta versão são **demonstrativos/fictícios** e devem ser substituídos por informações reais e autorizadas antes da publicação comercial definitiva.

As fotografias e a identidade visual pertencem à cliente e não devem ser reutilizadas em outros projetos sem autorização.

## Autor

Desenvolvido por **Adriano Meneguetti**.

---

Projeto criado para fins profissionais e de portfólio.
