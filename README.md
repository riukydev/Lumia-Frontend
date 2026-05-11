Studio Lumina - Landing Page 🏛️✨

Este projeto contém o código-fonte de uma landing page profissional, moderna e minimalista desenvolvida para o Studio Lumina, um estúdio focado em Arquitetura e Design de Interiores.

O design transmite elegância, luxo e confiança institucional, utilizando uma paleta de cores claras (light mode) e tipografia premium.

🌟 Principais Funcionalidades

Design Minimalista e Premium: Uso inteligente de whitespace (espaço em branco), tipografia clássica (Serifa + Sem Serifa) e tons terrosos/areia.

Totalmente Responsivo: Experiência de navegação perfeita em telemóveis, tablets e computadores de secretária (Desktop).

Animações de Alta Performance: Efeitos de revelação suaves ao fazer scroll, construídos com a API nativa IntersectionObserver (sem bibliotecas externas pesadas).

Navegação Inteligente: Cabeçalho que altera o seu estado visual ao rolar a página (Sticky Header com efeito de desfoque/blur).

Código Num Só Ficheiro: Todo o HTML, CSS e JavaScript estão integrados de forma limpa no mesmo ficheiro index.html para fácil implementação e teste imediato.

🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando apenas tecnologias web fundamentais (Vanilla), garantindo máxima velocidade e facilidade de manutenção:

HTML5: Estrutura semântica e acessível.

CSS3: Variáveis CSS (Custom Properties), Flexbox, CSS Grid e media queries para responsividade.

JavaScript (Vanilla): Lógica do menu mobile, transição do cabeçalho e observador de elementos para as animações de entrada.

Google Fonts: Lora (Títulos) e Montserrat (Corpo do texto).

🚀 Como Utilizar

Não é necessária nenhuma instalação complexa ou ambiente de desenvolvimento específico (Node.js, npm, etc.).

Faça o download ou clone este repositório.

Dê um duplo clique no ficheiro index.html para abri-lo no seu navegador web preferido (Google Chrome, Firefox, Safari, Edge).

Para modificar o código, abra o ficheiro em qualquer editor de texto ou código (como o Visual Studio Code, Sublime Text, etc.).

🎨 Como Personalizar (Variáveis CSS)

O projeto foi construído com Variáveis CSS globais, facilitando imenso a alteração de todo o esquema de cores e estrutura com apenas alguns cliques.

No início da secção <style> do ficheiro index.html, encontrará o bloco :root:

:root {
    --bg-main: #FFFFFF;      /* Cor de fundo principal */
    --bg-alt: #F7F6F2;       /* Cor de fundo secundária (secções alternadas) */
    --text-dark: #2C2C2C;    /* Cor principal do texto e cabeçalhos */
    --text-muted: #6B6B6B;   /* Cor do texto secundário (parágrafos) */
    --accent: #B59A7A;       /* Cor de destaque (botões, ícones, linhas) */
    --accent-hover: #987E60; /* Cor de destaque ao passar o rato (hover) */
    
    --font-head: 'Lora', serif;          /* Fonte dos títulos */
    --font-body: 'Montserrat', sans-serif; /* Fonte dos textos */
}


Basta alterar os códigos hexadecimais (ex: #B59A7A) para as cores da sua marca, guardar o ficheiro e recarregar a página!

📱 Menu Mobile

O menu de navegação colapsa automaticamente num menu estilo "hambúrguer" em ecrãs menores que 768px. O JavaScript incluído gere a abertura, fecho e o bloqueio de rolagem do fundo enquanto o menu está aberto, garantindo uma excelente experiência de utilizador (UX).

📄 Licença

Este projeto é de código aberto e pode ser utilizado para fins pessoais ou comerciais. Sinta-se à vontade para o modificar e adaptar às suas necessidades!
