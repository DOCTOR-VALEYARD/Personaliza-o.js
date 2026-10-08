<div align="center">

# 🔴 TERMUX STUDIO 🔴

### ▭❦❲ Personalize a tela inicial do seu Termux ❳❦▭

**🎨 Arte no seu nome · 💻 Prompt estilizado · 🔐 Senha · 👋 Boas-vindas · 🕒 Hora em vermelho**

</div>

```
█████╗█████╗████╗ █╗  █╗█╗  █╗█╗  █╗
╚═█║═╝█║═══╝█║══█╗██╗██║█║  █║╚█╗█╗╝
  █║  ████╗ ████╗╝█║█╗█║█║  █║ ╚█╗╝
  █║  █║══╝ █║═█║ █║╚╝█║█║  █║ █╗█╗
  █║  █████╗█║ ╚█╗█║  █║╚███╗╝█╗╝╚█╗
  ╚╝  ╚════╝╚╝  ╚╝╚╝  ╚╝ ╚══╝ ╚╝  ╚╝

 ████╗█████╗█╗  █╗████╗ █████╗ ███╗
█╗═══╝╚═█║═╝█║  █║█║══█╗╚═█║═╝█╗══█╗
╚███╗   █║  █║  █║█║  █║  █║  █║  █║
 ╚══█╗  █║  █║  █║█║  █║  █║  █║  █║
████╗╝  █║  ╚███╗╝████╗╝█████╗╚███╗╝
╚═══╝   ╚╝   ╚══╝ ╚═══╝ ╚════╝ ╚══╝

 ✦ Doctor Valeyard C'rizz Lunático ✦
 ▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣▣ 100%
```

<div align="center">

| 🟢 Node.js 14+ | 📱 Android / Termux | 📦 0 dependências | 🎨 16 estilos | 🌈 16 cores | 🔐 Senha scrypt | 📜 MIT |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|

👑 **Criado por Doctor Valeyard C'rizz Lunático**

</div>

---

## 📑 Navegação

