# Criando o ambiente de testes:

### Aulas de consulta
 - https://github.com/fiapsecdevops/classroom/blob/master/labs/travis/01-lab-integration.md
 - https://github.com/fiapsecdevops/classroom/blob/master/labs/travis/02-lab-dockersetup.md


```
    pip install virtualenv
    virtualenv lab
    source lab/Scripts/activate
    pip install -r requirements.txt
    python -m pytest -v tests/test_generator.py

```

---

# Travis(SAAS) vs Jenkins(OFFLINE)

**Travis**

Vantagem:
- Sem instalação;
- Consomecomo SVC;

Desvantagem:
- Segurança(expor código, precisa confiar no prestador de CI);

**Jenkins**

Vantagem:
- Segurança controlada;
- OpenSource;

Desvantagem:
- Instalaçã trabalhosa;
- Disponibilidade (apenas local);

