# Estrutras de Dados

## Coleção (array)
Para declarar uma lsita em Ruby, é só usar o colchetes (`[]`):

```ruby
myArray = [3,4,2,1,5,6,2,10]
```
### Adicionando em uma coleção
```ruby
myArray << 5 # [3, 4, 2, 1, 5, 6, 2, 10, 5]

```

### Métodos

#### Ordenação crescente
```ruby
myArray.sort # [1, 2, 2, 3, 4, 5, 6, 10]
```
#### Invertendo a ordem
```ruby
myArray.reverse # [10, 2, 6, 5, 1, 2, 4, 3]
```
#### Removendo duplicados
```ruby
myArray.uniq # [3, 4, 2, 1, 5, 6, 10]
```

#### Combinando métodos
```ruby
# ordena > Inverte > remove duplicados
myArray.sort.reverse.uniq # [10, 6, 5, 4, 3, 2, 1]
```
#### Contar quantos elementos possui o Array
```ruby
myArray.count # 8
```


## Hash
Hash não é uma lista, ele é um "dicionário", ou seja, contém uma `key` e um `value`. Para criar, basta utilizar chaves.
```ruby
myHash = {firstName: 'Raul', surName: 'de Melo'} # {:firstName=>"Raul", :surName=>"de Melo"}
```

Para pegar o valor, basta passar a chave:
```ruby
myHash[:surName] #"de Melo"
```

E caso você passe algo que não existe, retorna um `Nil`!

### Métodos

#### Pegar todas as chaves do Hash
```ruby
myHash.keys #[:firstName, :surName]
```

#### Pegar todas os valores
```ruby
myHash.values #["Raul", "de Melo"]
```

#### Contar quantos elementos possui o Hash
```ruby
myHash.count # 2
```