# AdonisJS mensagens para internacionalização

Esta biblioteca é um simples catálogo de arquivos em JSON contendo mensagens traduzidas para respostas amigáveis do validator do AdonisJS. Sua estrutura de pastas já está organizada e pronta para uso, bastando escolher seu idioma.

## Traduções disponíveis

- **en** Inglês
- **pt** Português

## Referências

1. AdonisJS Framework: [AdonisJS Framework](https://adonisjs.com)
2. AdonisJS Validator: [AdonisJS Validator docs](https://adonisjs.com/docs/4.1/validator)
3. AdonisJS Internationalization: [AdonisJS Internacionalization docs](https://adonisjs.com/docs/4.1/internationalization)

## Instalação

Baixe os arquivos e copie-os para a pasta `resource` no seu projeto.

Quando esse repositório ficar mais maduro, pode ser que justifique transformá-lo em um pacote **npm**, mas não agora.

Não precisa copiar tudo basta o idioma que quizer utilizar!

## Configuração

Altere a opção **locales** no arquivo `config/app.js`:

```javascript
locales: {
    loader: 'file',
    locale: 'en' // (pt, es, etc)
  },
```

## Agradecimentos

Primeiro, um grante **obrigado** à toda equipe do [AdonisJS](http://adonisjs.com/) por esse fenomenal, incrível e maravilhoso framework.

Um obrigado especial ao **Diego Fernantes** da [RocketSeat](https://github.com/Rocketseat) que providenciou o arquivo com as mensagens em inglês e que serviram de base para eu iniciar esse projeto.

### Mais traduções serão bem-vindas!