[🚀 Instalação](#-instalação) · [🖼️ Como fica](#️-como-fica) · [🎨 Estilos](#-os-16-estilos-de-arte) · [🕹️ Como usar](#️-como-usar) · [🔐 Senha](#-segurança-da-senha) · [🗂️ Arquivos](#️-o-que-é-criado-no-seu-termux) · [♻️ Restaurar](#️-restaurar-o-termux-original) · [🛠️ Problemas](#️-solução-de-problemas)

---

## ✨ O que é

O **Termux Studio** troca a tela inicial comum do Termux por uma tela **sua**:

- 🎨 **Seu nome em arte**, em 16 estilos diferentes
- 💻 **Prompt personalizado** no lugar do `$`, no formato `▭❦❲seu texto❳❦▭`
- 🕒 **Hora sempre no topo**, em vermelho
- 🔴 **Tudo que você executa no Termux fica vermelho**
- 🔐 **Senha de entrada** (opcional)
- 👋 **Mensagem de boas-vindas** (opcional)
- 📊 **Barra de carregamento** `▣▣▣▣` mostrando o que está sendo feito
- 🧹 **Terminal organizado**: cada ação limpa a tela e mostra só ela
- 💾 **Salvar e sair**: fica gravado mesmo fechando o Termux

---

## 🚀 Instalação

### ⚡ Comando único (baixa, extrai e já abre)

Copie, cole no Termux e pronto. Não cria pasta: o arquivo é extraído na sua pasta inicial e o Studio **abre sozinho**.

```bash
cd ~ && pkg install -y curl unzip nodejs && curl -fL "https://github.com/DOCTOR-VALEYARD/Personaliza-o.js/raw/main/dvcl-termux-studio.zip" -o dvcl-termux-studio.zip && unzip -ojq dvcl-termux-studio.zip '*termux-studio.js' && rm -f dvcl-termux-studio.zip && node termux-studio.js
```

### 🪜 Passo a passo (separado)

| Passo | O que faz | Comando |
|:--:|---|---|
| 1️⃣ | Vai para a pasta inicial | `cd ~` |
| 2️⃣ | Instala o que precisa | `pkg install -y curl unzip nodejs` |
| 3️⃣ | Baixa o pacote | `curl -fL "https://github.com/DOCTOR-VALEYARD/Personaliza-o.js/raw/main/dvcl-termux-studio.zip" -o dvcl-termux-studio.zip` |
| 4️⃣ | Extrai o programa direto na pasta inicial | `unzip -ojq dvcl-termux-studio.zip '*termux-studio.js'` |
| 5️⃣ | Apaga o zip (opcional) | `rm -f dvcl-termux-studio.zip` |
| 6️⃣ | Abre o Studio | `node termux-studio.js` |

> [!TIP]
> Depois de **Salvar e sair**, o Studio guarda uma cópia própria em `~/.dvcl_termux`. Para abrir de novo, é só digitar `studio` em qualquer lugar do Termux.

> [!NOTE]
> **Atualizar** é rodar o comando único de novo. O `unzip -o` sobrescreve o arquivo antigo e a sua personalização continua salva.

---

## 🖼️ Como fica

### 🏠 Tela de entrada

```
 ◉ 18:03:41  qui 08/10/2026

 ████╗ █╗  █╗ ████╗█╗
 █║══█╗█║  █║█╗═══╝█║
 █║  █║█║  █║█║    █║
 █║  █║╚█╗█╗╝█║    █║
 ████╗╝ ╚█╗╝ ╚████╗█████╗
 ╚═══╝   ╚╝   ╚═══╝╚════╝

 ╔═ BOAS-VINDAS ════════════════╗
 ║ Bem-vindo, DVCL! 🔥          ║
 ╚══════════════════════════════╝
 ✦ Criado por Doctor Valeyard C'rizz Lunático

 ▭❦❲DVCL❳❦▭ _
```

### 🎛️ Painel

```
╔═ PAINEL ════════════════════════════════╗
║ [1] Nome da arte           ▸ DVCL       ║
║ [2] Estilo da arte         ▸ 3. Sombra  ║
║ [3] Cor da arte            ▸ Vermelho   ║
║ [4] Texto do prompt        ▸ DVCL       ║
║ [5] Cor do prompt          ▸ Vermelho   ║
║ [6] Senha de entrada       ▸ ativada    ║
║ [7] Boas-vindas            ▸ ativada    ║
║ [8] Visualizar                          ║
║ [9] Salvar e sair                       ║
║ [0] Sair sem salvar                     ║
║ [R] Restaurar Termux original           ║
╚═════════════════════════════════════════╝
```

### 📊 Barra de carregamento

```
╔═ SALVANDO ══════════════════╗
║ ▣▣▣▣▣▣▣▣▣▣▣▣▣▢▢▢▢▢▢▢▢▢  57% ║
╚═════════════════════════════╝
 ➤ Aplicando ao .bashrc ...
```

---

## 🎨 Os 16 estilos de arte

Cada estilo aparece no painel já com o nome que a pessoa digitou. Toque para abrir:

<details>
<summary>🧱 <b>1. Bloco sólido</b></summary>

```
████  █   █  ████ █
█   █ █   █ █     █
█   █ █   █ █     █
█   █  █ █  █     █
████    █    ████ █████
```

</details>

<details>
<summary>🌫️ <b>2. Bloco com fundo ░</b></summary>

```
████░░█░░░█░░████░█░░░░░
█░░░█░█░░░█░█░░░░░█░░░░░
█░░░█░█░░░█░█░░░░░█░░░░░
█░░░█░░█░█░░█░░░░░█░░░░░
████░░░░█░░░░████░█████░
░░░░░░░░░░░░░░░░░░░░░░░░
```

</details>

<details>
<summary>🌑 <b>3. Sombra ANSI (╗ ═)</b></summary>

```
████╗ █╗  █╗ ████╗█╗
█║══█╗█║  █║█╗═══╝█║
█║  █║█║  █║█║    █║
█║  █║╚█╗█╗╝█║    █║
████╗╝ ╚█╗╝ ╚████╗█████╗
╚═══╝   ╚╝   ╚═══╝╚════╝
```

</details>

<details>
<summary>🌒 <b>4. Sombra ANSI com fundo ░</b></summary>

```
████╗░█╗░░█╗░████╗█╗░░░░
█║══█╗█║░░█║█╗═══╝█║░░░░
█║░░█║█║░░█║█║░░░░█║░░░░
█║░░█║╚█╗█╗╝█║░░░░█║░░░░
████╗╝░╚█╗╝░╚████╗█████╗
╚═══╝░░░╚╝░░░╚═══╝╚════╝
```

</details>

<details>
<summary>🧊 <b>5. 3D extrusão</b></summary>

```
████  █   █  ████ █
█▒▒▒█ █▒  █▒█ ▒▒▒▒█▒
█▒  █▒█▒  █▒█▒    █▒
█▒  █▒ █ █ ▒█▒    █▒
████ ▒  █ ▒  ████ █████
 ▒▒▒▒    ▒    ▒▒▒▒ ▒▒▒▒▒
```

</details>

<details>
<summary>🌈 <b>6. Degradê ▓░</b></summary>

```
▓▓▓▓░ ▓░  ▓░ ▓▓▓▓░▓░
▓░░░▓░▓░  ▓░▓░░░░░▓░
▓░  ▓░▓░  ▓░▓░    ▓░
▓░  ▓░ ▓░▓░░▓░    ▓░
▓▓▓▓░░  ▓░░  ▓▓▓▓░▓▓▓▓▓░
 ░░░░    ░    ░░░░ ░░░░░
```

</details>

<details>
<summary>⚫ <b>7. Pontos ●</b></summary>

```
●●●●  ●   ●  ●●●● ●
●   ● ●   ● ●     ●
●   ● ●   ● ●     ●
●   ●  ● ●  ●     ●
●●●●    ●    ●●●● ●●●●●
```

</details>

<details>
<summary>⭐ <b>8. Estrelas ★</b></summary>

```
★★★★  ★   ★  ★★★★ ★
★   ★ ★   ★ ★     ★
★   ★ ★   ★ ★     ★
★   ★  ★ ★  ★     ★
★★★★    ★    ★★★★ ★★★★★
```

</details>

<details>
<summary>💎 <b>9. Diamantes ◆</b></summary>

```
◆◆◆◆  ◆   ◆  ◆◆◆◆ ◆
◆   ◆ ◆   ◆ ◆     ◆
◆   ◆ ◆   ◆ ◆     ◆
◆   ◆  ◆ ◆  ◆     ◆
◆◆◆◆    ◆    ◆◆◆◆ ◆◆◆◆◆
```

</details>

<details>
<summary>📦 <b>10. Caixas ▣</b></summary>

```
▣▣▣▣  ▣   ▣  ▣▣▣▣ ▣
▣   ▣ ▣   ▣ ▣     ▣
▣   ▣ ▣   ▣ ▣     ▣
▣   ▣  ▣ ▣  ▣     ▣
▣▣▣▣    ▣    ▣▣▣▣ ▣▣▣▣▣
```

</details>

<details>
<summary>💖 <b>11. Corações ♥</b></summary>

```
♥♥♥♥  ♥   ♥  ♥♥♥♥ ♥
♥   ♥ ♥   ♥ ♥     ♥
♥   ♥ ♥   ♥ ♥     ♥
♥   ♥  ♥ ♥  ♥     ♥
♥♥♥♥    ♥    ♥♥♥♥ ♥♥♥♥♥
```

</details>

<details>
<summary>#️⃣ <b>12. Hash ##</b></summary>

```
####  #   #  #### #
#   # #   # #     #
#   # #   # #     #
#   #  # #  #     #
####    #    #### #####
```

</details>

<details>
<summary>✳️ <b>13. Asteriscos **</b></summary>

```
****  *   *  **** *
*   * *   * *     *
*   * *   * *     *
*   *  * *  *     *
****    *    **** *****
```

</details>

<details>
<summary>📏 <b>14. Barras ||</b></summary>

```
||||  |   |  |||| |
|   | |   | |     |
|   | |   | |     |
|   |  | |  |     |
||||    |    |||| |||||
```

</details>

<details>
<summary>〰️ <b>15. Traços //</b></summary>

```
////  /   /  //// /
/   / /   / /     /
/   / /   / /     /
/   /  / /  /     /
////    /    //// /////
```

</details>

<details>
<summary>🌊 <b>16. Ondas ~~</b></summary>

```
~~~~  ~   ~  ~~~~ ~
~   ~ ~   ~ ~     ~
~   ~ ~   ~ ~     ~
~   ~  ~ ~  ~     ~
~~~~    ~    ~~~~ ~~~~~
```

</details>

🌈 São também **16 cores** para a arte e **16 cores** para o prompt, incluindo **Arco-íris**.

---

## 🕹️ Como usar

1. ✍️ Digite o **nome** que vai virar arte.
2. 🎨 Escolha o **estilo** (1 a 16) e a **cor**.
3. 💻 Escolha o **texto do prompt** (vai dentro de `▭❦❲ ❳❦▭`) e a cor dele.
4. ⚙️ No **painel**, configure senha e boas-vindas e use **[8] Visualizar**.
5. 💾 Escolha **[9] Salvar e sair**, feche o Termux e abra de novo.

### 🧭 Menu do painel

| Tecla | Ação |
|:-----:|------|
| `1` | ✍️ Nome da arte |
| `2` | 🎨 Estilo da arte (16) |
| `3` | 🌈 Cor da arte |
| `4` | 💻 Texto do prompt (substitui o `$`) |
| `5` | 🖌️ Cor do prompt |
| `6` | 🔐 Senha de entrada |
| `7` | 👋 Mensagem de boas-vindas |
| `8` | 👁️ Visualizar |
| `9` | 💾 Salvar e sair |
| `0` | 🚪 Sair sem salvar |
| `R` | ♻️ Restaurar Termux original |

### 💬 Variáveis da mensagem de boas-vindas

| Variável | Vira |
|----------|------|
| `{nome}` | 🏷️ O nome escolhido |
| `{hora}` | 🕒 A hora atual |
| `{data}` | 📅 A data atual |

---

## 🔐 Segurança da senha

- 🔒 A senha **nunca** é guardada em texto puro.
- 🧂 O Studio grava só um *hash* **scrypt** com sal aleatório.
- 🚫 São **3 tentativas**; errou as 3, o Termux fecha.

---

## 🗂️ O que é criado no seu Termux

| 📄 Arquivo | 🧩 Função |
|---------|--------|
| `~/.dvcl_termux/config.json` | Suas escolhas |
| `~/.dvcl_termux/boot.sh` | Define PS1, cores e chama a tela inicial |
| `~/.dvcl_termux/termux-studio.js` | Cópia do programa |
| `~/.dvcl_termux/bashrc.backup` | Backup do seu `.bashrc` original |
| `~/.bashrc` | Recebe um bloco marcado que carrega o `boot.sh` |
| `~/.hushlogin` | Oculta a mensagem padrão do Termux |

💾 A personalização **fica salva**. Só some se você formatar o celular, reinstalar o Termux ou restaurar pelo painel.

---

## ♻️ Restaurar o Termux original

No painel, escolha **`R`** e digite `SIM`. Isso remove o bloco do `.bashrc` e apaga a pasta `~/.dvcl_termux`.

> [!WARNING]
> Esqueceu a senha? Restaure o backup do `.bashrc`:
>
> ```bash
> cp ~/.dvcl_termux/bashrc.backup ~/.bashrc
> ```

---

## 🛠️ Solução de problemas

| ⚠️ Problema | ✅ Solução |
|---|---|
| `curl: (22) ... error: 404` | O link está errado ou o `dvcl-termux-studio.zip` não está na raiz do repositório, no branch `main` |
| `End-of-central-directory signature not found` | O arquivo baixado não é um zip. Rode o comando de novo |
| `node: command not found` | Rode `pkg install -y nodejs` |
| `unzip: command not found` | Rode `pkg install -y unzip` |
| A arte quebra em mais de uma linha | Normal em telas estreitas. Gire o celular ou diminua a fonte do Termux |
| Cores de `git`, `pkg` ou `ls --color` não ficam vermelhas | Esses programas usam cor própria. O Studio força vermelho no prompt, no que você digita e na saída comum |

---

## ⚠️ Observações

- 🐚 Funciona com **bash** (padrão do Termux).
- 🧼 No texto do prompt, os caracteres `\ $ ` ' "` são removidos por segurança.
- 🔤 Nomes aceitam letras (acentos viram a letra sem acento na arte), números, espaço e `- _ . !`, até 20 caracteres.

---

<div align="center">

### 👑 Créditos 👑

**Doctor Valeyard C'rizz Lunático**

▭❦❲ feito para o Termux ❳❦▭

</div>
