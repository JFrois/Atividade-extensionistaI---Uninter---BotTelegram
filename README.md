  <h1>Atividade-extensionista I - BotTelegram</h1>
    <p>
        Este projeto consiste em um bot do Telegram desenvolvido em Python para auxiliar no acompanhamento da saúde, com foco especial na pressão arterial. 
        Ele fornece informações úteis, permite o preenchimento de formulários diários e integra-se a uma planilha como base de dados para análise.
    </p>

  <h2>Funcionalidades</h2>
    <ul>
        <li>
            <strong>Formulário diário:</strong> O bot fornece um link para preenchimento de um formulário online para registro de dados diários.
        </li>
        <li>
            <strong>Recomendações de aparelhos:</strong> Oferece sugestões de dispositivos confiáveis para medição de pressão arterial.
        </li>
        <li>
            <strong>Central de ajuda:</strong> Direciona o usuário a uma central de suporte ou oferece um número de telefone para contato.
        </li>
        <li>
            <strong>Informações sobre hipertensão arterial:</strong> Compartilha artigos e recursos para aprender mais sobre o tema.
        </li>
    </ul>

  <h2>Como usar</h2>
    <ol>
        <li>Adicione o bot no Telegram usando a chave API fornecida (substitua pela sua ao clonar o repositório).</li>
        <li>Digite os comandos no chat para acessar as opções disponíveis:</li>
        <ul>
            <li><code>/opcao1</code> - Preencher o formulário diário.</li>
            <li><code>/opcao2</code> - Visualizar aparelhos indicados para medir pressão arterial.</li>
            <li><code>/opcao3</code> - Acessar a central de ajuda.</li>
            <li><code>/opcao4</code> - Ler mais sobre hipertensão arterial.</li>
        </ul>
    </ol>
    <h2>Como funciona</h2>
    <p>O bot utiliza a biblioteca <a href="https://pypi.org/project/pyTelegramBotAPI/" target="_blank">PyTelegramBotAPI</a> para interagir com a API do Telegram. Ele responde a mensagens enviadas pelos usuários com base nos comandos reconhecidos, oferecendo links úteis e informações relevantes.</p>
    <h2>Instalação</h2>
    <ol>
        <li>Clone este repositório:</li>
        <pre><code>git clone https://github.com/seu-usuario/seu-repositorio.git</code></pre>
        <li>Instale as dependências:</li>
        <pre><code>pip install pyTelegramBotAPI</code></pre>
        <li>Substitua a variável <code>CHAVE_API</code> no código pela chave do seu bot.</li>
        <li>Execute o script:</li>
        <pre><code>python bot_telegram.py</code></pre>
    </ol>
    <h2>Recursos utilizados</h2>
    <ul>
        <li>Python 3.8+</li>
        <li>Biblioteca <a href="https://pypi.org/project/pyTelegramBotAPI/" target="_blank">PyTelegramBotAPI</a></li>
        <li>Google Forms para coleta de dados</li>
        <li>Planilhas do Google para integração como base de dados</li>
    </ul>
