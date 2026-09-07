``` markdown 
# Anotações Prof. Davi

Repositório criado para atividade prática de Git e GitHub.

Integrantes do grupo:

- Nome 1: Gabriel dos Santos Silva

- Nome 2: Guilherme Mello Sant' Anna

- Nome 3: Kaíque Souza Feliciano

- Nome 4: Lucas Misael Dias

- Nome 5: Luiza Fernandes Zagatto Pinto

- Nome 6: Vinícius Gabriel Feliciano

Objetivo:

Registrar anotações e praticar versionamento com Git.

---

## 📖 Fluxo Diário de Trabalho com Git e GitHub

O fluxo diário de trabalho com o Git e o GitHub baseia-se em um ciclo contínuo de sincronização e salvamento do código. Após realizar alterações em um arquivo no seu ambiente local, o desenvolvedor utiliza o comando `git add` para preparar as modificações, aplicando em seguida um `git commit` acompanhado de uma mensagem descritiva para registrar o estado do projeto no histórico. Por fim, o comando `git push` envia essas alterações locais diretamente para o repositório remoto na nuvem, enquanto o `git pull` serve para baixar atualizações feitas por outros colaboradores, garantindo que a equipe inteira trabalhe sempre com a versão mais recente do sistema. Assim, fica mais fácil organizar o projeto, acompanhar as mudanças e trabalhar em equipe sem perder as versões anteriores do código.

---

## 🛠️ Comandos Git Estudados

*   **`git clone`**: Utilizado para clonar um repositório remoto existente no GitHub para a máquina local do desenvolvedor, configurando de forma automática a conexão com o servidor remoto.
*   **`git status`**: Exibe o estado atual da área de trabalho local (Working Directory) e da área de preparação (Staging Area), identificando arquivos modificados, deletados, não rastreados ou prontos para serem commitados.
*   **`git add`**: Prepara os arquivos modificados para o próximo commit, movendo-os do diretório local para a Staging Area.
*   **`git commit`**: Registra as alterações salvas na Staging Area no histórico local de versões, associando uma mensagem clara, concisa e descritiva ao ponto de salvamento.
*   **`git push`**: Envia os commits do repositório local do desenvolvedor para o repositório remoto hospedado no GitHub.
*   **`git pull`**: Busca as alterações mais recentes presentes no repositório do GitHub e as integra imediatamente ao branch de trabalho local, mantendo o ambiente de trabalho sincronizado com os outros desenvolvedores.

---

## 🤝 Fluxo Colaborativo de Trabalho (Diretrizes Práticas)

Com base nas atividades práticas ministradas pelo Prof. Davi (Atividades Básico e Avançado), o grupo adota as seguintes práticas e dinâmicas de entrega:

### 1. Dinâmica de Repositório em Equipe (Nível Básico)
*   **Colaboração Inicial**: Um integrante do grupo inicializa o repositório e adiciona os demais como colaboradores formais através das configurações de acesso do GitHub (*Settings → Collaborators*).
*   **Trabalho Individual**: Cada membro deve clonar o repositório em sua máquina local utilizando o `git clone`.
*   **Frequência de Commits**: Cada participante é responsável por realizar pelo menos **2 commits próprios**, gerando mensagens claras e detalhadas do que foi alterado.
*   **Regra de Histórico**: O projeto deve totalizar no mínimo **6 commits no histórico final**, evidenciando o trabalho distribuído de todos os membros.
*   **Identidade e Autoria**: É obrigatório que cada membro utilize a sua própria conta do GitHub para commitar. Commits executados por uma pessoa em nome de outra ou de forma anônima comprometem a avaliação de contribuição individual.

### 2. Fluxo de Trabalho de Equipe Real (Nível Avançado)
*   **Uso de Branches Individuais**: É proibido commitar diretamente no branch `main`. Cada integrante cria e desenvolve em uma ramificação individual a partir do `main`, utilizando o padrão de nomenclatura:
    `feature/nome-da-pessoa`
*   **Abertura de Pull Requests (PR)**: Após concluir pelo menos 1 alteração e commit dentro do seu branch, o desenvolvedor envia a ramificação ao GitHub com `git push` e solicita a integração ao branch `main` por meio de um *Pull Request*.
*   **Revisão Cruzada (Code Review)**: Todo Pull Request precisa obrigatoriamente ser avaliado, comentado e aprovado por outro integrante da equipe na aba de discussões do GitHub antes de sofrer a mesclagem (*merge*). O autor do PR não pode revisar nem aprovar o próprio código.
*   **Resolução de Conflitos**: Para exercitar situações comuns do mercado, o grupo simula e resolve intencionalmente conflitos de merge (como a edição simultânea da mesma linha de um arquivo por branches diferentes), registrando no histórico como a resolução foi realizada.
*   **Gestão de Issues**: O repositório deve conter no mínimo **2 Issues abertas**, listando e detalhando com clareza melhorias futuras propostas para o sistema ou correções identificadas.
*   **Gerenciamento de Releases (Tags)**: Uma vez que todos os Pull Requests tenham sido devidamente testados, aprovados e mesclados ao `main`, cria-se uma tag de versão `v1.0` no commit final do histórico, publicando-a no GitHub.
*   **Higienização de Branches**: Após o término do fluxo de integração e entrega da versão estável, todos os branches de trabalho remoto e local que já foram integrados devem ser excluídos para manter o repositório limpo e organizado.
## Contribuição da Luiza

Alteração realizada para a atividade de Design Profissional — Nível Avançado.