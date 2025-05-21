# 🏦 Sistema Bancário em Python - POO

## 📌 Sobre o Projeto
Este sistema bancário é desenvolvido em **Python**, utilizando conceitos de **Programação Orientada a Objetos (POO)** para tornar o código mais organizado e modularizado. Ele permite que usuários realizem operações bancárias como **depósitos, saques e consultas de extrato**, além de **cadastrar clientes e criar contas bancárias**.

O código foi estruturado para ser **interativo**, com um **menu dinâmico** que guia o usuário através das funcionalidades do sistema.

---

## 📁 Estrutura do Projeto

```shell
bank-system-POO/
│── bank.py                # Arquivo principal que contém o loop do menu
│── README.md              # Documentação do projeto
```
## 🚀 Funcionalidades<br>
🔹 Operações Bancárias
✅ Depositar: Usuário pode inserir valores e atualizar saldo.<br> ✅ Sacar: Verifica saldo disponível, limite por saque e número máximo de saques. <br>✅ Exibir Extrato: Lista todas as movimentações financeiras.<br>

🔹 Gerenciamento de Clientes<br>
✅ Criar Usuário: Nome, data de nascimento, CPF e endereço são cadastrados.<br>✅ Evita CPFs duplicados: Garante que não haja clientes repetidos no sistema.<br>

🔹 Gerenciamento de Contas<br>
✅ Criar Conta Corrente: Vincula um cliente do banco à conta, gerando um número sequencial. <br>✅ Listar Contas: Exibe todas as contas bancárias existentes.

🔄 Melhorias Implementadas<br>

## 📌 Uso de Programação Orientada a Objetos (POO)<br>
✔️ Melhor organização do código. <br>✔️ Modularização através de funções que permitem reutilização do código.
<br>
##📌  Sistema Interativo<br>
✔️ Menu dinâmico para facilitar a navegação do usuário. <br>✔️ Mensagens informativas que garantem uma melhor experiência.

##📌  Validação e Segurança<br>
✔️ CPF armazenado corretamente para evitar erros na busca de clientes.<br> ✔️ Verificação de duplicidade de CPF ao criar clientes.

## 🎯 Como Executarv
1️⃣ Baixe o projeto ou clone via GitHub:
git clone https://github.com/VBDOL/bank-system-POO.git
cd bank-system-POO
2️⃣ Execute o arquivo principal (main.py):
python main.py
3️⃣ Utilize o menu interativo para operações bancárias!
[d] Depositar  
[s] Sacar  
[e] Extrato  
[nc] Nova conta  
[lc] Listar contas  
[nu] Novo usuário  
[q] Sair  
