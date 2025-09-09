Termo de Agendamento Sonare
Esta é uma aplicação web de página única (single-page application) para agendamento de exames. A aplicação foi desenvolvida para coletar dados de pacientes, exibir termos de agendamento e obter uma assinatura digital, gerando um documento PDF para download.

Funcionalidades
Formulário em Múltiplos Passos: A experiência do usuário é guiada através de um formulário dividido em quatro etapas:

Dados Pessoais: Coleta de informações como nome, data de nascimento, CPF, gênero, endereço e telefone.

Termos de Agendamento: Exibição dos termos de serviço, com a opção de visualização em tela cheia para uma leitura mais confortável.

Assinatura: Um campo de assinatura digital sensível ao toque para capturar a rubrica do paciente.

Confirmação: Um resumo dos dados preenchidos antes da finalização.

Geração de PDF Dinâmico: Após a finalização, a aplicação gera um PDF com todos os dados do paciente, os termos de agendamento e a assinatura capturada. O nome do arquivo PDF gerado inclui o nome do paciente e a data atual, por exemplo, Termo_Agendamento_Sonare_Nome_do_Usuario_2025-09-08.pdf.

Botão "Assinar Novo Termo": Este botão, que só é habilitado após o download do PDF ser iniciado, permite que o usuário limpe o formulário e inicie um novo agendamento, facilitando o uso consecutivo da aplicação.

Máscaras de Input: Os campos de data, CPF e telefone possuem máscaras de entrada para garantir a correta formatação dos dados.

Teclado Numérico em Mobile: Nos campos de data e CPF, a aplicação abre automaticamente o teclado numérico em dispositivos móveis, melhorando a usabilidade.

Design Responsivo: A interface é adaptada para funcionar de forma intuitiva em desktops e dispositivos móveis.

Tecnologias Utilizadas
A aplicação é construída com tecnologias web básicas, utilizando bibliotecas externas para funcionalidades específicas.

HTML5, CSS3, JavaScript: A estrutura, o estilo e a lógica da aplicação.

jsPDF: Biblioteca para a geração do documento PDF diretamente no navegador.

Signature Pad: Biblioteca para a criação e captura da assinatura digital em um canvas.

Font Awesome: Para os ícones de download, WhatsApp, e navegação.

Como Usar
Abra o arquivo index.html em qualquer navegador web.

Preencha as informações solicitadas em cada passo.

Leia e aceite os termos de agendamento.

Assine no campo designado.

Confirme os dados e clique em "Finalizar".

Clique em "Baixar PDF" para salvar o documento em seu dispositivo.

Clique em "Assinar Novo Termo" (botão habilitado após o download) para resetar o formulário.

Estrutura do Projeto
O projeto é composto por um único arquivo, index.html, que contém todo o HTML, CSS e JavaScript necessários para a aplicação. As bibliotecas externas são carregadas via CDN.

/
└── index.html