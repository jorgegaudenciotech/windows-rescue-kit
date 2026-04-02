# windows-rescue-kit

# 🪟 Windows Command Hub

Comandos úteis e soluções práticas para resolver problemas comuns no Windows.

> 💡 Um guia rápido para troubleshooting, administração e uso no dia a dia.

---

## 📌 Sobre

Este repositório reúne comandos do Windows (CMD e PowerShell) organizados por categoria, com foco em **resolver problemas reais** de forma rápida e prática.

Ideal para:

* 🧑‍💻 Suporte técnico
* 📚 Estudos
* ⚙️ Administração de sistemas
* 👨‍🔧 Uso no dia a dia

---

## 🚀 Comandos rápidos

### 🌐 Corrigir problemas de internet

```cmd
ipconfig /release
ipconfig /renew
ipconfig /flushdns
```

### ⚙️ Verificar integridade do sistema

```cmd
sfc /scannow
```

### 🧱 Reparar imagem do Windows

```cmd
DISM /Online /Cleanup-Image /RestoreHealth
```

### 💾 Verificar e corrigir disco

```cmd
chkdsk /f /r
```

---

## 🛠️ Soluções comuns

### 🔌 Internet não funciona

1. Abra o CMD como administrador
2. Execute:

```cmd
ipconfig /release
ipconfig /renew
ipconfig /flushdns
```

---

### 🐢 Computador lento

```cmd
sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth
```

---

### 💽 Erros no disco

```cmd
chkdsk /f /r
```

---

## 📂 Estrutura do repositório

```
.
├── README.md
├── networking/
├── system/
├── disk/
├── users/
└── troubleshooting/
```

---

## 📘 Como usar

1. Navegue pelas pastas por categoria
2. Abra o arquivo do comando desejado
3. Leia a descrição e exemplos
4. Execute no terminal (CMD ou PowerShell)

> ⚠️ Alguns comandos exigem execução como administrador.

---

## 🧩 Padrão dos arquivos

Cada comando segue um padrão:

* 📌 Descrição
* ⚙️ Uso básico
* 🔥 Exemplos úteis
* 🧠 Quando usar
* ⚠️ Observações

---

## 🤝 Contribuindo

Contribuições são bem-vindas!

1. Faça um fork
2. Crie uma branch (`feature/nome-do-comando`)
3. Commit suas alterações
4. Abra um Pull Request

---

## 🎯 Objetivo

Criar um repositório simples, direto e útil para **resolver problemas no Windows sem perder tempo**.

---

## ⭐ Dica

Use este projeto como um **“kit de primeiros socorros” do Windows**.

---

## 📌 Licença

Este projeto está sob a licença MIT.
