# Case

```ruby
nome = 'Meir'

case nome
    when 'Raul'     then '14/11/1991'
    when 'Camila'   then '14/06/1990'
    when 'Meir'     then '05/02/1964'
end
```

Da pra fazer comparativos com Range
```ruby
idade = 60

case idade
    when 0..13 then puts 'child'
    when 14..19 then puts 'teenager'
    when 20..35 then puts 'Adult'
    when 36..50 then puts 'Mature'
    when 51..69 then puts 'Older'
    when 70..130 then puts 'Elder'
else puts 'idade inválida'
end
```