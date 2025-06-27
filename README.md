# 🏨 Sistema de Hospedagem - DIO .NET

### Desafio de Projeto - Trilha .NET - Módulo: Explorando a linguagem C#

[![Badge](https://img.shields.io/badge/DIO-Projeto%20.NET-blue.svg)](https://www.dio.me/)

---

## 📌 Descrição

Este projeto consiste em um sistema de **reserva de hospedagens**, desenvolvido como parte do desafio da **Digital Innovation One (DIO)**, no módulo *Explorando a linguagem C#* da trilha .NET.

O sistema simula o processo de reserva em um hotel, com **validações de capacidade**, **cálculo de valor da diária**, e **controle de hóspedes e suítes**. O objetivo é reforçar conceitos fundamentais da linguagem C#, como orientação a objetos, encapsulamento e estruturas de dados básicas (`List`, `if`, `foreach`, etc.).

---

## 🧠 Tecnologias Utilizadas

- C#
- .NET 6.0 ou superior
- Visual Studio / VS Code
- Git & GitHub

---

## 📁 Estrutura do Projeto

- `Pessoa.cs` - Representa um hóspede, com nome e sobrenome.
- `Suite.cs` - Representa uma suíte, com tipo, capacidade e valor da diária.
- `Reserva.cs` - Responsável por gerenciar o relacionamento entre hóspedes e suíte, além de calcular o valor total e validar a reserva.
- `Program.cs` - Ponto de entrada do sistema, simula o uso da aplicação.

---

## ✅ Funcionalidades

- ✅ Cadastrar hóspedes e suíte.
- ✅ Validar capacidade da suíte com base na quantidade de hóspedes.
- ✅ Calcular valor total da hospedagem.
- ✅ Conceder **10% de desconto** em reservas com **10 ou mais dias**.
- ✅ Exibir lista de hóspedes e total de dias reservados.

---

## 📏 Regras de Negócio

- Não é permitido reservar uma suíte com **capacidade menor** que a quantidade de hóspedes.
- O método `ObterQuantidadeHospedes()` retorna o número de hóspedes cadastrados.
- O método `CalcularValorDiaria()` retorna o valor total com ou sem desconto, dependendo do número de dias reservados.

---
