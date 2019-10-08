# Documentação da FastAI em Português

> **NOTA:** *Esta documentação é independente e não possui vínculo com a FastAI. Não há garantias que ela estará disponível na [página oficial da documentação](https://docs.fast.ai) (apesar de que eventualmente um pull request pode ser feito se boa parte do material for traduzido). Também não há garantias de que a documentação traduzida estará 100% atualizada com a versão em inglês.*

Este projeto foi iniciado com o intuito de revisar o material do curso e possibilitar com que a FastAI alcance um número maior de pessoas. Praticamente a documentação inteira foi criada utilizando cadernos do jupyter (arquivos .ipynb). Há também arquivos em markdown, no entanto são minoria. Todos os cadernos estão disponívels em [/fastai/docs_src](https://github.com/fastai/fastai/tree/master/docs_src). Já os markdown estão em [/fastai/docs](https://github.com/fastai/fastai/tree/master/docs). Por exemplo, a página inicial está [aqui](https://github.com/fastai/fastai/blob/master/docs_src/index.ipynb).

Estarei compartilhando aqui o progresso neste projeto. Você é bem vindo para ajudar! Todos os cadernos já foram pré-traduzidos a partir de um [script](https://github.com/WittmannF/jupyter-translate) que fez uso de um API do Google Translate (e também alguns artifícios para que blocos especials de markdown não fossem "traduzidos"). No entanto ainda é necessário uma leitura de cada caderno e correção em comparação com os arquivos originais. Os arquivos pré-traduzidos estão em um branch de um fork da fastai chamado 'doc-portuguese'. Seguem os links:

- Cadernos do Jupyter pré-traduzidos: https://github.com/WittmannF/fastai/tree/docs-portuguese/docs_src/pt-br
- Arquivos em markdown pré-traduzidos: https://github.com/WittmannF/fastai/tree/docs-portuguese/docs/pt-br

Para contribuir, basta baixar o caderno que tenha interesse em revisar a tradução e depois me enviar (`fernando . wittmann @ gmail . com`) para que eu adicione ao branch. Você pode abrir o caderno diretamente utilizando o Google Colab (confira as intruções abaixo). Você também pode mandar um pull request diretamente ao branch caso saiba fazer isso. 

## Arquivos revisados até o momento
- [index.ipynb](https://github.com/WittmannF/fastai/blob/docs-portuguese/docs_src/pt-br/index.ipynb)

## Revisões em andamento
- 

## Como abrir os arquivos .ipynb no Google Colab
Você pode abrir arquivos do Github diretamente no Google Colab utilizando os seguinte template:
- `https://colab.research.google.com/github/` + {caminho do repositório}

Portanto basta acrescentar à url anterior o caminho que vem após `https://github.com/`. Por exemplo, para abrir o arquivo https://github.com/WittmannF/fastai/blob/docs-portuguese/docs_src/pt-br/tutorial.data.ipynb basta remover o `https://github.com/` e juntar com `https://colab.research.google.com/github/`. Ficaria da seguinte forma:
- https://colab.research.google.com/github/WittmannF/fastai/blob/docs-portuguese/docs_src/pt-br/tutorial.data.ipynb

Alternativamente você pode ir em https://colab.research.google.com, clicar em Github e colocar a URL do repositório. 

**!IMPORTANTE:** As alterações não serão salvas de arquivos abertos diretamente do Github. Você deve ou clicar em "Copy to Drive" ou menu 'File > Save a copy in GitHub'. Recomendo a segunda opção pois haverá a opção 'Include a link to Colaboratory' no qual incluirá um link para abrir no jupyter um link para abrir o arquivo diretamente no Google Colab. 
