# Projeto Sistemas Operativos - Fase 2

## Identificação

**Grupo 10** <br>
Daniela Camarinha 58199 <br>
Diogo Lopes 60447<br>
Pedro Silva 59886<br>

---
## Diretórios

O projeto hOSpital está dividido nos seguintes diretórios:
- ```bin```: que contém o ficheiro executável
- ```include```: que contém os ficheiros com a extensão .h
- ```obj```: que contém os ficheiros objeto .o
- ```src```: que contém os ficheiro fonte .c

---
## Execução

Para compilar: <br>

```bash
make clean
```
```bash
make
```
2. executar programa com:
```bash
./bin/hOSpital config.txt
```
---
## Limitações
É passada à função create_shared_memory os parâmetros corretos, devido a razões alheias ao nosso conhecimento, o buffer comm, na sua inicialização é inicializado muda tamanho e por isso, multiplicamos um valor arbitrário (1000) para serem criadas mais slots no buffer e assim poderem ser usadas as inicialmente passadas como parâmetro.
Pelo que o fluxo normal do programa mantêm-se.
 <br>

