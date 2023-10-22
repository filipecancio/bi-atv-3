# Trabalho Prático - Projeto de Criação de Dashboard

**Objetivo**: Criar um Dashboard seguindo os requisitos a seguir. O trabalho prático deverá ser entregue de acordo com o
Cronograma de Atividade.

## Requisitos
- Utilizar base de dados real preferencialmente do local de trabalho de vocês. Caso não tenham, podem utilizar uma base de dados de um dos repositórios a seguir:
  - https://www.kaggle.com/datasets
  - https://www.opendatani.gov.uk/
  - https://datasetsearch.research.google.com/
  > Informar a URL da base de dados utilizada.
- Formatar os campos no Power Query.
  > **Informar quais as formatações realizadas.**
- Criar relacionamentos entre as tabelas.
  > **Mostrar o print dos relacionamentos.**
- Criar tabela e os campos de medidas.
  > Informar as medidas criadas, por exemplo,
  > ```sql
  > Admissão = COUNTROWS(RH)
  > Salário Médio = CALCULATE(AVERAGE(RH[Salário]))
  > ```
- Criar, pelo menos uma página, com drill-through.
> Informar o nome da(s) página(s).
- Criar, pelo menos, uma página com dica de ferramenta.
> Informar o nome da(s) página(s).
- Além das páginas de drill-through e dica de ferramenta, criar três páginas, sendo uma principal. As páginas secundárias deverão ser acessadas por meio da página principal.
  - Criar, pelo menos, sete (7) componentes de visualizações distintos;
  - Criar pelo menos dois (2) componentes que não sejam do visual padrão do Power BI.
- Formatar relatório para Desktop e Mobile
- Utilizar layout com cores harmônicas nas páginas *
  > Cereja do bolo

**Características da Apresentação** : Organizar a apresentação em slides contendo explicação das etapas desenvolvidas
na criação do Dashboard com duração de 15 a 20 minutos.

**Anexar no Classroom os seguintes arquivos**:
- Base de dados utilizada
- Imagens do dashboard (background)
- Arquivo pbix
- Arquivo PDF contendo a tabela Requisitos preenchida
- Slide (PPTX e PDF)
- URL de acesso público ao Dashboard

Cronograma de Atividade:
| Data | Atividade |
|--|--|
| 23/11/2023 | Orientação |
| 30/11/2023 | Orientação |
| 07/12/2023 | Apresentação do projeto prático da III Unidade |


## Sobre o repositorio

Repositório base para template de artigo tcc em Tex baseado no modelo da SBC - Sociedade Brasileira de Computação disponidel no [site oficial](https://www.sbc.org.br/documentos-da-sbc/summary/169-templates-para-artigos-e-capitulos-de-livros/878-modelosparapublicaodeartigos). Este modelo utiliza o projeto [latex-devcontainer](https://github.com/a-nau/latex-devcontainer) para executar o projeto via [codespaces](https://github.com/features/codespaces).

## Executando o projeto local
Como pre requisito você precisará instalar na sua máquina:
- [MikTex](https://miktex.org/howto/download-miktex).
- [VsCode](https://code.visualstudio.com/)
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [latex-formatter](https://marketplace.visualstudio.com/items?itemName=nickfode.latex-formatter)
- [LaTeX](https://marketplace.visualstudio.com/items?itemName=mathematic.vscode-latex)
- [LTeX – LanguageTool grammar/spell checking](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex)
- [code runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

Após isso basta clicar no play no canto superior esquerdo no arquivo `main.tex` e gerar o .pdf (de preferência remover o pdf atual antes de gerar um novo).

## Executando o projeto no codespaces

Para o codespaces só precisa criar uma nova instância. o Container ja oferece todas as dependências instaladas. 
Após isso basta clicar no play no canto superior esquerdo no arquivo 'sbc-template.tex' e gerar o .pdf (de preferência remover o pdf atual antes de gerar um novo).

## Estrutura

O artigo consta na pasta `article`. Em `util` vemos as configurações e as referências. Na pasta `images`, colocamos os arquivos `.jpg` e `.png`. E por último em `sections` é onde é feito o artigo de fato. Os artigos possuem prefixo numérico pra facilitar a visualização em ordem nas pastas. Os arquivos Header e Abstract são obrigatórios. os demais podem ser substituídos.
