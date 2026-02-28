╔═══════════════════════════════════════════════════════════════════════════════════╗
║                     CORE LANGUAGE - DOCUMENTAÇÃO COMPLETA                        ║
║                         TODOS OS COMANDOS E FUNÇÕES                              ║
╚═══════════════════════════════════════════════════════════════════════════════════╝


┌─────────────────────────────────────────────────────────────────────────────────┐
│                              1. COMANDOS BÁSICOS                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ system import cmd        │ Inicia o sistema de comandos                          │
│ system import random     │ Carrega funções aleatórias                            │
│ system import math       │ Carrega funções matemáticas                           │
│ system import coregame   │ Modo gráfico com pygame                               │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             2. MOSTRAR MENSAGENS                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ most string "texto"                    │ Mostra texto normal branco             │
│ most color-azul "texto"                 │ Mostra texto em azul                   │
│ most color-verde "texto"                │ Mostra texto em verde                  │
│ most color-vermelho "texto"              │ Mostra texto em vermelho               │
│ most color-amarelo "texto"               │ Mostra texto em amarelo                │
│ most color-roxo "texto"                  │ Mostra texto em roxo                   │
│ most color-rosa "texto"                  │ Mostra texto em rosa                   │
│ most color-ciano "texto"                 │ Mostra texto em ciano                  │
│ most color-laranja "texto"                │ Mostra texto em laranja                │
│ most color-branco "texto"                 │ Mostra texto em branco                 │
│ most color-preto "texto"                  │ Mostra texto em preto                  │
│ most color-cinza "texto"                  │ Mostra texto em cinza                  │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             3. PERGUNTAS E RESPOSTAS                             │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ ask string "pergunta"                    │ Faz pergunta, guarda em 'resposta'   │
│ ask string+anycalc "pergunta"             │ Pergunta e guarda no anycalc         │
│ resposta                                  │ Variável com última resposta         │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                                  4. VARIÁVEIS                                     │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ crt global variable = name "variavel"     │ Cria uma variável global             │
│ storage "valor"                           │ Armazena valor na última variável    │
│ set nome = "João"                         │ Define valor direto (texto)          │
│ set idade = 25                             │ Define valor direto (número)         │
│ set nome = resposta                        │ Define valor com resposta            │
│ mostrar nome                               │ Mostra valor de uma variável         │
│ mostrar variaveis                          │ Mostra todas as variáveis criadas    │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                            5. PONTOS E INVENTÁRIO                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ pontos +10                              │ Adiciona pontos                        │
│ pontos -5                               │ Remove pontos                          │
│ mostrar pontos                           │ Mostra total de pontos                 │
│ add inventario "espada"                  │ Adiciona item ao inventário            │
│ remover inventario "poção"               │ Remove item do inventário              │
│ mostrar inventario                        │ Mostra todos os itens do inventário   │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                          6. OPERAÇÕES MATEMÁTICAS                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ calc soma = 5 + 3                       │ Adição                                 │
│ calc sub = 10 - 4                       │ Subtração                              │
│ calc multi = 6 * 7                      │ Multiplicação                          │
│ calc div = 15 / 3                       │ Divisão                                │
│ calc resto = 10 % 3                     │ Resto da divisão                       │
│ calc potencia = 2 ** 3                  │ Potência                               │
│ calc media = (5 + 7 + 9) / 3            │ Expressões complexas                   │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                            7. NÚMEROS ALEATÓRIOS                                  │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ random numero = 1 10                    │ Número aleatório entre 1 e 10         │
│ random dado = 1 6                        │ Dado de 6 lados                       │
│ random dano = 5 20                       │ Dano aleatório entre 5 e 20           │
│ random moedas = 10 50                    │ Moedas aleatórias                     │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                                  8. LISTAS                                        │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ criar lista frutas                       │ Cria uma lista vazia                  │
│ adicionar lista frutas "maçã"            │ Adiciona item à lista                 │
│ remover lista frutas "banana"            │ Remove item da lista                  │
│ mostrar lista frutas                      │ Mostra todos os itens da lista        │
│ tamanho lista frutas                      │ Mostra quantidade de itens            │
│ item lista frutas 0                       │ Mostra item no índice 0               │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                          9. CRIAÇÃO DE APPS (MODO GRÁFICO)                       │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ app button "OK" cor="verde"              │ Cria um botão                         │
│ app button "Sair" cor="vermelho" x=100 y=50 │ Botão com posição específica       │
│ app label "Título" cor="azul" tamanho=16 │ Cria um texto                         │
│ app entry "usuario" placeholder="Nome"   │ Campo de entrada de texto             │
│ app frame "principal" largura=400 altura=300 │ Cria um frame                     │
│ app checkbox "Aceito termos"             │ Cria uma checkbox                     │
│ app radio "Masculino" grupo="sexo"       │ Cria radio button                     │
│ app listbox "cores"                      │ Cria uma lista de seleção             │
│                                                                                   │
│ # Parâmetros de posicionamento:                                                  │
│ x=10                                      │ Posição horizontal                   │
│ y=20                                      │ Posição vertical                     │
│ tamanho=14                                │ Tamanho da fonte                     │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                        10. CORES PARA APPS (MODO GRÁFICO)                        │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ cor="verde"          │ #2ecc71          │ Botão/Label verde                      │
│ cor="azul"           │ #3498db          │ Botão/Label azul                       │
│ cor="vermelho"       │ #e74c3c          │ Botão/Label vermelho                   │
│ cor="amarelo"        │ #f1c40f          │ Botão/Label amarelo                    │
│ cor="roxo"           │ #9b59b6          │ Botão/Label roxo                       │
│ cor="rosa"           │ #e83e8c          │ Botão/Label rosa                       │
│ cor="laranja"        │ #e67e22          │ Botão/Label laranja                    │
│ cor="cinza"          │ #95a5a6          │ Botão/Label cinza                      │
│ cor="preto"          │ #2c3e50          │ Botão/Label preto                      │
│ cor="branco"         │ #ffffff          │ Botão/Label branco                     │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                          11. JOGOS (MODO COREGAME)                               │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ system import coregame                   │ Ativa modo gráfico de jogos           │
│ crt global variable = name "tela"        │ Cria a tela do jogo                   │
│ storage "screen size 800x600"            │ Define tamanho da tela                │
│ most corecolor-verde allpaint            │ Pinta a tela inteira de verde         │
│ most corecolor-azul allpaint             │ Pinta a tela de azul                  │
│ crt global variable - name "player"      │ Cria um sprite (jogador)              │
│ storage "sprite-color vermelho"          │ Define cor do sprite                  │
│ sprite + keybind front "w" back "s" right "d" left "a" │ Controles WASD         │
│ sprite + velocity "10"                   │ Define velocidade do sprite           │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                          12. ESTRUTURAS DE CONTROLE                              │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ # Condicional IF/ELSE                                                            │
│ if resposta == "1"                                                                │
│     most color-verde "Você escolheu 1!"                                           │
│     pontos +10                                                                     │
│ else                                                                               │
│     most color-vermelho "Opção inválida!"                                          │
│ end                                                                                │
│                                                                                   │
│ # Operadores de comparação                                                        │
│ if idade == 18       │ Igual a                                                   │
│ if nome != "admin"    │ Diferente de                                             │
│ if pontos > 100       │ Maior que                                                │
│ if vida < 0           │ Menor que                                                │
│ if idade >= 18        │ Maior ou igual                                           │
│ if nivel <= 5         │ Menor ou igual                                           │
│                                                                                   │
│ # Loop WHILE                                                                      │
│ while vida > 0                                                                     │
│     most string "Ainda vivo!"                                                      │
│     vida -10                                                                       │
│ end                                                                                │
│                                                                                   │
│ # Loop REPEAT                                                                     │
│ repeat 5                                                                           │
│     most string "Olá mundo!"                                                       │
│ end                                                                                │
│                                                                                   │
│ # Comando BREAK                                                                   │
│ break                               │ Sai do loop atual                         │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             13. TEMPO E DATA                                      │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ wait 2 segundos                         │ Pausa a execução por 2 segundos       │
│ mostrar data                             │ Mostra a data atual (dd/mm/aaaa)      │
│ mostrar hora                             │ Mostra a hora atual (hh:mm:ss)        │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                          14. ANYCALC (MEMÓRIA INTELIGENTE)                       │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ ask string+anycalc "Qual seu nome?"      │ Pergunta e guarda resposta no anycalc │
│ mostrar anycalc                           │ Mostra todos os valores no anycalc   │
│ anycalc                                   │ Variável que guarda último valor     │
│                                                                                   │
│ # Exemplo completo:                                                              │
│ ask string+anycalc "Qual seu nome?"                                               │
│ most color-azul "Bem vindo anycalc!"                                              │
│ most string "anycalc, vamos jogar?"                                               │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                          15. ARQUIVOS E PROJETOS                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ Ctrl+N              │ Novo projeto (limpa o editor)                             │
│ Ctrl+O              │ Abrir projeto (.core)                                     │
│ Ctrl+S              │ Salvar projeto atual                                      │
│ Salvar Como         │ Salvar com novo nome                                      │
│ Exportar .pyw       │ Gera executável sem console                               │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             16. EXEMPLO COMPLETO - APP                           │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ system import cmd                                                                 │
│                                                                                   │
│ app label "SISTEMA DE LOGIN" cor="azul" tamanho=20 x=50 y=30                     │
│                                                                                   │
│ app label "Usuário:" cor="preto" x=50 y=100                                      │
│ app entry "usuario" placeholder="Digite seu usuário" x=150 y=100                 │
│                                                                                   │
│ app label "Senha:" cor="preto" x=50 y=150                                        │
│ app entry "senha" placeholder="********" x=150 y=150                             │
│                                                                                   │
│ app button "Entrar" cor="verde" x=50 y=200                                       │
│ app button "Cancelar" cor="vermelho" x=150 y=200                                 │
│                                                                                   │
│ app label "Esqueceu a senha?" cor="azul" x=50 y=250                              │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             17. EXEMPLO COMPLETO - RPG                           │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ system import cmd                                                                 │
│ system import random                                                              │
│                                                                                   │
│ ask string "Qual seu nome, herói?"                                                │
│ crt global variable = name "heroi"                                                │
│ storage anycalc                                                                   │
│ most color-verde "Bem vindo, anycalc!"                                            │
│                                                                                   │
│ set vida = 100                                                                     │
│ set moedas = 50                                                                    │
│ add inventario "poção"                                                            │
│                                                                                   │
│ while vida > 0                                                                     │
│     most string "Vida: " + vida                                                   │
│     most string "Moedas: " + moedas                                               │
│     most string "1- Explorar"                                                     │
│     most string "2- Loja"                                                         │
│     most string "3- Sair"                                                         │
│     ask string "Escolha:"                                                          │
│                                                                                   │
│     if resposta == "1"                                                             │
│         random evento = 1 3                                                        │
│         if evento == 1                                                             │
│             most color-vermelho "Um monstro apareceu!"                            │
│             random dano = 10 20                                                    │
│             vida - dano                                                            │
│             most color-vermelho "Perdeu " + dano + " de vida"                     │
│         else                                                                       │
│             most color-verde "Você encontrou um tesouro!"                         │
│             random ouro = 10 30                                                    │
│             moedas + ouro                                                          │
│             add inventario "tesouro"                                              │
│         end                                                                        │
│     end                                                                            │
│                                                                                   │
│     if resposta == "2"                                                             │
│         most color-azul "LOJA: Poção - 20 moedas"                                 │
│         ask string "Comprar? (sim/nao)"                                            │
│         if resposta == "sim" and moedas >= 20                                      │
│             moedas -20                                                             │
│             add inventario "poção"                                                │
│             most color-verde "Poção comprada!"                                    │
│         end                                                                        │
│     end                                                                            │
│                                                                                   │
│     if resposta == "3"                                                             │
│         most color-amarelo "Até logo!"                                            │
│         break                                                                      │
│     end                                                                            │
│ end                                                                                │
│                                                                                   │
│ mostrar inventario                                                                 │
│ mostrar pontos                                                                     │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             18. EXEMPLO - CALCULADORA                            │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ system import math                                                                │
│                                                                                   │
│ most color-azul "╔ CALCULADORA ╗"                                                │
│ ask string "Primeiro número:"                                                     │
│ set n1 = resposta                                                                 │
│ ask string "Segundo número:"                                                      │
│ set n2 = resposta                                                                 │
│                                                                                   │
│ calc soma = n1 + n2                                                               │
│ calc sub = n1 - n2                                                               │
│ calc multi = n1 * n2                                                             │
│ calc div = n1 / n2                                                               │
│ calc resto = n1 % n2                                                             │
│                                                                                   │
│ most color-verde "Resultados:"                                                   │
│ most string "Soma: " + soma                                                       │
│ most string "Subtração: " + sub                                                   │
│ most string "Multiplicação: " + multi                                             │
│ most string "Divisão: " + div                                                     │
│ most string "Resto: " + resto                                                     │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             19. EXEMPLO - LISTA DE TAREFAS                       │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ criar lista tarefas                                                               │
│                                                                                   │
│ while true                                                                        │
│     most color-azul "╔ LISTA DE TAREFAS ╗"                                       │
│     most string "1- Adicionar tarefa"                                            │
│     most string "2- Listar tarefas"                                              │
│     most string "3- Remover tarefa"                                              │
│     most string "4- Sair"                                                        │
│     ask string "Opção:"                                                           │
│                                                                                   │
│     if resposta == "1"                                                             │
│         ask string "Digite a tarefa:"                                             │
│         adicionar lista tarefas resposta                                          │
│         most color-verde "Tarefa adicionada!"                                    │
│     end                                                                            │
│                                                                                   │
│     if resposta == "2"                                                             │
│         mostrar lista tarefas                                                     │
│     end                                                                            │
│                                                                                   │
│     if resposta == "3"                                                             │
│         mostrar lista tarefas                                                     │
│         ask string "Qual tarefa remover?"                                         │
│         remover lista tarefas resposta                                            │
│         most color-vermelho "Tarefa removida!"                                   │
│     end                                                                            │
│                                                                                   │
│     if resposta == "4"                                                             │
│         most color-amarelo "Saindo..."                                           │
│         break                                                                      │
│     end                                                                            │
│ end                                                                                │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


┌─────────────────────────────────────────────────────────────────────────────────┐
│                             20. ATALHOS DO TECLADO                               │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│ F5                 │ Executar o código atual                                    │
│ F6                 │ Executar o último app exportado                           │
│ F7                 │ Limpar o console                                           │
│ Ctrl+N             │ Novo projeto                                               │
│ Ctrl+O             │ Abrir projeto                                              │
│ Ctrl+S             │ Salvar projeto                                             │
│ Ctrl+F             │ Buscar texto                                               │
│ Ctrl+H             │ Substituir texto                                           │
│ TAB                │ Inserir 4 espaços (indentação)                            │
│                                                                                   │
└─────────────────────────────────────────────────────────────────────────────────┘


╔═══════════════════════════════════════════════════════════════════════════════════╗
║                     CORE LANGUAGE - VERSÃO 4.0                                   ║
║                Desenvolvida para ser simples, divertida e poderosa!              ║
║                                                                                   ║
║                🎮 Crie jogos │ 🎨 Faça apps │ 📊 Programas utilitários           ║
╚═══════════════════════════════════════════════════════════════════════════════════╝
