# Tomasulo Web Simulator

Simulador educacional do algoritmo de Tomasulo com interface em Streamlit.

## Interface web:
acesso via: [Inserir Link](http://)

## Execução via terminal:
Rodar o codigo completo do processador, incluindo a execução dos testes, diretamente pelo terminal:
```powershell
python -m femTomas.processor
```

Rodar o código do processador com configuração default e o arquivo de teste
```powershell
python -m femTomas.processor -d -t
```

Rodar o Streamlit localmente para acessar a interface web:
```powershell
streamlit run femTomas/app.py
```

# Características:

# Registradores
- 8 Registradores: R0-R7
- R0 é sempre zero (hardwired)
- Renaming Table (RAT) implementada
# Instruções

## Implementadas e Testadas:
  - ADDI;
  - ADD;
  - SUB;
  - MUL;
  - DIV;
  - STORE
  - LOAD
  - HALT
  - NOP

## A Ser implementadas:
JMP
BEQ
JAL
RET

# Reserve Stations e Functional Units
- 1 FU para cada RS
- MUL e DIV compartilham a mesma FU