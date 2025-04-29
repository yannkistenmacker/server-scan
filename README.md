# 📡 IP Scanner App

Um aplicativo simples em Go para escanear e exibir o **endereço IP público** e os **servidores DNS** de um domínio.  
A simple Go app to scan and display the **public IP address** and **DNS servers** of a domain.

---

## 📝 Descrição · Description

**🇧🇷 Português:**  
Este é um pequeno aplicativo escrito em Go que permite obter o **endereço IP público** e os **servidores DNS** de um domínio informado. É leve e útil para diagnósticos rápidos de rede, testes ou fins educacionais.

**🇺🇸 English:**  
This is a small tool written in Go that retrieves the **public IP address** and **DNS servers** of a given domain. It’s lightweight and useful for quick network diagnostics, testing, or learning purposes.

---

## ✅ Funcionalidades · Features

- 🌐 Exibe o IP público de um domínio.  
  Displays the public IP of a domain.

- 🧭 Mostra os servidores DNS configurados.  
  Shows the configured DNS servers.

- ⚡ Interface simples, leve e rápida.  
  Simple, lightweight, and fast interface.

---

## ▶️ Como Usar · How to Use

Execute os seguintes comandos no terminal:  
Run the following commands in your terminal:

```bash
go run ip.go --host example.com.br
go run servidores.go --host example.com.br
