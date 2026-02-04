Guia Prático: Fundamentos da Web e HTML

Fala, dev! Se você está começando agora, entender a dinâmica entre quem pede e quem entrega a informação é o primeiro passo para dominar o desenvolvimento web. Vamos passar pelos conceitos de infraestrutura até a prática da marcação.

1. A Dinâmica Client-Server e Navegadores
   No linguajar web, temos dois atores principais: 
   - o Client (Cliente) e o Server (Servidor). O Cliente: É o seu dispositivo (PC, celular) consumindo a internet. Quando você digita uma URL, o cliente envia uma requisição.
   - O Servidor: É a máquina que recebe o pedido e retorna os arquivos necessários: HTML, CSS, JavaScript e imagens.
   - O Cache: Para não ficar "indo e vindo" no servidor sem necessidade, o navegador armazena arquivos temporariamente. Isso economiza banda e tempo.
   - Navegadores e W3C: O navegador serve para interpretar os códigos. Para que um site não pareça quebrado em um browser e perfeito em outro, o Padrão W3C define as regras que todos devem seguir.

        Dica de mestre: Use o site W3Schools para verificar se uma tag ou comando funciona no navegador que seu usuário utiliza.
        
2. Servidores e InfraestruturaUm servidor não é apenas um "computador ligado". Ele é composto por camadas:
   - Hardware: Focado em processamento e armazenamento pesado (SSDs e muita memória RAM).
   - Software: Sistemas como Ubuntu, Debian ou Windows Server, rodando serviços como Apache ou Nginx.
   - 
**Tipos de Servidores que você precisa conhecer:**

Proxy: Intermedeia a conexão (comum em empresas para filtrar acesso).Firewall: A barreira de segurança contra acessos externos.DNS: O "RG" da internet. Ele traduz o nome do site (https://www.google.com/search?q=google.com) para o IP da máquina.FTP: O protocolo padrão para transferir seus arquivos para a hospedagem.3. Linguagens e o Papel do JavaScriptExistem linguagens que rodam no servidor (Back-end) e linguagens que rodam no navegador (Front-end).Server-side: PHP, Python, C#, Java e o próprio JavaScript (via Node.js).Client-side: Aqui o JavaScript reina absoluto, interpretado pelo motor V8 (o mesmo do Chrome).Atenção: O HTML não é uma linguagem de programação, mas sim uma linguagem de marcação. Assim como um arquivo CSV organiza dados, o HTML organiza a estrutura do que vemos.4. HTML na Prática: Mão na MassaPara começar, usamos o VS Code com a extensão Live Server para ver as alterações em tempo real. A estrutura básica de qualquer página segue este esqueleto:HTML<html>
    <head>
        <title>Meu Aprendizado DIO</title>
    </head>
    <body>
        Conteúdo visível aqui.
    </body>
</html>
Dominando as Tags de Texto (Tipografia)Ao escrever seu conteúdo, use a semântica correta para que o Google e os leitores de tela entendam sua página:Hierarquia: Utilize <h1> para o título principal e de <h2> até <h6> para subtítulos.Parágrafos: O texto comum deve estar sempre dentro de <p>.Ênfase: Se algo é urgente ou muito importante, use <strong>. Para termos técnicos ou estrangeirismos, use <i> (itálico).Destaques: Quer simular um marca-texto? Use a tag <mark>. Para letras miúdas (como direitos autorais), use <small>.Estilos Específicos: * Para fórmulas como $H_2O$, use <sub> (subscrito).Para potências como $x^2$, use <sup> (sobrescrito).Para sublinhar algo que precisa de atenção, use <u>.Separação: Para criar uma quebra temática entre assuntos, a tag <hr> cria uma linha horizontal.Citações e ListasSe for citar algum autor ou referência externa, utilize o <blockquote>, que dá um recuo visual no texto. Para organizar informações, temos dois tipos de listas:Ordenadas (<ol>): Quando a ordem importa (1, 2, 3...).Não Ordenadas (<ul>): Quando a ordem não importa (pontinhos/bullets).Itens (<li>): Cada item da lista, seja ela qual for, deve estar dentro desta tag.Links e AtributosA tag <a> (âncora) é o que conecta a web. Ela usa o atributo href para apontar o destino.Nota sobre Atributos: Tags como <img> ou <input> não costumam ter fechamento e dependem de atributos (como src para o caminho da imagem ou type para o tipo do campo de texto) para funcionar corretamente.