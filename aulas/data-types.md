# Tipos de Dados no Ruby

Ruby é uma linguagem dinamicamente tipada, ou seja, para atribuir uma varável, basta fazer uma **atribuição**, declarando o nome da variável e seu valor:

```ruby
nome = 'Raul Felipe de Melo'
```

Todo variável é um objeto, logo, podemos chamar métodos relacionados ao tipo, mesmo declarando algo "primitivamente".

```ruby
# String possui um método upcase (upper case)
"raul felipe de Melo".upcase
# "RAUL FELIPE DE MELO"
```

Assim como no javascript, é possível torcar o tipo de dado da variavel sem problemas:
```ruby
nome = "raul felipe de Melo"
puts nome # "raul felipe de Melo"
nome = 10
puts nome # 10
```


Para validar qual o tipo do objeto, basta usar o método class (`variavel.class`) e será retornado o tipo.

## String

### Concatenção
No Ruby, é possui concatenar através de template string (olha aiiii):

```ruby
primeiroNome = "Raul Felipe"
segundoNome = "de Melo"
nomeCompleto = "#{primeiroNome} #{segundoNome}"

puts nomeCompleto

# Raul Felipe de Melo
```

## Numbers
Diferente do Javascript, aqui o float e o interger tem diferença:

```ruby
1.class # Integer
1.4.class # Float
```

## Boolean
O `true` possui uma classe própria chamada `TrueClass` e o `false` possui a classe chamada `FalseClass`.

Para fazer comparações, basta usar `==`:
```ruby
1==1 #true
```

Negação funciona da mesma forma de sempre:
```ruby
1 != 1 #false
```

## null
Em ruby, null é representado por `nil` e também possui sua propria classe `NilClass`:

```ruby
nil.class #NilClass
```

### Métodos
Converter para inteiro:
```ruby
nil.to_i # 0 -> vira 0 (integer)
nil.to_s # "" -> Vira string vazia
nil.to_f # 0.0 -> Vira 0.0 (float)
```