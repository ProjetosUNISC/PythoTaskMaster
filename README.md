# 🕒 Task Master

**Task Master** é uma aplicação de gerenciamento de tarefas com foco em produtividade. Possui um timer estilo Pomodoro e permite criar, editar, concluir e visualizar tarefas. O projeto oferece uma **interface gráfica (GUI)** com `Tkinter` e também uma **interface de linha de comando (CLI)** com `curses`.

---

## ✅ Funcionalidades

- ⏱️ Cronômetro com pausa, continuar e finalizar
- 📝 Criação, edição e remoção de tarefas
- ✅ Marcar e desmarcar tarefas como concluídas
- 📊 Relatório gráfico (pizza) de tarefas resolvidas
- 💾 Armazenamento persistente em `tarefas.csv`
- 🎨 Personalização de cor das tarefas (GUI)
- 💻 Interface gráfica e linha de comando

---

## 🖥️ Interface Gráfica (Tkinter)

Para usar a interface gráfica, execute:
python gui.py



#Recursos disponíveis:
-Adicionar, editar e remover tarefas
-Escolher cores personalizadas para tarefas
-Timer com entrada personalizada (ex: 25:00)
-Geração de relatório gráfico
-Finalização com pontuação

Comandos disponíveis:
timer {minutos}
timer {minutos} + tasks {task1}, {task2}, ...
tasks
check {task1}, {task2}, ...
uncheck {task1}, {task2}, ...
remove {task1}, {task2}, ...
add {task1}, {task2}, ...
edit {task1} to {task2}
stop, pause, continue
plot
help
quit

📁 Estrutura do Projeto
.
├── cli.py             # Interface de linha de comando
├── gui.py             # Interface gráfica Tkinter
├── functions.py       # Lógica principal e persistência em CSV
└── tarefas.csv        # Gerado automaticamente (banco de dados local)

⚙️ Requisitos

Python 3.x

Dependências:
pandas
matplotlib
tkinter (nativo)

curses (em Unix/Linux/macOS; no Windows usar terminal compatível)


📝 Licença
Uso livre para fins educacionais e pessoais. 🚀



