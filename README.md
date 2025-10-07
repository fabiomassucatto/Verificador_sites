# 🕵️‍♂️ Monitorador de Sites em Go

Um simples e eficiente **monitorador de sites** desenvolvido em **Go (Golang)**.  
O programa verifica periodicamente se os sites estão online e registra o resultado em um arquivo de log.

---

## 🚀 Funcionalidades

- ✅ Lê uma lista de sites a partir do arquivo `sites.txt`
- 🔄 Realiza múltiplos ciclos de monitoramento
- 🧾 Registra logs com data, hora e status de cada site
- 📖 Exibe o histórico de logs diretamente no terminal
- 💻 Interface simples e intuitiva via linha de comando

---

## 📂 Estrutura do Projeto

monitorador/
├── main.go # Código principal do programa
├── sites.txt # Lista de sites a serem monitorados
├── logs.txt # Gerado automaticamente com os registros de monitoramento
└── README.md # Documentação do projeto


---

## ⚙️ Como Usar

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/seu-usuario/monitorador-sites-go.git
cd monitorador-sites-go

2️⃣ Criar o arquivo sites.txt

Adicione um site por linha, por exemplo:
https://www.google.com
https://www.alura.com.br
https://www.caelum.com.br

3️⃣ Executar o programa

go run main.go


4️⃣ Menu de opções

1 → Iniciar monitoramento

2 → Exibir logs

0 → Sair do programa

🧠 Como Funciona

O programa:

Lê os sites do arquivo sites.txt

Realiza 3 ciclos de monitoramento

Aguarda 3 segundos entre os ciclos

Registra o resultado no arquivo logs.txt com data, hora e status





