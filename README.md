# Ingestao_Indexacao
Este repositório documenta as atividades práticas realizadas no laboratório voltado à organização, ingestão e pesquisa de documentos com apoio de ferramentas de inteligência artificial. O objetivo principal foi aplicar técnicas modernas para extrair conhecimento útil a partir de grandes volumes de informação.


1. Objetivo
Aplicar técnicas de ingestão de dados, criação de índices inteligentes e exploração prática de documentos estruturados e não estruturados utilizando ferramentas baseadas em IA generativa, NLP e buscas vetoriais.

2. Etapas Realizadas
Ingestão de Conteúdo
Coletamos diferentes tipos de documentos (PDFs, textos, páginas web).

Utilizamos ferramentas como LangChain, PyMuPDF e BeautifulSoup para extrair texto bruto.

Padronizamos e estruturamos os dados extraídos em formato JSON e CSV.

Criação de Índices Inteligentes
Usamos FAISS para gerar índices vetoriais baseados em embeddings.

Empregamos OpenAI Embeddings para converter os documentos em vetores semânticos.

Organizamos os dados com metadados relevantes (título, fonte, data).

Exploração dos Dados
Integramos com LLMs (como OpenAI GPT-4) para permitir consultas em linguagem natural.

Implementamos uma interface simples de perguntas e respostas (Q&A bot).

Realizamos testes práticos para extrair insights e responder perguntas complexas com base nos documentos.


3.Insights
Durante os testes práticos, foi possível:
Automatizar a leitura e padronização de documentos diversos.
Realizar buscas por conteúdo semântico com alta precisão.
Observar a vantagem do uso de LLMs na interpretação de documentos extensos.
Gerar resumos automáticos e responder perguntas específicas com base no contexto dos arquivos indexados.

Este laboratório demonstrou, na prática, como pipelines de IA podem ser aplicados para organizar, pesquisar e extrair valor de grandes volumes de dados textuais. A combinação de embeddings vetoriais com modelos de linguagem natural se mostrou extremamente eficiente para tarefas de mineração de conhecimento.
