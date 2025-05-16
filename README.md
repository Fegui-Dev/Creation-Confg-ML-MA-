# ☁️ Criando sua Primeira Máquina Virtual no Microsoft Azure

E aí! 👋 Seja bem-vindo a esse mini-guia prático de como **criar e configurar uma Máquina Virtual (VM)** no **Microsoft Azure**. Aqui a ideia é deixar tudo bem direto, resumido e fácil de acompanhar. Bora meter a mão na nuvem? 🚀

---

## 📌 Parte 1: Antes de tudo... o que é Azure?

Azure é tipo um **super computador online**. Com ele você pode criar servidores, armazenar arquivos, rodar apps, e claro, criar máquinas virtuais que funcionam como se fossem computadores reais rodando na nuvem.

Se ainda não tem conta no Azure, você pode criar uma [aqui](https://azure.microsoft.com/) (dica: eles dão crédito gratuito pra começar 💸, e tem plano de estudante gratuito sem add CC).

---

## 🛠️ Parte 2: Criando a Máquina Virtual

Beleza, agora vamos criar nossa VM:

1. Acesse o [Portal do Azure](https://portal.azure.com).
2. No menu lateral, clique em **"Máquinas Virtuais"**.
3. Clique em **"Criar" > "Máquina Virtual"**.
4. Preencha os dados:
   - **Grupo de Recursos**: crie um ou use um já existente.
   - **Nome da VM**: tipo `minha-vm-teste`.
   - **Região**: escolha uma próxima de você (tipo `Brazil South`).
   - **Imagem**: escolha o sistema operacional (tipo Windows ou Ubuntu).
   - **Tamanho**: pode ser algo como `B1s` (baratinha).
   - **Usuário e senha** para login.

---

## 🔐 Parte 3: Configurando Acesso

Agora bora liberar o acesso:

- Vá na aba **"Regras de Porta de Entrada"** e marque **RDP (para Windows)** ou **SSH (para Linux)**.
- Isso vai permitir que você se conecte à máquina depois.

---

## 🚀 Parte 4: Criou? Agora conecta!

Depois que a VM estiver criada:

- Se for Windows, use o **Remote Desktop Connection (RDP)**.
- Se for Linux, use o **terminal com SSH** (tipo `ssh usuario@ip-da-vm`).

Dica: dá pra ver o IP da sua VM lá na tela de detalhes dela no portal Azure.

---

## 🧼 Parte 5: Lembre-se de parar ou excluir!

Se for só pra testar, **não esquece de parar ou excluir a VM** depois, senão ela continua rodando e... sim, você pode ser cobrado 💰.

---

## 🤝 Curtiu? Então bora aprender mais!

Esse repositório é só o começo! Se quiser, dá um fork, abre issues ou sugestões. Vamos explorar o mundo da nuvem juntos! ☁️💻

---

Feito com café ☕ e vontade de aprender 💡
