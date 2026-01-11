README.md - Landing Page Gabriel Dantas Viagens
https://images.unsplash.com/photo-1520250497591-112f2f40a3f4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80

📋 Descrição do Projeto
Este projeto é uma landing page responsiva desenvolvida para a empresa fictícia "Gabriel Dantas Viagens", especializada em viagens para vilarejos europeus autênticos. A página foi criada como parte de um desafio de desenvolvimento web, seguindo boas práticas de HTML5 semântico, CSS3 moderno e JavaScript.

A landing page implementa todos os requisitos solicitados, incluindo banner com overlay de texto, navegação interna com efeitos hover, três seções principais com conteúdo temático e funcionalidades interativas.

✨ Características Principais
Design Responsivo: Adapta-se perfeitamente a dispositivos móveis, tablets e desktops

Navegação Interna Suave: Links âncora com scroll suave entre seções

Banner Atraente: Imagem de vilarejo europeu com overlay de texto

Três Seções Temáticas:

MinhaViagem (TripMe): Apresentação de destinos turísticos

NosEncontre (MeetUs): Formulário de contato funcional

Conselhos (Advice): Dicas práticas para viajantes

Efeitos Visuais: Transições CSS, hover effects, cards interativos

Acessibilidade: HTML semântico, atributos alt, contraste adequado

Performance Otimizada: Código limpo e eficiente

🛠️ Tecnologias Utilizadas
HTML5: Estrutura semântica da página

CSS3: Estilização, layout Flexbox/Grid, animações

JavaScript: Interatividade e funcionalidades dinâmicas

Font Awesome: Ícones para interface

Google Fonts: Tipografia moderna

Unsplash: Imagens de alta qualidade

📁 Estrutura do Projeto
text
gabriel-dantas-viagens/
│
├── index.html          # Estrutura principal da página
├── style.css           # Estilos e layout
├── script.js           # Funcionalidades JavaScript
└── README.md           # Este arquivo de documentação
🚀 Como Executar o Projeto
Método 1: Execução Local
Faça o download dos arquivos:

Baixe os três arquivos (index.html, style.css, script.js) para uma pasta em seu computador

Abra o arquivo HTML:

Navegue até a pasta onde salvou os arquivos

Clique duas vezes no arquivo index.html

A página será aberta automaticamente em seu navegador padrão

Método 2: Usando um Servidor Local (Recomendado)
Instale uma extensão de servidor local (se estiver usando VS Code):

Instale a extensão "Live Server" do VS Code

Clique com o botão direito no arquivo index.html

Selecione "Open with Live Server"

Ou use Python (se instalado):

bash
# Navegue até a pasta do projeto no terminal
cd caminho/para/sua/pasta

# Para Python 3
python -m http.server 8000

# Para Python 2
python -m SimpleHTTPServer 8000

# Acesse no navegador: http://localhost:8000
Método 3: Editor Online (CodePen, JSFiddle, etc.)
CodePen:

Crie um novo Pen

Cole o conteúdo do index.html na aba HTML

Cole o conteúdo do style.css na aba CSS

Cole o conteúdo do script.js na aba JS

Adicione o link do Font Awesome nas configurações externas

JSFiddle:

Siga o mesmo processo do CodePen

Adicione o Font Awesome nas "External Resources":

text
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css
📱 Funcionalidades por Seção
1. Navegação (Navbar)
Menu fixo no topo da página

Links para todas as seções principais

Efeito hover com transição suave

Design responsivo (colapsa em dispositivos móveis)

2. Banner Principal
Imagem de fundo fixa de vilarejo europeu

Overlay escuro para melhor legibilidade do texto

Texto de chamada principal e botão CTA

Posicionamento centralizado vertical e horizontalmente

3. Seção MinhaViagem (TripMe)
Apresenta três vilarejos europeus com cards

Cada card contém imagem, título e descrição

Efeito de elevação ao passar o mouse

Layout responsivo com CSS Grid

4. Seção NosEncontre (MeetUs)
Informações de contato com ícones

Formulário funcional com validação

Feedback visual ao enviar mensagem

Layout em duas colunas (separa em mobile)

5. Seção Conselhos (Advice)
Seis cards com dicas práticas para viajantes

Ícones temáticos para cada conselho

Destaque com borda colorida à esquerda

Layout responsivo com múltiplas colunas

6. Rodapé (Footer)
Informações da empresa

Links rápidos para navegação

Redes sociais com ícones interativos

Copyright e informações legais

🎨 Personalização
Para personalizar este projeto, você pode modificar:

Cores Principais (no arquivo style.css):
css
:root {
  --azul-principal: #4dabf7;
  --azul-escuro: #2c3e50;
  --cinza-claro: #f8f9fa;
  --cinza-escuro: #333;
}
Conteúdo:
Texto: Modifique qualquer texto diretamente no arquivo index.html

Imagens: Substitua as URLs das imagens por suas próprias

Cores: Altere as cores principais no arquivo style.css

Funcionalidades: Adicione novas funcionalidades no script.js

Para alterar o banner:
html
<!-- No arquivo index.html, linha ~64 -->
<section id="home" class="banner">
  <!-- Substitua a URL da imagem no CSS -->
</section>
css
/* No arquivo style.css, linha ~72 */
.banner {
  background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                    url('SUA_IMAGEM_AQUI');
}
🔧 Requisitos Técnicos Atendidos
✅ Requisitos Obrigatórios
Banner dentro da tag <main> com imagem de lugar turístico

Texto overlay (h1/h2) sobre o banner

Navegação mínima (<nav>) com links internos

Três seções nomeadas conforme especificado

Navegação interna funcionando na mesma aba

Efeito hover nos elementos de navegação

Uso de tags semânticas HTML5

✅ Funcionalidades Extras Implementadas
Design responsivo (mobile-first)

Formulário de contato funcional

Scroll suave entre seções

Navegação ativa destacada

Animações CSS nas interações

Cards interativos com efeito hover

Ícones Font Awesome para melhor UX

Rodapé informativo completo

📱 Compatibilidade
Navegadores Testados: Chrome, Firefox, Safari, Edge

Dispositivos: Desktop, Tablet, Mobile

Resoluções: 320px a 1920px+

🐛 Solução de Problemas Comuns
Problema: Imagens não carregam
Solução: Verifique sua conexão com a internet ou substitua as URLs por imagens locais.

Problema: Font Awesome não aparece
Solução: Certifique-se de estar conectado à internet ou use uma versão local dos ícones.

Problema: Formulário não envia
Solução: A função está configurada apenas para demonstrar o funcionamento. Para produção, conecte a um backend.

Problema: Layout quebrado em mobile
Solução: Verifique se os três arquivos estão na mesma pasta e recarregue a página.

📄 Licença
Este projeto foi desenvolvido para fins educacionais e de portfólio. Sinta-se à vontade para usá-lo, modificá-lo e distribuí-lo, dando os devidos créditos.

👨‍💻 Desenvolvedor
Gabriel Santos Dantas
Desenvolvedor Front-End

📬 Contato
Para dúvidas, sugestões ou oportunidades:

Email: sro.danttas@gmail.com

GitHub: https://github.com/Gabriel-Santos-Dantas86

LinkedIn: https://www.linkedin.com/in/gabriel-dantas-3010a488?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
