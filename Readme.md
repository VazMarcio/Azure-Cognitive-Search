<h1>EXPLORANDO UM ÍNDICE DO AZURE AI SEARCH (UI)</h1>
<hr>
Neste laboratório você irá:
<ul>
    <li>Criar recursos do Azure</li>
    <li>Extrair dados de uma fonte de dados</li>
    <li>Enriquecer os dados com habilidades de IA</li>
    <li>Utilizar o indexador do Azure no portal do Azure</li>
    <li>Consultar o índice de pesquisa</li>
    <li>Revisar os resultados salvos em uma loja de conhecimento</li>
</ul>
<hr>
Neste laboratório será usado os seguintes recursos:
<ul>
    <li><b>Um Recurso do Azure AI Search</b>, que grenciará a indexação e a consulta.</li>
    <li><b>Um Recurso de Seviços do IA do Azure</b>, que irá fornecer serviços de <br>
    IA para habilidades que sua solução de pesquisa pode usar para enriquecer os  <br>
    dados na fonte de dados com insights gerados por IA.</li>
    <li><b>Uma Conta de Armazenamento</b> com containers de blobs, que armazenará documentos <br>
    brutos e outras coleções de tabelas, objetos e arquivos.</li>
</ul>
<hr>
<h2>Primeiro Passo:</h2>
<h3>RECURSO DO AZURE AI SEARCH</h3>
Criar um recurso do Azure AI Search, esse recurso deve ser feito no <b>Azure AI Search</b>
<ul>
    <li><b>Grupo de Recursos:</b> Selecionar,  ou criar um grupo de recursos com um nome exclusivo.</li>
    <li><b>Nome do Serviço:</b> Nome eclusivo.</li>
    <li><b>Localização:</b> Dê preferência para East U2</li>
    <li><b>Nivel de Preços:</b> Básico</li>
</ul>
Depois de feito, selecione <b>Review + create</b>, depois de ser validado, selecione <b>Create</b>
Após o término da implantação, selecione <b>Ir para o recurso</b>
<hr>
<h2>Segundo Passo:</h2>
<h3>CRIAR UM RECURSO DE SERVIÇOS DE IA DO AZURE</h3>
Você precisará provisionar um recurso <b>de serviços de IA do Azure</b> que esteja no mesmo local que seu recurso do Azure AI Search. Sua solução de pesquisa usará esse recurso para enriquecer os dados no armazenamento de dados com insights gerados por IA.
Retorne à página inicial do portal do Azure. Clique no botão Criar um recurso e pesquise os serviços de IA do Azure. Você será levado a uma página para criar umrecursos de serviços de IA do Azure.
<ul>
    <li><b>Grupo de Recursos:</b> O mesmo grupo de recursos que seu recurso do Azure AI Search</li>
    <li><b>Região:</b> O mesmo local do Recurso do Azure AI earch.</li>
    <li><b>Nome:</b> Um nome exclusivo.</li>
    <li><b>Nível de preços:</b> Padrão SO</li>
</ul>
Marcar a próxima caixa onde: confirmo que li e compreendi todos os termos.
Obs: Selecione Revisar + Criar, depois de tudo estiver validado, selecione Create.
Depois da conclusão visualize os detalhes da implantação.
<hr>
<h2>Terceiro Passo:</h2>
<h3>CRIE UM CONTA DE ARMAZENAMENTO</h3>
Retorne novamente à página inicial do portal do Azure e selecione o botão 
<b>Criar um Recurso</b>
Procure por <b>conta de armazenamento</b> e crie um recurso <b>de conta de armazenamento</b> com as seguintes configurações:
<ul>
    <li><b>Grupo de recursos:</b> O mesmo grupo de recursos do Azure AI Search e dos Serviços Azure AI.</li>
    <li><b>Nome da conta de armazenamento:</b> Um nome exclusivo</li>
    <li><b>Localização:</b>East U2</li>
    <li>Padrão <b>de desempenho</b></li> 
    <li><b>Redundância:</b> armazenamento localmente redundante (LRS)
</ul>
Clique em <b>Revisar</b> e em <b>Criar</b> Aguarde a conclusão e vá para o recurso implantado
Na conta de armazenamento do Azure que você criou, no painel de menu esquerdo, selecione <b>Confiuração</b> em configurações atere a configuração de Permitir acesso anônimo de Blob para <b>Habilitado e selecione <b>Salvar</b>
<hr>
<h2>Quarto Passo:</h2>
<h3>CARREGAR OS DOCUMENTOS PARA O ARMAZENAMENTO DO AZURE</h3>
Selecione <b>containers</b> no painel esquerdo, será abeto um painel do seu lado direito.
Crie o documento:
<ul>
    <li><b>Nome:</b> coffeereviews(Desse jeito mesmo, letras minusculas e tudo junto)</li>
    <li><b>Nivel de acesso público:</b> (Acesso de leitura anônima para conteiners e blobs)</li>
    <li><b>Avançado:</b> sem alterações.
</ul>
Depois de ter baixado os documentos, no portal do Azure, e depois que o upload for concluído, você <br>
pode fechar o painel upload blob.
<hr>
<h2>Quinto Passo:</h2>
<h3>INDEXAR OS DOCUMENTOS</h3>
Depois de ter armazenado os documentos, você usa o AI Search para extrair insights de documentos, crie <br>
automaticamente um índice e um indexador para fonte de dados suportadas.
Durante todo o processo você terá a oportunidade de aprender:
<ul>
    <li>Um serviço de pesquisa em nuvem totalmente gerenciado;</li>
    <li>Permite aos desenvolvedores criar experiências de pesquisas sofisticadas em seus aplicativos.</li>
</ul>
<ol>
    <li><b>Indexação de dados:</b> O serviço pode indexar de várias fontes, como banco de dados, <br>
    armazenamento de blob, uma pesquisa rápida e relevante.</li>
    <li><b>Enriquecimento de conteúdo:</b> Enriquecer os dados durante o processo de indexação, <br>
    incluindo extração de entidades, identificação de idiomas, análise de sentimentos e muito mais.</li>
    <li><b>Suporte a Diversos tipos de dados:</b> Lida com uma ampla variedade de tipos de dados, <br>
    incluindo texto, imagem, aúdio e video.</li>
</ol>
<hr>
O Azure Search é uma ferramenta poderosa para criar experiências de pesquisas inteligentes e <br>
personalizadas em aplicativos, aproveitando a inteligência artificial para enriquecer e oferecer <br>
resultados relevantes aos usuários.
<Explore an Azure AI Search index (UI)>








