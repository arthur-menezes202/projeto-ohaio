# projeto-ohaio
o projeto ohaio é bem simples, um site onde estudantes de japonês possam praticar e decorar hiraganas, o projeto inicial visa apenas uma pratica simples

# Como Funciona
Um simbolo aparece em um campo, e então, são gerados 4 botões, onde um deles é a resposta certa, inicialmente, o limite é de 10 tentativas, mas atualizações serão feitas e o limite sera da escolha do usuário.

# Quando Fica Pronto?
Ainda não tenho um data prevista, estou me dedicando no mínimo uma hora por dia, acredito eu que ao fim de dezembro o projeto já esteja concluído.

# Tecnologia Utilizadas
o projeto sera desenvolvido com REACT, utilizando redux, um arquivo json para manter as informações sobre japonês, jest para fazer teste unitários, e bibliotecas de css, como bootstrap e Material-ui para que o site possa ser usado em celulares, computadores ou tablets.

# estruração do arquivo json
A estruturação é bem simples:
```javascript
[
    {
      "simbolo": "あ",
      "romaji": "a",
      "imagem": "a.png"
    },
    {
      "simbolo": "い",
      "romaji": "i",
      "imagem": "i.png"
    }
]
```
É composto por três campos, contem o simbolo, romaji(tradução), e por fim a imagem que ira aparecer, esta é a ideia inicial, esta sujeito a alterações.