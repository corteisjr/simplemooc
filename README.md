# SimpleMOOC - Ensino a distância
[![Build Status](https://travis-ci.org/paulopinda/simplemooc.svg?branch=master)](https://travis-ci.org/paulopinda/simplemooc)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/19176ed01baa477b9221033f85eadfa6)](https://www.codacy.com/app/paulo-pinda/simplemooc?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=paulopinda/simplemooc&amp;utm_campaign=Badge_Grade)

Plataforma de ensino a distância com foco em cursos abertos utilizando Django para o seu 
desenvolvimento. O projeto foi concluído no curso de "Python 3 na Web com Django".

Foi utilizado neste projeto Python 3.5.1 e Django 1.9.6.

### Instalação no Linux
Antes de executar o script abaixo, instale a última versão do Pyenv.

```bash
git clone https://github.com/paulopinda/simplemooc.git
cd simplemooc 
./scripts/setup.sh 
source .venv/bin/activate
python manage.py test 
python manage.py runserver
```