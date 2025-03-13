Arquivo: adicionando-item-na-pasta-de-estudos.md

# Como Adicionar um Item na Pasta de Estudos

Neste estudo, vamos aprender como adicionar um novo item (arquivo de estudo) dentro da pasta `materiais-de-apoio` do repositório. O processo envolve criar o arquivo de estudo, adicionar conteúdo e fazer o commit das mudanças no GitHub.

## 1. Criando o Arquivo de Estudo

Primeiro, navegue até o diretório onde estão os arquivos de estudo:

```bash
cd ~/Git-Hub/dio-curso-git-github/materiais-de-apoio
Agora, crie um novo arquivo Markdown para o seu estudo. O Markdown é um formato simples de texto que pode ser usado para formatação de conteúdo, como títulos, listas e links. Use o comando touchpara criar um arquivo novo:

Editar
touch 05-nome-do-estudo.md
Substitua nome-do-estudopelo título que desejar para o seu estudo. O formato do arquivo será .md.

2. Adicionando Conteúdo ao Arquivo
Abra o arquivo que você acabou de criar com seu editor de código preferido, como o Visual Studio Code ou Nano :

code 05-nome-do-estudo.md
Agora, insira o conteúdo do estudo no arquivo Markdown. Por exemplo:

redução de preço

# Título do Estudo

## 1. Introdução
Aqui você pode escrever uma breve introdução sobre o assunto.

## 2. Detalhamento
Escreva o conteúdo do seu estudo, detalhando pontos importantes.

## 3. Exemplos
Se necessário, adicione exemplos relacionados ao estudo.

## 4. Conclusão
Faça uma conclusão resumida sobre o estudo.
Após inserir o conteúdo, salve o arquivo.

3. Adicionando o Arquivo ao Repositório
Agora que o arquivo foi criado e editado, você precisa adicionar ele ao repositório para versioná-lo com o Git.

No terminal, execute os seguintes comandos:

git add materiais-de-apoio/05-nome-do-estudo.md
Esse comando adiciona o arquivo para o próximo commit.

4. Realizando o Commit
Agora que o arquivo foi adicionado, vamos fazer o commit para registrar as alterações. Escreva uma mensagem explicativa do commit:

git commit -m "Adiciona estudo sobre [Assunto] na pasta de apoio"
Substitua [Assunto]pelo título do seu estudo.

5. Enviando para o GitHub (Push)
Por fim, envie as mudanças para o repositório no GitHub:

git push origin main
Agora, o arquivo não estará no repositório remoto e qualquer colaborador poderá acessar o estudo na pasta de apoio.

6. Conclusão
Adicionamos com sucesso um novo item na pasta materiais-de-apoiodo repositório. Esse processo é útil para compartilhar novos conteúdos e estudos com a equipe ou para contribuir com o repositório.
```
