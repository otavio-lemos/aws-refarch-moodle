# Hosting Moodle on AWS - Forked https://github.com/aws-samples/aws-refarch-moodle

## Overview

Diferenças para o https://github.com/aws-samples/aws-refarch-moodle
- EC2 com t3 e m5;
- Aurora com db.t3.medium;
- ElastiCache com t2 (não existe t3 até a data dessa publicação);
- AMI Amazon Linux 2 para EC2;
- Repositorio Amazon Extras com php7.3;
- Moodle 3.7.2 (última versão até a data dessa publicação);
- Utilizando PHP 7.3.9 no EC2 (última versão até a data dessa publicação);
- Criptografia habilitada para todos os serviços.

Essa estrutura já irá servir para o moodle 4.0 que precisará de php 7.3 (ou superior).

Após a implantação, deve-se habilitar o cloudfront e configurar o memcache no moodle.

Seguir procedimentos oficiais da AWS em https://github.com/aws-samples/aws-refarch-moodle .

Qualquer dúvida entre em contato!

Abs...

