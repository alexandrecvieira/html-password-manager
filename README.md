# HTML Password Manager

Adaptado de [Helpful Sheep - HTML password manager](https://helpfulsheep.com/2012-01-20-html-password-manager/)

Utiliza a [Stanford Javascript Crypto Library](https://github.com/bitwiseshiftleft/sjcl) para criptografar as senhas

Para Salvar as alterações clique no botão Salvar, não tente usar a opção de menu **Arquivo / Salvar** do navegador para salvar as alterações(não funciona)

Para refazer o logon tecle **F5**

Para Resetar a senha Mestra, Digite no lugar da senha: **reset**

Os campos **Mensagem Secreta** e **Dado de Autenticação** são opcionais, são utilizados como chaves adicionais para encriptar as senhas

ATENÇÃO: Se a senha Mestra for resetada, todas as senhas serão perdidas e deverão ser recadastradas. Tenha sempre uma cópia de **backup** deste arquivo.

## CHANGELOG

### [Unreleased]

### [hpm_0.6] - 2020-06-14
* Mobile device detection
* Allow to save only the master password
* Bug in the save function
* Improved indentation
* Line break on table

### [hpm_0.5] - 2020-06-10
* Search feature improved
* Save button
* Other interface improvements

### [hpm_0.4] - 2019-07-13
* Unified release V0.4: fields for optional settings: salt and adata

### [en_0.3] - 2019-07-12
* Improved master password screen, hiding password by default and button to show password | Visibility of statusIndicator
