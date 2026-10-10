<div align="center">

<img src="assets/banner-horizontal.png" alt="Caça-Cliente — Sites com IA do Zero" width="100%" />

# 🎯 Caça-Cliente

### O radar de negócios sem site — do clique ao WhatsApp.

*A ferramenta oficial do curso **Sites com IA do Zero** — encontre negócios **sem site** na sua cidade e feche seu primeiro cliente.*

[![Versão](https://img.shields.io/github/v/release/d1g4odev/caca-cliente-downloads?sort=semver&filter=v*&label=vers%C3%A3o&color=6f42c1)](https://github.com/d1g4odev/caca-cliente-downloads/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white)](#-windows)
[![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white)](#-mac)
[![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)](#-linux)
[![Custo](https://img.shields.io/badge/custo-R%24%200-2ea44f)](#-quanto-custa)

</div>

> 🔒 **Exclusivo para alunos do curso Sites com IA do Zero.** Aqui ficam só os instaladores do app. Não é permitido redistribuir, revender ou publicar os arquivos em outro lugar — veja a [licença](./LICENSE).

---

## 👋 O que é isso?

Você aprendeu a criar sites com IA. Agora precisa de **clientes** pra vender esses sites. E quem mais precisa de um site? **Os negócios que ainda não têm um.**

Achar esses negócios na mão é lento: abrir o Google, digitar "barbearia em [sua cidade]", clicar em cada um, ver se tem site, anotar o telefone… O **Caça-Cliente** faz isso pra você, **de graça**, em segundos:

1. Você digita o **nicho** (ex.: _barbearia_) e a **cidade**.
2. A ferramenta varre o **OpenStreetMap** (o "Google Maps" gratuito) e acha os estabelecimentos daquele ramo na região.
3. Quando o mapa acha pouca coisa, ela **completa com a base oficial da Receita Federal** (empresas com CNPJ ativo), com telefone e e-mail cadastrados.
4. Ela **descarta** quem já tem site — sobram só os que precisam de um.
5. Para cada lead, ainda **procura sozinha** e-mail, Instagram, Facebook e LinkedIn na internet.
6. Você abre o WhatsApp com a mensagem já pronta, manda, e fecha o cliente.

---

## ⬇️ Baixar o app

### 👉 **[Baixar a versão mais nova](https://github.com/d1g4odev/caca-cliente-downloads/releases/latest)**

Na página que abrir, desça até **Assets** e baixe o arquivo do seu sistema:

| Seu sistema | Arquivo para baixar |
|---|---|
| 🪟 **Windows** | `CacaCliente-X.Y.Z-win-x64.exe` |
| 🍎 **Mac Apple Silicon** (M1, M2, M3, M4) | `CacaCliente-X.Y.Z-mac-arm64.dmg` |
| 🍎 **Mac Intel** | `CacaCliente-X.Y.Z-mac-x64.dmg` |
| 🐧 **Linux** | `CacaCliente-X.Y.Z-linux-x86_64.AppImage` |

> 💡 **Não sabe qual Mac você tem?** Menu 🍎 (canto superior esquerdo) → **Sobre Este Mac**. Se aparecer "Apple M1/M2/M3/M4", baixe o `arm64`. Se aparecer "Intel", baixe o `x64`.

🔹 **~100–130 MB** — tamanho normal de app desktop (já vem com o navegador embutido).\
🔹 **Sem terminal, sem configuração** — instala e usa.\
🔹 **Seus leads ficam salvos** no seu computador — feche e abra de novo que nada se perde.

---

## 🛠️ Instalar

### 🪟 Windows

1. Dê **dois cliques** no arquivo `.exe`.
2. ⚠️ Se aparecer a tela azul **"Windows protegeu o seu PC"** (SmartScreen), é normal: o app é novo e não tem um certificado pago. Clique em **"Mais informações"** → **"Executar assim mesmo"**.
3. No instalador: **Avançar** → **Avançar** → **Instalar** → **Concluir**.
4. O app aparece no **Menu Iniciar** e na **Área de Trabalho**. Pronto!

> 🚫 **Não precisa "abrir como administrador".** O instalador é por usuário e não pede permissão de admin.
>
> 🛡️ **Dois cliques e nada acontece?** O antivírus pode ter colocado o arquivo em quarentena. Abra **Segurança do Windows** → **Proteção contra vírus e ameaças** → **Histórico de proteção**, procure o Caça-Cliente e clique em **Permitir**.

### 🍎 Mac

1. Dê **dois cliques** no arquivo `.dmg`.
2. **Arraste o ícone do Caça-Cliente pra pasta Applications** (Aplicativos).
3. Abra o **Finder** → **Aplicativos** e dê **dois cliques** no Caça-Cliente.
4. ⚠️ Na primeira vez, o Mac vai mostrar **"O item Caca-Cliente não foi aberto"** (ou "desenvolvedor não identificado"). É normal: o app ainda não tem o certificado pago da Apple. **Clique em OK** — nunca em "Mover para o Lixo" — e libere de um destes jeitos:

   **Jeito 1 — pelos Ajustes** (macOS 15 Sequoia ou mais novo):
   1. Abra **Ajustes do Sistema** → **Privacidade e Segurança**.
   2. Desça até **Segurança** e clique em **Abrir Mesmo Assim**, ao lado de *"O uso de 'Caca-Cliente' foi bloqueado"*.
   3. Digite a senha do Mac e confirme em **Abrir Mesmo Assim**.

   **Jeito 2 — pelo Terminal** (funciona em qualquer versão e resolve também o "app está danificado"):
   1. Abra o **Terminal** (Aplicativos → Utilitários → Terminal).
   2. Cole o comando abaixo, aperte Enter e abra o app de novo:
      ```bash
      xattr -cr /Applications/Caca-Cliente.app
      ```
   Esse comando só tira o aviso de quarentena do download — não mexe no app.

   > No macOS 14 ou mais antigo também funciona **botão direito no app → Abrir → Abrir**.

   Isso só precisa ser feito **uma vez**. Depois, é abrir normalmente.

### 🐧 Linux

1. Baixe o arquivo `.AppImage`.
2. No terminal, na pasta onde baixou:
   ```bash
   chmod +x CacaCliente-*-linux-x86_64.AppImage
   ```
3. Dê **dois cliques** no arquivo (ou rode `./CacaCliente-*` no terminal).

> Se não abrir no Ubuntu/Debian, instale o `libfuse2`: `sudo apt install libfuse2`.

---

## 🔄 Atualizar

- 🪟 **Windows e 🐧 Linux:** quando sair versão nova, o app mostra um **aviso** no topo. É só clicar e ele atualiza sozinho.
- 🍎 **Mac:** o aviso aparece, mas o Mac não atualiza sozinho. Baixe o `.dmg` novo [aqui](https://github.com/d1g4odev/caca-cliente-downloads/releases/latest) e arraste o app pra pasta Aplicativos, por cima do antigo.

> 💡 Atualizar **não apaga seus leads** — eles ficam guardados numa pasta separada do app.

---

## 🧭 Primeiro uso — do clique ao primeiro cliente

### 1. Fazer uma busca

Na barra à esquerda:

1. **Nicho** — digite o tipo de negócio (`barbearia`, `salão de estética`, `dentista`, `restaurante`…) ou escolha um da lista.
2. **Cidade** — comece a digitar e escolha uma opção da lista.
3. **Raio** — arraste a barrinha pra definir o tamanho da área (em km).
4. Clique em **Buscar leads sem site**.

Em segundos, os **pinos aparecem no mapa** e os cartões na lista. Cada pino é um negócio **sem site** que você pode abordar.

> 🏛️ **Cidade pequena?** Se o mapa achar pouca coisa, o app completa com a **base da Receita Federal**. Na primeira busca de cada estado ele baixa essa base (uma vez só, pode levar alguns minutos). Esses leads aparecem com o selo **🏛️ via CNPJ**; o endereço pode estar desatualizado e o e-mail, às vezes, é o do contador da empresa.

### 2. Esperar os contatos chegarem (eles vêm sozinhos)

O app busca os contatos em segundo plano e eles **vão aparecendo nos cartões** (✉️ e-mail, 📷 Instagram, Facebook, LinkedIn). Os pinos mudam de cor conforme isso acontece.

> 👆 Quer prioridade num negócio específico? **Clique nele** — ele fura a fila.
>
> ⏳ Se aparecer **"busca parcial"**, é porque o buscador da internet bloqueou por um tempo. O app tenta de novo sozinho.

### 3. Filtrar e ordenar

Acima da lista você pode **ordenar** por relevância ou nome e **filtrar** só quem tem 📞 WhatsApp, 📷 Instagram ou ✉️ e-mail. Cada lead ganha uma nota de 0 a 100 — quanto mais fácil de contatar, maior:

- 🔴 **Quente** (60+) — vários contatos, vá com tudo.
- 🟡 **Morno** (35–59).
- 🔵 **Frio** (abaixo de 35).

### 4. Anotar e acompanhar

Clique num cartão pra abrir os **detalhes**: todos os contatos encontrados, **anotações** ("liguei dia 12, retornar quinta"), **data de retorno** (o app avisa quando vencer), **valor** estimado da venda e **tags**.

### 5. Abordar no WhatsApp

Clique em **💬 WhatsApp** no cartão. Abre a conversa **com a mensagem já escrita**, personalizada pro ramo do negócio. Você revisa e envia.

> ✏️ Clique em **✏️ Editar mensagem do WhatsApp** (no topo) pra mudar o texto padrão e **trocar `[Seu nome]` pelo seu nome**.
>
> 🚀 **Modo disparo:** no Kanban, marque até 10 leads e clique em **💬 Enviar no WhatsApp**. O app abre uma conversa por vez — você aperta enviar e o lead vai pra "Contatado" sozinho.

### 6. Mover no Kanban até "Ganho"

Clique em **🗂 Kanban** no topo. **Arraste** os cartões entre as colunas conforme a negociação avança:

`Novo · Qualificado · Contatado · Ganho · Descartado`

Quando o cliente fechar, arraste pra **Ganho**. Você fechou seu primeiro cliente. 🎉

### 7. Exportar (opcional)

Em **Exportar**, baixe a planilha em **CSV** ou **Excel** com todos os leads e contatos.

---

## ✨ O que vem no app

- 🗺️ **Mapa interativo** com pinos coloridos por status
- 🔍 **Filtro "sem site"** — descarta quem já tem site
- 🏛️ **Base da Receita Federal** — completa a busca em cidades com pouca cobertura no mapa
- 🧩 **Contatos automáticos** — e-mail, Instagram, Facebook e LinkedIn, chegando em tempo real
- 🗂️ **Funil Kanban** — `Novo · Qualificado · Contatado · Ganho · Descartado`
- ✍️ **Mensagens prontas** por ramo e por etapa do funil
- 🚀 **Modo disparo** — aborda os leads em sequência, você no controle de cada envio
- 📊 **Painel** — conversão do funil e valor em negociação, por nicho e por cidade
- 📤 **Exportação** CSV / Excel
- 💾 **Tudo salvo no seu computador** — nada se perde ao fechar

---

## ❓ Dúvidas comuns

**Vieram poucos resultados.**
- Aumente o raio ou tente uma cidade vizinha. Se for a primeira busca naquele estado, espere a base da Receita terminar de baixar e busque de novo.

**Apareceu "Overpass ocupado" ao buscar.**
- É o serviço de mapas gratuito sob carga. Espere alguns segundos e tente de novo, ou reduza o raio.

**O app abriu mas a tela ficou em branco.**
- Feche e abra de novo. Se continuar, baixe a [versão mais nova](https://github.com/d1g4odev/caca-cliente-downloads/releases/latest).

**O WhatsApp não abre quando clico no botão.**
- Confira se o lead tem telefone. Se tem, veja se o navegador não está bloqueando pop-ups do `wa.me`.

**A mensagem veio com "[Seu nome]" no texto.**
- Clique em **✏️ Editar mensagem do WhatsApp** e coloque o seu nome no lugar.

**Windows: "O acesso a este arquivo foi bloqueado".**
- Botão direito no `.exe` → **Propriedades** → marque **Desbloquear** → **OK**. Depois abra de novo.

**Mac: "O item Caca-Cliente não foi aberto" / "não pode ser aberto" / "está danificado".**
- Clique em **OK** (não em "Mover para o Lixo") e libere em **Ajustes do Sistema → Privacidade e Segurança → Abrir Mesmo Assim**, ou rode `xattr -cr /Applications/Caca-Cliente.app` no Terminal. Detalhes em [Instalar → Mac](#-mac).

**Quero usar com meu sócio.**
- Cada um instala o app no próprio computador. Os leads de cada um ficam salvos localmente.

<details>
<summary><strong>📂 Onde ficam meus dados e como fazer backup</strong></summary>

<br>

| Sistema | Pasta dos dados |
|---|---|
| **Windows** | `%APPDATA%\caca-cliente-desktop\` (ex.: `C:\Users\SeuNome\AppData\Roaming\caca-cliente-desktop`) |
| **Mac** | `~/Library/Application Support/caca-cliente-desktop/` |
| **Linux** | `~/.config/caca-cliente-desktop/` |

**Backup:** feche o app e copie o arquivo `caca-cliente.db` (e, se existirem, `caca-cliente.db-wal` e `caca-cliente.db-shm`) pra um pendrive ou pro Google Drive. Pra restaurar, cole de volta na mesma pasta.

</details>

---

## 💸 Quanto custa?

**R$ 0.** Sem assinatura, sem chave de API, sem cartão. Os dados vêm de fontes públicas e gratuitas: **OpenStreetMap**, **Receita Federal** (dados abertos do CNPJ) e busca pública na internet. Tudo fica salvo no seu próprio computador.

> ⚖️ **LGPD:** os contatos são de empresas e vêm de fontes públicas. Use pra prospecção com respeito — se alguém pedir pra não ser contatado, tire da sua lista.

---

## 🎓 Créditos

<div align="center">

<img src="assets/banner-devjuninho.png" alt="DevJuninho — Sites com IA do Zero" width="400" />

### O Caça-Cliente é a ferramenta oficial do curso **[Sites com IA do Zero](https://instagram.com/devjuninho_)**.

Siga o **DevJuninho** nas redes e fique por dentro do curso:

[![Instagram](https://img.shields.io/badge/Instagram-@devjuninho_-E4405F?logo=instagram&logoColor=white)](https://instagram.com/devjuninho_)
[![X](https://img.shields.io/badge/X-@devjuninho-000000?logo=x&logoColor=white)](https://x.com/devjuninho)

</div>

---

<div align="center">
<sub>Ferramenta oficial do curso <strong>Sites com IA do Zero</strong> · uso exclusivo de alunos — <a href="./LICENSE">licença</a> · dados abertos do OpenStreetMap (ODbL) e da Receita Federal</sub>
</div>
