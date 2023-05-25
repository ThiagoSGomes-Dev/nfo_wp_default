# Padrões de codificação do WordPress (WPCS)

* Padrões de codificação do WordPress (WPCS).
* PHP_CodeSniffer (PHPCS).
* Revisão de código de pares.
* Segurança 🛡️.
* Esquema de documentação do WordPress.

## Padrões específicos de idioma

* [Padrões de codificação CSS](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/css/).
* [Padrões de Codificação HTML](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/html/).
* [Padrões de Codificação JavaScript](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/javascript/).
* [Padrões de Codificação PHP](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/php/).

## Padrões de Acessibilidade

* O WordPress está comprometido em atender às [Diretrizes de Acessibilidade de Conteúdo da Web (WCAG) no nível AA](https://www.w3.org/TR/WCAG20/)

* [guia rápido para problemas comuns de acessibilidade](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/accessibility/)

finished :round_pushpin:

## PHP_CodeSniffer (PHPCS)

* [Recursos recomendados](https://learn.rtcamp.com/courses/wordpress-development/l/coding-standards-and-best-practices/t/php-codesniffer-phpcs/)

### instruções que funcionou para mim

* Verifique a versão atual do Composer:

  ```bash
        composer --version
  ```

  Isso exibirá a versão atual do Composer instalada em seu sistema.

* Execute o seguinte comando para atualizar o Composer:

  ```bash
        composer self-update
  ```

  Isso baixará e instalará a versão mais recente do Composer em seu sistema, Após a atualização ser concluída, verifique novamente a versão do Composer.

:warning: executar o terminal com privilégios de administrador

## Para instalar o PHP CodeSniffer (PHPCS) em sua máquina local

* Execute o seguinte comando para instalar globalmente o PHPCS:

  ```bash
        composer global require "squizlabs/php_codesniffer=*" 
  ```

* Para verificar se a instalação foi concluída com sucesso, execute o seguinte comando:

  ```bash
        phpcs --version
  ```

  Isso exibirá a versão do PHPCS instalada em sua máquina.

## Instalar WPCS e PHPCompatibilidade

* Para instalar o WordPress Coding Standards (WPCS) e o PHPCompatibility, você pode seguir estes passos:

* Certifique-se de ter o Composer instalado em sua máquina. Se você não tiver o [Composer instalado](https://getcomposer.org/), para obter instruções sobre como instalá-lo.

* Instale o WordPress Coding Standards (WPCS) globalmente executando o seguinte comando:

  ```bash
       composer global require wp-coding-standards/wpcs
  ```

* Em seguida, instale o PHPCompatibility globalmente com o seguinte comando:

  ```bash
       composer global require --dev phpcompatibility/phpcompatibility-wp
  ```

Certifique-se de que o diretório de binários do Composer está no seu caminho de sistema. Dependendo do sistema operacional e das configurações, isso pode variar. Geralmente, o diretório binário do Composer está localizado em `~/.composer/vendor/bin` (Linux/Mac) ou `C:\Users\{nome de usuário}\AppData\Roaming\Composer\vendor\bin` (Windows).

* Agora você pode configurar o PHPCS para usar as regras do WPCS e do  PHPCompatibility. Para isso, execute o seguinte comando no terminal:

  ```bash
       phpcs --config-set installed_paths ~/.composer/vendor/wp-coding-standards/wpcs,~/.composer/vendor/phpcompatibility/php-compatibility
  ```

Certifique-se de ajustar o caminho ~/.composer/vendor se necessário, de acordo com a localização correta em seu sistema.

## Instalar os padrões de codificação WPCS e VIP

* Você pode instalar os padrões de codificação WPCS e VIP por meio do repositório git, segue o [Link](https://learn.rtcamp.com/courses/wordpress-development/l/coding-standards-and-best-practices/t/php-codesniffer-phpcs/).

finished :round_pushpin:

## Revisão de código de pares

* [Revisão de código: por que é importante por Brad Capeau-Laurion](https://www.youtube.com/watch?v=2AX7Awm6wZU)

finished :round_pushpin:

## Segurança 🛡️

* [Link learn](https://learn.rtcamp.com/courses/wordpress-development/l/coding-standards-and-best-practices/t/security/)

finished :round_pushpin:

## Esquema de documentação do WordPress

* [Link learn](https://learn.rtcamp.com/courses/wordpress-development/l/coding-standards-and-best-practices/t/wordpress-documentation-schema/)

finished :round_pushpin:

:construction: Documentação em construçao! :construction:
