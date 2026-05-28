# Tomasulo Web Simulator

Simulador educacional do algoritmo de Tomasulo com interface em Streamlit.

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

# Instruções

## Implementadas e Testadas:
  - ADDI;
  - ADD;
  - SUB;
  - MUL;
  - DIV;
  
## Não Testadas
STORE
LOAD


## A Ser implementadas:
JMP
BEQ
JAL
RET
NOP
HALT

# RS e FU
- 1 FU para cada RS
- MUL e DIV compartilham a mesma FU