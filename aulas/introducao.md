# Ruby

É uma linguagem open-source, **interpretada**, com boa sintaxe e multiparadigma.

## GEMS
Ruby Gems, ou gems, não plugins ou bibliotecas que a gente pode compartilhar código para outros porjetos ou usar códigos já criados. Basicamente adiciona comportamento.

## Rails
É uma GEM! ~Música de Mistério~

Logo, pra instala-lo, basta digitar `gem install rails`

## Coisas a se saber

- Rails é uma GEM! :O
- [Instalação do Ruby no Linux](https://gist.github.com/raulfdm/7f6e1e18b7565ba8cc2ec1c8459acfb2)
- IRB = É um terminal Ruby para execução de códigos sem precisar criar arquivos, igual o terminal do node.
- Instrução `puts`: Imprimi algum retorno. Similar ao console log?
- Comentar linha: `#`
- Para receber um parâmetro via execução de código, usa-se `ARGV` (array)
```ruby
nome = ARGV[0]
senha = ARGV[1]

puts "#{nome} e #{senha}"
```

### Comandos
- `gem list`: Retorna todas as Gems
- `ruby -v`: Retorna a versão do ruby instalado (hodor)
- `rails new nome-do-projeto`: Cria um projeto Rails
- `rails s`: Boota um servidor (dentro do projeto)