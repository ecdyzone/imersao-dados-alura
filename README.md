

# O que?

Este repositório contém os notebooks desenvolvidos na imersão dados 2021 da Alura.

- [Github da Alura com aulas, desafios e dados utilizados](https://github.com/alura-cursos/imersaodados3)
- [Desafio Final](https://github.com/alura-cursos/imersao-dados-desafio-final)
- Origem dos dados e inspiração: *Mechanisms of Action (MoA) Prediction* no [Kaggle](https://www.kaggle.com/c/lish-moa)

# Porque?

Notei que os comentários da aula se perdiam. Por exemplo, o arquivo da aula 4 contém os comentários apenas da aula 4 e não das outras aulas. Mas os comentários da aula 4 não estão presentes no notebook da aula 5.

Eu queria um arquivo unificado com todas as aulas comentadas, então criei dois arquivos pra facilitar minha vida e de quem mais quiser:

- [Um arquivo](https://github.com/mumaral/imersao-dados-alura/blob/main/Imersao-Tudo_Desafios-Nao-Resolvidos.ipynb) com todas as aulas comentadas + desafios não resolvidos

- [Outro arquivo](https://github.com/mumaral/imersao-dados-alura/blob/main/Imersao-Tudo_Desafios-Resolvidos.ipynb) com todas as aulas comentadas + desafios resolvidos (resoluções da alura, não minhas)

  

(Os arquivos ficaram grandinhos, mas o índice tá bem organizado então fica fácil se encontrar)

# Abrindo no Google Collab

> Link do github para o arquivo com desafios NÃO resolvidos: https://github.com/mumaral/imersao-dados-alura/blob/main/Imersao-Tudo_Desafios-Nao-Resolvidos.ipynb
>
> Link do github para o arquivo com desafios resolvidos: https://github.com/mumaral/imersao-dados-alura/blob/main/Imersao-Tudo_Desafios-Resolvidos.ipynb
>
> (Ao clicar nestes links, pode ser que o github não carregue de primeira a visualização do arquivo devido ao tamanho, mas é só clicar no “Reload” que funciona)

Para abrir no [Google Collab](https://colab.research.google.com/), a forma mais fácil é:

1. No canto superior esquerdo do google collab clique na sequência: File > Open Notebook > Github
2. Cole o link do github e clique na lupa
3. Vai aparecer o símbolo do github com um link abaixo, clique neste link para abrir o notebook
4. IMPORTANTE: No canto superior esquerdo clique em "Copy to Drive", para criar uma cópia na sua do google direto do meu github. Se não fizer isso, você não conseguirá salvar nenhuma alteração que fizer

Outra opção seria:

1. Abrir o link do arquivo desejado (links acima)
2. Clicar em download, no lado direito da tela
3. No canto superior esquerdo do google collab clique na sequência: File > Open Notebook > Upload
4. Arraste o arquivo baixado pra lá

# Como unificar notebooks

Na pasta *Arquivos-Originais-Separados* cada aula está fragmentada em 3:

- Aula X comentada
- Desafios Não-Resolvidos da Aula X (apenas enunciados)
- Desafios Resolvidos da Aula X

Para unificar os notebooks, use `nbmerge` (a documentação está disponível [aqui](https://nbdime.readthedocs.io/en/latest/cli.html)):

```bash
pip install nbmerge
```

```bash
nbmerge file_1.ipynb file_2.ipynb file_3.ipynb > merged.ipynb
```


