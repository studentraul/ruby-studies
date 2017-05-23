# Condicionais

## if
Podemos escrever a instrução em blocos
```ruby
number = 1
if 1>0
    puts 'True'
    end
```

Ou inline
```ruby
number = 1 
puts 'true' if number == 1
# true
```

## Else
```ruby
age = 18
if age < 20
    puts 'Teenager'
else
    puts 'Adult'
end
```

## Else if
ATENÇÃO: É **ELSIF** e não **ELSEIF**!!

```ruby
age = 18
if age < 20
    puts 'Teenager'
elsif age >= 20 && age <22
    puts 'Almost Adult'
else
    puts 'Adult'
end
```

## Unless
Unless é uma particularidade do Ruby, que é igual o `if`, mas é invertido:
```ruby
puts 'true' unless number == 1
# Nil
```

Em suma, será avaliado:
> Faça X, a menos que Y condição seja atendida

## Ternário

```ruby
age = 19;
age<20 ? puts('teenager') : puts('Adult')

# Outra forma de fazser a mesma coisa
puts(age<20 ? 'teenager' : 'Adult')

# Outra maneira
puts "the person is #{age<20 ? 'Teenager' : 'Adult'}"
```

## E
Normal, utilizando `&&`:
```ruby
if 18<19 && true == true
    puts 'Vai tomar no cu'
else
    puts 'Brinks'
end
```

## OU
Normal, utilizando `||`:
```ruby
if 18<18 || true == false
    puts 'Vai tomar no cu'
else
    puts 'Brinks'
end
```