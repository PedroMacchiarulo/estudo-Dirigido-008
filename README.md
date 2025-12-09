# PATRI-TECH API

## 🛠️ Sobre o projeto

Este projeto implementa uma API REST usando Django + Django REST Framework para gerenciar unidades, salas, status, bens e categorias.  
O objetivo é fornecer um backend básico de inventário — permitindo criar, listar e manipular dados de “Unidade”, “Sala”, “Status”, “Bem” e “Categoria”.

## 🚀 Tecnologias / Stack

- Python  
- Django  
- Django REST Framework  
- drf_spectacular (para geração de documentação OpenAPI + Swagger)  
- SQLite (banco padrão — pode ser trocado conforme necessidade)

## 📦 Funcionalidades principais

- CRUD para Unidades, Salas, Status, Bens e Categorias.  
- Endpoints REST para listar e criar recursos.  
- Documentação automática da API com Swagger (/docs/).  
- Interface administrativa do Django com modelos registrados (Unidade, Sala, Status, Bem, Categoria).

## 🔧 Como rodar o projeto (local)

1. Clone o repositório  
   ```bash
   git clone https://github.com/PedroMacchiarulo/estudo-Dirigido-008.git
   cd estudo-Dirigido-008
   
2 Crie e ative um ambiente virtual

# Windows (cmd/powershell)
python -m venv venv
venv\Scripts\activate

# Linux / macOS
# python3 -m venv venv
# source venv/bin/activate


3 Instale dependências

pip install -r requirements.txt


4 Execute migrações do banco

python manage.py makemigrations
python manage.py migrate


5 (Opcional) Crie um superusuário para acessar o admin

python manage.py createsuperuser


6 Rode o servidor local

python manage.py runserver


7 Acesse:

API → http://127.0.0.1:8000/api/

Documentação Swagger → http://127.0.0.1:8000/docs/

Django Admin → http://127.0.0.1:8000/admin/

🤝 Contribuição

Contribuições são bem-vindas! Para contribuir, siga:

Fork este repositório.

Crie uma branch com sua feature ou correção (git checkout -b feature/nome-da-feature).

Faça commit das suas mudanças (git commit -m "Descrição da feature/fix").

Faça push para sua branch (git push origin feature/nome-da-feature).

Abra um Pull Request.

📄 Licença

Este projeto está sob a licença MIT — sinta-se livre para usar, modificar e distribuir conforme os termos.
