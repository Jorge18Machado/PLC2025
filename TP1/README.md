TPC1 - Especificação de uma expressão regular

Jorge Miguel Meireles Machado, a85797

![FotoPLC](https://github.com/user-attachments/assets/cebdf399-9cdf-4da0-ab5f-bd6410f3faae)

Expressão Regular:
  ^(?![01]*011)[01]*$

Explicação da expressão regular:
  ^     -> significa o início da string
  ?!    -> negative lookahead: garante que não exista a substring '011' em nenhum lugar da string
  [01]* -> significa que pode haver zero ou mais caracteres antes e/ou depois da substring '011'
  $     -> significa o fim da string

Aqui está a expressão regular aplicada aos exemplos dados pelo professor no Regex101.com:

  <img width="2246" height="944" alt="TPC1PL1" src="https://github.com/user-attachments/assets/5dd6be60-8371-468f-8454-32146f63daee" />
