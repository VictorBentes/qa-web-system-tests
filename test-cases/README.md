# Casos de Teste

Esta pasta contém os casos de teste realizados no sistema web.

# Caso de Teste - Cadastro com Dados Válidos

## ID

CT-002

## Objetivo

Validar cadastro utilizando informações válidas.

## Passos

1. Acessar tela de cadastro
2. Preencher todos os campos obrigatórios
3. Inserir dados válidos
4. Clicar em salvar

## Resultado Esperado

Sistema deve realizar cadastro com sucesso.

## Resultado Atual

Cadastro realizado corretamente.


# Caso de Teste - Cadastro com Dados Fictícios

## ID

CT-003

## Objetivo

Validar comportamento do sistema utilizando dados fictícios.

## Passos

1. Acessar tela de cadastro
2. Inserir dados fictícios nos campos
3. Finalizar cadastro

## Resultado Esperado

Sistema deve validar corretamente os campos e impedir dados inválidos, caso necessário.

## Resultado Atual

Cadastro realizado corretamente.


# Caso de Teste - Validação de CNPJ Incompleto

## ID

CT-004

## Objetivo

Validar comportamento do sistema ao inserir CNPJ incompleto.

## Passos

1. Acessar tela de cadastro
2. Inserir CNPJ com quantidade insuficiente de números
3. Tentar finalizar cadastro

## Resultado Esperado

Sistema deve impedir o cadastro e apresentar mensagem de validação.

## Resultado Atual

O sistema identificou corretamente o CNPJ incompleto e bloqueou o cadastro.

## Status

Aprovado


Caso de Teste - Preenchimento Automático de Endereço via CEP
ID

CT-005

Objetivo

Validar preenchimento automático de endereço através do CEP informado.

Passos
Acessar tela de cadastro
Inserir um CEP válido
Aguardar carregamento automático dos dados
Resultado Esperado

Sistema deve preencher automaticamente os campos de endereço corretamente.

Resultado Atual

O sistema preencheu automaticamente os dados do endereço de forma correta após inserção do CEP.

Status

Aprovado
