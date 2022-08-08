# backEnd-Insta
BackEnd do instagram , projeto desenvolvido pela empresa


- login do usuário ✅
    
    Esse endpoint deve receber o email e a senha para validar o usuário
    
- cadastro do usuário ✅
    
    Este endpoint recebe nome , nicknome , email , fotoDePerfil e senha
    
    **No perfil do usuario vai ter a bio. Como o usuario esta criando a conta , ela por padrão por vir vazia e ele preencher dps q criar a conta**
    
- Stories ✅
    
    Este endpoint deve retorna um conjunto de fotos que a pessoa inseriu no stories.
    
    - O stories deve durar 24hr. Após esse tempo , ele é apagado.
    - O stories aparece só para as pessoas que eu sigo.
    
    **OBS: As fotos do stories é diferente das fotos de post**
    
- Feed ✅
    
    Este endpoint deve retornar os post dos usuários , com os likes e os comentários.
    
    **Importante**
     - **Só deve retornar os feed das pessoas que eu sigo.**
     - **O post deve ter um horário , informando quando que a pessoa criou o post (Assim aparece 2H no post. Este valor deve ser assíncrono , ao ponto de quanto o tempo passar , essa hora vai alterando)**
    
    - Um post pode ter mais de uma foto.
    - Os comentários devem ter id , descrição , id de quem comentou , imagemPerfil de quem comentou.
    - Os likes devem ser sincronizados com o front. A partir do momento que a pessoa do front clicar em like , ele incrementa no back.
- criar post ✅
    
    Este endpoint cria um post. Ele vai ter:
    
    - id
    - foto
    - descrição
    - array de tags [#sports , #cinema]
    
    **As hashtag servem para o filtro de buscar as imagens pela hashtag**
    
- imagens de procura ✅
    
    Este Endpoint retorna todas as imagens através da hashTag informada
    
- informações de likes e follow ✅
    
    Este endpoint deve informar quando a pessoa começou a te seguir e quando ela deu like. E assim:
    
    - retornar a imagem da pessoa que começou a te seguir e quando ela começou a te seguir.
    - retornar a imagem da pessoa que te deu like , qual foto ela deu like e quando ela deu like
- perfil ✅
    
    Este endpoint deve retornar todas as informações do usuario.
    
    - Quantos post ele tem
    - Quantas pessoas ele segue
    - Quantas pessoas o seguem
    - Foto , nome e bio.
