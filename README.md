# Breve descrição:
Este é um indexador de páginas da Wikipedia em português desenvolvido em Python sobre perspectiva orientada à objeto. Seu objetivo é identificar as palavras e as páginas encontradas e criar uma base NoSQL com a indexação das palavras por arquivo, levando em consideração o número de ocorrências de cada. A amostra da wikipedia contém 61.127 em HTML. Nesse caso, não ocorre coleta propriamente dita pois a amostra já está disponível.

O projeto possui 2 principais arquivos: `indexer.py` e `structure.py`. Cada método desenvolvido foi submetido a testes disponíveis em `file_index_test.py`, `index_structure_test.py`, `indexer_test.py` e `performance_test.py`. Todos os arquivos citados até o momento encontram-se na pasta `./index`. Além disso, para melhor apurar os testes e resultados, existem os arquivos jupyter `TP2 - Dojo - Indice.ipynb` e `relatorio.ipynb`.

Cabe ressaltar que os termos obtidos no acervo da Wikipedia, passam por filtros. Não são indexadas palavras definidas no arquivo stopwords.txt. Acentos, pontuações, elementos textuais, marcações de HTML são ignorados. Sobram apenas palavras. Essas por sua vez, elementos como particípio e gerúndio removidos.

## Participantes:
- [ANTONIO PIERRE MARTINS VIEIRA](https://github.com/PierreVieira) - pierrevieiraggg@gmail.com
- [CRISTHIAN SALA MINOVES](https://github.com/CMinoves) - cminoves26@gmail.com
- [THIAGO FERNANDES DORNELLES](https://github.com/thiagodff) - thiago.fdornelles@gmail.com
- [VINICIUS NASCIMENTO SILVA](https://github.com/vnszero) - vnszero@gmail.com

## Sobre orientação do professor:
- DANIEL HASAN

# Objetivo:
> O propósito do é organizar as ocorrências dos termos em arquivos .idx.